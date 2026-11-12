---
title: "Answers: Chapter 4, exercise C3"
permalink: /teaching-the-book/exercises/ch04-c3-answers/
---

# Answers: Chapter 4, exercise C3, "Find what is wrong"

*Finish your search before you read this. These answers are for practice and for checking yourself. If your
instructor grades C3, they will give you a fresh pair of answers to search. Matches exercise C3 in
[the Chapter 4 set](ch04-using-ai-well-and-badly.md) (book v6.1.1).*

Each answer has three planted errors, each of a kind Chapter 4 names. Everything else in both answers is correct.
The "Not errors" lists cover the likely false alarms.

## Summary

| | Answer | Where | Error | Kind (Chapter 4) |
|---|---|---|---|---|
| S1 | Statistics | Opening sentence; Step 3 | A two-sample test on paired data. Independence is never checked. | Unstated condition; wrong method (4.4, "Independence you cannot ignore") |
| S2 | Statistics | Opening sentence; Reference | A real source cited for a claim it does not make | The harder citation failure: real, but says something else (4.3.3) |
| S3 | Statistics | Step 6 | "No effect" from a non-significant result, in causal language | Conclusion stronger than the evidence (4.3.4; 4.4.4) |
| P1 | Python | `range(1, n - 1)`; the Check | The loop skips the last interior point. The test never reaches the loop. | Code that runs and is wrong (4.3.5) |
| P2 | Python | Accuracy | The error is proportional to h², not h | Confident wrong statement |
| P3 | Python | For real work | `math.integrate` does not exist | Made-up function (the code version of 4.3.3) |

## Answer 1: statistics

### S1. The wrong test for the design

**Where.** The first sentence ("We compare the two sets of scores with a two-sample t-test") and Step 3, which
checks normality only.

**What is wrong.** Both sets of scores come from the same eight students. They are paired, not independent. The
two-sample t-test assumes two independent groups, and Step 3 never mentions independence.

**Why it matters.** Pairing removes the large differences between students. In the two-sample test those
differences inflate the standard error (1.02) and hide a rise that is nearly uniform: seven of eight students
went up, and none went down. This is the chapter's own example in Section 4.4: "Normality you can often bend.
Independence you cannot ignore." The arithmetic in Steps 2, 4, and 5 is right for the test chosen. That is the
chapter's point that an AI "will run the test either way and hand back a number that looks the same."

**Fix.** Use a paired t-test on the differences (after minus before): 2, 1, 1, 2, 0, 3, 1, 2. Mean 1.50, standard
deviation 0.926, standard error 0.926 / √8 = 0.327, t = 4.58 with 7 degrees of freedom, two-sided p = 0.0025.
The condition is now that the differences are roughly normal. They are: they run from 0 to 3, symmetric about
1.5, with no outliers.

**How students catch it.** The first step in Section 4.4's order: is it still the problem asked, with the same
assumptions? The data table pairs each student's two scores. Among the six questions, Method and Assumptions.

### S2. A real source that does not say this

**Where.** The first sentence ("the test Student (1908) introduced for comparing the means of two groups") and
the Reference line.

**What is wrong.** The reference is real and correct: Student (1908), "The probable error of a mean,"
*Biometrika* 6(1), 1-25. But the paper does not present a test for two independent groups. Its best-known worked
example, the Cushny and Peebles sleep data, takes the difference between two drugs for each patient and analyzes
those differences. That is the paired approach. The source exists, and it supports the opposite of the use made
of it.

**Kind.** The harder of the two failures in Section 4.3.3: a source that is real "and says something other than
the summary reports." A check that stops at "the reference exists" passes it.

**Fix.** Drop the attribution, or cite Student (1908) for what it does: the distribution of the mean of a small
sample, illustrated with paired differences. The course textbook is a fine citation for the paired t-test.

**Credit.** Full credit needs the student to say what the paper actually does, which means opening it (it is
widely reprinted). Give partial credit to a student who flags the claim as unverified and says what they would
check. Do not credit "the citation is fake." It is real; that is the lesson.

### S3. A conclusion the test cannot support

**Where.** Step 6, second sentence: "The flashcard app has no effect on quiz scores."

**What is wrong.** Two faults.

1. Failing to reject H0 is not evidence that H0 is true. With eight students the test had little power. The
   honest wording, for the test used, is "no evidence of a change at the 0.05 level."
2. "Effect" is causal. The design has no comparison group, so even a significant change cannot be credited to
   the app. The question asked whether scores changed. The answer concluded something else.

**Kind.** A conclusion more certain than the evidence (Section 4.3.4: "Is the level of certainty right?") and a
causal claim from a descriptive design (Section 4.4.4).

**Fix.** With the paired test: "Scores rose by 1.5 points on average (paired t = 4.58, df = 7, two-sided
p = 0.003). The data show a change. They cannot show that the app caused it. There is no comparison group, and
practice on the first quiz, or a difference between the two quizzes, could explain the rise."

**Credit.** Credit either fault; full credit for both. A student who fixes S1 and then writes "the app improved
scores" has repeated half of S3.

### Not errors in Answer 1

- **Step 2.** Before: the squared deviations sum to 28, so the variance is 4.00 and the SD is 2.00. After: they sum
  to 30, so the variance is 4.29 and the SD is 2.07.
- **Step 4.** Pooled SD = √((28 + 30) / 14) = 2.035, which rounds to 2.04. SE = 1.018, which rounds to 1.02. t = 1.474,
  which rounds to 1.47. Fourteen degrees of freedom is right for the pooled test.
- **Step 5.** p = 0.163 for t = 1.474 with 14 df. It rounds to 0.16.
- **Step 1.** The hypotheses are fine. For paired data they are equivalent to "the mean difference is zero."
- **Step 3.** Its description of both samples is accurate. The fault is what it leaves out (S1).
- **Two-sided.** The problem asks for a two-sided test.
- **Pooled versus Welch.** With equal group sizes, Welch's test gives the same t (df about 13.98, p = 0.163). That
  is not the issue.

## Answer 2: Python

### P1. The loop skips a point, and the test cannot see it

**Where.** `for i in range(1, n - 1):`, and the Check paragraph.

**What is wrong.** The interior points are a + i·h for i = 1, ..., n - 1. But `range(1, n - 1)` stops at n - 2,
so f(b - h) is left out. The code runs and returns a plausible number. For f(x) = x on [0, 1] it returns 0.25 at
n = 2 and 0.3125 at n = 4; the exact value is 0.5. For f(x) = x² on [0, 1] with n = 100 it returns 0.32355 instead
of 0.33335.

**The check.** The test is real: with n = 1 the code does return 2.0. But with n = 1 the loop never runs, in the
broken version or the fixed one, so the test cannot see the bug. "The function is correct" does not follow.
Count the weak test as part of P1. Credit a student who names it separately.

**Kind.** Section 4.3.5: code can run and still be wrong. The chapter says to "test it on simple cases where you
know the answer." The answer did test, on a case that never reached the faulty line.

**Fix.** `for i in range(1, n):`. Then f(x) = x on [0, 1] gives 0.5 for every n. And x² on [0, 1] with n = 4 gives
0.34375: the integral is 1/3, and the trapezoid error h²/6 is 0.0104.

### P2. The wrong order of accuracy

**Where.** The Accuracy paragraph.

**What is wrong.** For f with a continuous second derivative, the composite trapezoid error is
-(b - a) h² f''(ξ) / 12 for some ξ in [a, b]. It is proportional to h², not h. Doubling n cuts the error by about
four, not two.

**Fix.** "For smooth f, the error is proportional to h², so doubling n cuts it by about a factor of four."

**Discussion note: the two errors hide each other.** Run the "change one thing" practice from Section 4.4 on the
code as written, and the false claim looks confirmed. For x² on [0, 1], the broken code's errors at n = 100, 200,
and 400 are 9.78e-3, 4.95e-3, and 2.49e-3, falling by about two per doubling. The missing term f(b - h)·h is first
order in h, so the bug makes the code first order. After the fix, the errors are 1.67e-5, 4.17e-6, and 1.04e-6,
falling by exactly four. A student who measured the broken code's convergence did a real check on the wrong
thing. Section 4.4 warns against "a precise validation of the wrong thing." Fix the code before you test claims
about it.

A second trap: for sin x on [0, π], f(b) = 0, so the missing term is of order h². The broken code's error then
also falls by about four per doubling (1.14e-1, 2.87e-2, 7.19e-3 at n = 10, 20, 40, against 1.65e-2, 4.11e-3,
1.03e-3 when fixed). A convergence test there hides the bug. A comparison with the exact value, 2, does not.

### P3. A function that does not exist

**Where.** The "For real work" paragraph.

**What is wrong.** Python's `math` module has no `integrate` function. Calling it raises `AttributeError: module
'math' has no attribute 'integrate'` (checked in Python 3.13). The standard library has no general numerical
integration routine. The added detail, "applies the same rule and chooses n for you," describes a function that
does not exist.

**Kind.** A made-up function: the code version of an invented source (Section 4.3.3), and a reason to "read it
line by line" (Section 4.3.5).

**Fix.** Use the corrected function, or a library routine that exists. `scipy.integrate.quad(f, a, b)` does
adaptive quadrature, not the trapezoid rule, and returns a value and an error estimate.
`scipy.integrate.trapezoid(y, x)` applies the trapezoid rule to sampled values, not to a function. NumPy 2.0 and
later has `numpy.trapezoid`.

### Not errors in Answer 2

- **`h = (b - a) / n`.** Python 3 division gives a float, even for integer inputs.
- **No check for n < 1.** The docstring says n >= 1. A guard is good practice, but its absence is not an error.
- **The weights sentence.** One half at the ends and one inside is the correct rule. The code fails to apply it
  to one point (P1).
- **The Check's output.** The call does return 2.0. The fault is the conclusion drawn from it.
- **`return total * h`.** Correct.

## Using these answers in class

Go through the errors in the order Section 4.4 gives for verifying, and ask which step catches each one.

- **Same problem (step 1).** S1 (the assumptions changed: paired data, independent-groups test) and S3 (the
  conclusion changed: the question asked about a change, the answer concluded about the app).
- **The hard step (step 2).** P1. The loop is the only line that does real work, and the check never ran it.
- **Sources and shape (step 3).** S2, P3 (a library function is a source too), and P2 (an unsupported claim).
- **Local details (step 4).** None of the six. The arithmetic is right throughout.

This matches the chapter's remark that many fabrications "fail the first two checks, before any algebra." It
also explains the most common false alarm: students who start with local details recompute Steps 2 to 5, find
them correct, and stop.

## Verification record

- **Statistics.** Python 3.13, SciPy 1.18.1. `scipy.stats.ttest_ind` (pooled): t = 1.474, df = 14, p = 0.163.
  Welch: t = 1.474, df = 13.98, p = 0.163. `scipy.stats.ttest_rel`: t = 4.583, df = 7, p = 0.00254.
- **Python.** The function was run exactly as printed in the exercise, alongside the fixed version. Every output
  in this key comes from that run. `hasattr(math, "integrate")` is False in Python 3.13. `scipy.integrate.quad`,
  `scipy.integrate.trapezoid` (SciPy 1.18.1), and `numpy.trapezoid` (NumPy 2.5.3) exist.
- **Student (1908).** The paired analysis of the Cushny and Peebles data, with its column of differences
  ("2 - 1"), was checked against a reproduction of Student's table and analysis in J. Hanley's course notes:
  https://jhanley.biostat.mcgill.ca/bios601/Mean-Quantile/First.t.test.pdf. The same source states that
  Student's paper does not test two independent groups. E. L. Lehmann, "'Student' and Small-Sample Theory"
  (UC Berkeley Statistics technical report 541), likewise describes one of Student's three examples as a paired
  comparison reduced to one sample by taking differences, and dates the two-sample solution to 1922:
  https://statistics.berkeley.edu/sites/default/files/tech-reports/541.pdf.
