# Claim audit ledger, draft v2_108_2

This ledger lists corrections made to printed claims during the 2026 pre-publication audit of the manuscript. Each claim was checked against its own sources, the book's equations, or a recomputation with the book's own models and code. Each row is a finding the authors ruled on, with the version of the draft in which the correction landed. The current draft is v2_108_2. Wording-only style fixes, such as dashes and punctuation, are not listed.

Chapter and section numbers are those of the printed book. Values are given as the check measured them.

## Printed Chapters 10, 11, 12, 17, 19 and 20 (RG-200, landed v2_91_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-200.1 | Ch 11, Sections 11.7 and 11.8, summary item 5 | Gave a proportional-mixing herd-immunity formula attributed to Anderson and May (1985), with a threshold of 0.614, above the uniform 0.575. | The formula is not in the cited paper and contradicts the section's own uniform result. At 0.614 the case study still has Re = 0.909. Coverage weighted by contact rate needs a total of 0.379, less than uniform. | Replaced by contact-weighted coverage: 0.38 on the case study, between the uniform 0.575 and the cheapest allocation's 0.19, with a closed form under proportionate mixing. The citation moved to the minimum-total paragraph, which the paper supports; summary item 5 follows. |
| RG-200.2 | Ch 20 text and Figs. 20.1 and 20.2; Ch 19 Scenario 1 and summary | Chapter 20 used HIV's additive total: R0 1.70, condoms 0.91, ART 0.17, population average 0.45, sensitivity weights 0.93 and 0.07. Chapter 19's Scenario 1 used 0.012 for the vertical term. | Chapter 19 makes the spectral radius rho(K) the threshold quantity. Under it the values are 1.64, 0.85, 0.16 and 0.44, the weights 0.96 and 0.04, and the vertical term 0.008. No scenario changes side of 1. | rho(K) used throughout Chapters 19 and 20, in the text and both figures. Scenario 1 uses 0.008. Chapter 19's summary gives the vertical share as 4 percent, its weight under rho(K). |
| RG-200.3 | Ch 10, Section 10.2, SIRS endemic formula | Presented the formula with "one finds", without saying when it holds. | It is exact only for equal contact rates. With the book's rates it falls short by 0.27, 1.33 and 2.60 percent for mean immunity of 5 years, 1 year and 180 days. | Stated for equal contact rates, with a note that with the book's rates it is within 3 percent. |
| RG-200.4 | Ch 12, gonorrhea case study; Ch 19, delta-method interval | Chapter 12 printed 0.0621/0.018 as 3.46 and a treated value of 0.42. Chapter 19 printed the interval [0.97, 2.31]. | The division gives 3.45, and the treated value is 0.41 at the unrounded removal rate. 1.64 times (1 plus or minus 1.96 x 0.211) is [0.96, 2.32]. | 3.45 and 0.41 in Chapter 12; [0.96, 2.32] in Chapter 19. |
| RG-200.5 | Ch 17, growth equation; Ch 10, Section 10.3 | Chapter 17 wrote the growth equation with r and a capital I, the only such use in the book. Chapter 10 repeated Section 5.3's next-generation calculation without saying so. | A notation left over from a symbol change, and an unmarked overlap. | The growth rate is written sigma with the book's prevalence symbol. Section 10.3 gains one back-reference to Section 5.3. |

## Printed Chapters 1 and 2, and the end-of-chapter exercise notes (RG-209, landed v2_93_3)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-209.2 | Ch 1, Section 1.4.3, lab exercise | Compared the linear and exact transmission probability only at the baseline, where R0 runs from 4.6 to 24, and asked for the final size 1 - S(infinity)/N. | The epidemics saturate there, which hides the difference. With births and deaths S(infinity) is the endemic level, not a final size. At a matched R0 of about 1.92 the linear form overstates peak prevalence by 13, 40 and 93 percent. | Asks for the size of the first wave, and adds a repeat of the comparison with R0 matched to about 1.92. |
| RG-209.3 | Ch 1, Section 1.7, Ex. 7(a) | Called lambda an aggregate quantity in people per unit time. | The book's Section 3.4 defines lambda per susceptible; lambda S is the aggregate. | Rewritten: lambda S = alpha I is the aggregate rate, and the reader states the units of lambda. |
| RG-209.4 | End-of-chapter note on section-level exercises, in printed Chapters 1, 3, 4, 7, 13, 14, 15, 18, 19 and 20 | Each note gave a count and list of the exercise sets above it. | The count or the list was wrong in 10 of 17 chapters, because sets were added after the notes were written. | Each note regenerated from the actual sets, with an automated check so a new set cannot leave a note stale. |
| RG-209.5 | Ch 2, Section 2.4, Ex. 1 | Used a per-minute rate rho = 0.05. | At that rate every listed contact duration overstates beta by more than 10 percent (the threshold is 3.9 minutes), so the question has no contrast. | rho = 0.005 per minute: errors of 1.3 to 33 percent, crossing between 30 and 60 minutes. |

## Printed Chapter 5 (RG-211, landed v2_94_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-211.1 | Section 5.6, proof of Theorem 5.5 (general case) | The Routh-Hurwitz argument used printed coefficients a2 and a3 and an inequality (iii), A*B* + gamma_R C* > 0. | The printed a2 and a3 are not the coefficients of the characteristic polynomial, and (iii) is false: -4.47 x 10^-7 at the baseline, and negative in 2,651 of 17,293 random parameter sets with R0 > 1. The theorem itself holds. | Coefficients corrected; (iii) replaced by C* < 0, which the section already shows; a corrected factorization of a1 a2 - a3. Checked symbolically and against a numerical Jacobian of the book's model. |
| RG-211.2 | Section 5.8, Ex. 6 | Asked the reader to show that the false inequality (iii) holds. | Follows from RG-211.1. | The reader verifies the corrected coefficients, then evaluates the quantity at the baseline and finds it negative: a lesson in checking a lemma numerically. |
| RG-211.3 | Section 5.6, equal-contact case, Jacobian | Printed the (2,1) entry of the Jacobian incorrectly. | The entry is nu_m(R0 - 1). The printed matrix did not give the (correct) polynomial printed below it. | Entry corrected. |

## Printed Chapter 6 (RG-213, landed v2_94_1)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-213.1 | Section 6.2 | Said a horizon of 10,000 days is enough to come within 10^-5 of equilibrium. | The largest deviation is 9.2 x 10^-2 at 10,000 days; the trajectory is within tolerance only after 60,000 days, because the recurrent epidemics damp slowly. | Says more than 60,000 days are needed and points to the closed form as the efficient check. |
| RG-213.2 | Section 6.9, Ex. 2 | Said two forms agree to within 3 x 10^-13. | Contradicts Section 6.5; measured 1.7 x 10^-16 and 8.9 x 10^-16. | "Agree to round-off (about 10^-16)". |
| RG-213.3 | Section 6.9, Ex. 9(c) | Said prevalence peaks near 0.01 and that default solver tolerances give peak times wrong by 5 to 10 percent. | The peak is 0.174. Default tolerances shift the peak time by 0.14 percent and its height by 0.42 percent. | Peak about 0.17; default tolerances differ in the third significant figure, enough to fail a four-digit comparison. |
| RG-213.4 | Section 6.9, Ex. 8, bug 3 | A step size of 5 days, described as longer than tau_R. | tau_R is 12 days. At 5 days Euler's method stays positive; at 15 days a component goes negative. | Step size of 15 days. |
| RG-213.5 | Section 6.2, AI Lab box, step 3; Section 6.9, Ex. 8(c) | Checked a simulation against the conservation-law peak and the final size, and said a gap above 1 percent points to a mismatch. | Both are equal-contact results. A correct simulation at the baseline misses them by 20.2 and 5.6 percent. | Checks Re = 1 at the simulated peak and the endemic equilibrium instead, and says the two formulas hold only for equal contact rates. |

## Printed Chapter 7 (RG-215, landed v2_94_2)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-215.1 | Section 7.3 caution; Fig. 7.5 caption; Section 7.8, Ex. 12(b) | Said that when the generation time is shorter than tau_R*, the exponential-period conversion underestimates R0. | The direction is reversed. The book's own Section 15.5 example gives 1.46 against the true 1.30, an overestimate. | "Overestimates" in all three places, with the reason stated. |
| RG-215.2 | Section 7.3, worked example | Said three parameter sets give trajectories "not close, but equal to within numerical tolerance" in the growth phase. | Incidence differs by 0.27 percent after 10 days, 1.7 percent after 30 and 12 percent after 60. | Indistinguishable early, separating by about 2 percent after 30 days and 12 percent after 60, where the depletion phase carries information about c_I. |
| RG-215.3 | Section 7.8, Ex. 6(a) | Said endemic prevalence is sensitive to R0 through a factor that diverges as D goes to 0. | The derivative vanishes as D goes to 0, while the elasticity stays near 1.09. | Asks why the derivative vanishes while the relative sensitivity stays of order one. |
| RG-215.4 | Section 7.2, Ex. 2 (and Ex. 3) | Said the companion repository provides a real surveillance dataset. | No such dataset is staged; the chapter's series is synthetic. On 60 days the weekly peak also splits between frequency bins. | Uses the chapter's synthetic series or any public daily series, and tells the reader to trim to whole weeks. |
| RG-215.5 | Section 7.8, Ex. 10 | Asked for residual autocorrelation at lags of 1, 2, 7 and 30 days on weekly data. | Daily lags do not exist in weekly data, and nine points leave almost no pairs at 30 days. | Lags of one, two and four observations (weeks). |

## Printed Chapter 8 (RG-219, landed v2_95_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-219.1 | Section 8.3; Table 8.1; Section 8.5, delay example | Read a generation time of 1.91 days as the data's, giving R0 = 1.37 (2.58 for 3.6 days). The delay example used a growth rate of 0.19 per day and a 44 percent bias. | The chapter's series grows at 0.0761 per day, which gives 1.15, 1.27 and 1.38 for generation times of 1.91, 3.6 and 5 days. The delay bias at that rate is 20 percent. In the model the generation time equals tau_R*, so Table 8.1 set two priors on one quantity. | The text says the data fix the growth rate, not R0, and gives the three values. A note under Table 8.1 says the generation-time row is not a second prior. The delay example uses the series' rate (20 percent), with the 0.19 case kept as a contrast. |
| RG-219.2 | Section 8.2, Ex. 3 | Asked the reader to show that a population-size term in the delta-method interval is nonzero. | Under the consistent conversion the elasticity is 0; for an incidence-only fit it is -0.041 or -0.153, not -1. | The reader shows the term vanishes, then estimates the incidence-only elasticity from the chapter's figure. |
| RG-219.3 | Fig. 8.3 and caption; Section 8.3, AI box | The profile-likelihood figure was drawn from a formula plus noise but captioned as computed on the chapter's series. The box's multistart rule accepted a fit on a parameter bound. | Computed, the profile with tau_R free is flat from 0.1 to 100 seeds. All 20 starts converge to the lower bound on tau_R. | Figure regenerated from the computed profile, with the tau_R penalty in the right panel (about 2.5 to 13 index cases). The box adds that a cluster on a bound is a boundary solution, not an estimate. |
| RG-219.4 | Section 8.5, AI box, structural verification | Its one-line test showed the ascertainment rate rho cancelling even when it changes. | With prevalence built from past reports, the estimate doubles on the day rho doubles and relaxes over about 11 days. | Rewritten: rho cancels only if incidence and prevalence are ascertained by the same factor at the same time. |
| RG-219.5 | Ch 8 exercises | The chapter's 24 exercises printed unnumbered, the only chapter to do so. | A reader could not cite them. | Numbered within each section, as in every other chapter. |
| RG-219.6 (1) | Section 8.1, Ex. 1 | Gave data that imply R0 = 0.75. | The outbreak is declining, which the exercise did not address. | Numbers kept; the exercise asks whether the outbreak is growing and what that says about when the estimate measures R0. |
| RG-219.6 (2) | Section 8.1, Ex. 3 | A population-size range of 15,000 to 30,000. | No crossing occurs in that range. | Range of 10,000 to 40,000, matching the chapter's figure. |
| RG-219.6 (3) | Section 8.2, AI box | Called the delta-method formula exact for separately estimated parameters. | It is a first-order approximation. | "Valid, to first order". |
| RG-219.6 (4) | Section 8.8, Ex. 1 | "The plateau median". | Algorithm 1 uses the mean. | "The plateau mean". |
| RG-219.6 (5) | Section 8.7 and its Ex. 1 | Wrote the stage thresholds as prevalence. | They are cumulative-incidence fractions. | Restated as cumulative incidence (3 to 6 percent; about 75 percent). |

## Printed Chapters 8 and 9 (RG-222, landed v2_96_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-222.1 | Ch 9: Table 9.1, Section 9.3.6, Section 9.7 tables and text, the endemic-prevalence panels of four figures | Classed the contact rates c_S and c_R as negligible for endemic prevalence I*, to be neglected in first-order analyses. | Those are equal-contact results. In the general model their elasticities are +0.52 and -0.52, burden parameters at the chapter's threshold of 0.5. The equal-contact formula is accurate at the baseline only because c_S = c_R there; with c_R = 4, I* is 72 percent higher. | General values in the table, the text and both partition tables; Section 9.3.6's reason restated; the four figure panels regenerated from the general formula. |
| RG-222.2 | Section 9.9, Ex. 1 | Called the estimator asymmetry "the sensitivity-theoretic justification" of the fitting-advantage claim. | The block it cites calls it one half of the argument. | "Only the sensitivity-theoretic half", and the exercise asks for the other half. |
| RG-222.3 | Section 9.9, Ex. 8(b) and (c) | (b) said two estimates should agree; (c) named tau_R and tau_m as acting linearly. | (b) fails for c_S and c_R. tau_m is as curved as c_I, because I* scales as 1/tau_m. | (b) compares c_S and c_R with the general indices; (c) names tau_R and explains tau_m. |
| RG-222.4 | Section 9.8, Check Your Work, check 2 | "If the top ranks change, M was too small." | Fails for ties: c_I, beta and tau_R are tied for R0, and their order never settles as M grows. | Adds an exception for parameters tied within their sampling error. |
| RG-222.5 | Ch 8, Section 8.8, Open Project | "The plateau median". | Algorithm 1 and Section 8.8 Ex. 1 use the mean. | "Mean". |
| RG-222.6 | Ch 8 summary | Wrote the Stage 2 threshold with the prevalence symbol. | Section 8.7 now uses cumulative incidence. | "A cumulative incidence of about 3 to 6 percent". |

## Printed Chapters 9 and 10 (RG-225, landed v2_96_1)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-225.1 | Ch 10, Section 10.2, Ex. 2 | Asked students to show two endemic equilibria below R0 = 1 (a backward bifurcation) for reinfection factor theta between 0 and 1. The force formula was garbled, and it cited a modeling pathology that appears nowhere in the book. | Impossible for theta at most 1; a scan of 225 cases found no equilibrium below threshold. One appears only for theta above a critical value, about 1.004 (10-year immunity) or 1.013 (1-year) at the baseline. | Restated: show the bifurcation is forward for theta at most 1, then find the critical theta above 1. The stray citation is dropped. |
| RG-225.2 | Ch 10, Section 10.7, Ex. 1 | Asked for "the four ingredients". | The section lists five. | "Five". |
| RG-225.3 | Ch 9, partition schematic, caption | Said c_I and beta sit in the invasion-only region and affect I* only weakly. | The chapter's table classes them as mixed, with an I* index of 1.09. | Unit sensitivity for R0 and about 1.09 for I*: invasion-dominant at this baseline. |
| RG-225.4 | Ch 9, partition schematic, labels | The labels of c_I and beta overlapped, and tau_m's label overlapped "burden". | The labels could not be read. | One shared label for the shared point; class labels moved clear. No data change. |
| RG-225.5 | Ch 10, Section 10.8, Ex. 11(a) | Called the late-time behavior a plateau at the new endemic equilibrium. | After five years prevalence still swings by 33 percent of its mean. | Uses the average over the fifth year, and describes the approach as a damped oscillation. |

## Printed Chapter 11 (RG-227, landed v2_96_2)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-227.1 | Section 11.2, Eq. 11.4 and the sentence after Eq. 11.5 | Defined each group's contact pool by summing its rates over every group's state. A sentence read "N^c_k is approximately N^c_k". | Read literally, Eq. 11.4 does not reduce to Eq. 11.9: at the disease-free state it gives 0.0940 and 0.0802 per day, where the next-generation form gives 0.300 and 0.120. | The pool is defined pairwise, as the contacts group k directs at group j. Eq. 11.4 then reduces exactly under equal contact rates, and the sentence is corrected. |
| RG-227.2 | Section 11.6; Section 11.9, Ex. 4 | "All three quantities cross the threshold value 1 together." | True of R0 and the cycle number C0, false for the stage numbers. In Ex. 4's example R0 crosses 1 at beta = 0.0341, the stage numbers at 0.0278 and 0.0418. | R0 and C0 cross together; a stage number can sit below 1 while the infection invades. Ex. 4 asks for that range of beta. |
| RG-227.3 | Section 11.9, Ex. 8 | Asked students to verify that the ratio of the two groups' estimates matches the row ratio of the mixing matrix. | Early in an epidemic both groups give the same rate: the simulated ratio is 0.989, against the rows' 2.50. | Asks why the two estimates agree early, and where in the data the mixing matrix does leave a trace. |
| RG-227.4 | Section 11.9, Ex. 3 | "Double the assortativity parameter to 0.6". | The case study's value is 0.35. | "Raise the assortativity parameter to 0.6" (R0 from 2.35 to 2.66). |
| RG-227.5 | Section 11.8 | Said disassortative mixing can make a population-averaged calculation overestimate R0. | The comparison used a plain average. Under balance, with common transmission and removal rates, the size-weighted average never exceeds the true value (a Rayleigh-quotient argument); 20,000 random matrices agree. | States that the averaged rate never overestimates R0 and matches it only when every group makes the same number of contacts. Worked example: 2.00 against 1.60. The convexity sentence is dropped. |
| RG-227.6 | Section 11.3 | Deferred the endemic-equilibrium details to "Exercise 2". | The closed-form equilibrium is Ex. 1. | The reference points to Ex. 1. |
| RG-227.7 | Section 11.1 | Said this chapter extends its techniques to m-group models. | The multigroup extension is in Chapter 12, Section 12.5. | Points to Chapter 12 for sexual transmission and the multigroup model, and to the vector-host chapter. |
| RG-227.8 | Section 11.9, Ex. 7 | Called the assortativity value 0 "proportional mixing". | In the case-study construction only group 1's row is then proportional; balance fixes group 2's. | "Group 1 mixing in proportion to group size". |
| RG-227.9 | Section 11.9, note on the exercises | "Four section-level retrieval exercises appear above." | There are five, and one is a derivation, not retrieval. | "Five section-level exercises appear above". |

## All chapters: the exercise notes (RG-228, landed v2_96_3)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-228.1 | End-of-chapter note on section-level exercises, 17 chapters | Each note counted exercise sets, not exercises, and called them all "retrieval" exercises. | The reader counts exercises. The count was wrong in about a dozen chapters, and "retrieval" in most. | Each note counts exercises and drops "retrieval", as in Chapter 11. An automated check enforces the rule. |

## Printed Chapter 12 (RG-229, landed v2_96_4)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-229.1 | Section 12.7, sensitivity to contact rate; summary item 4; Section 12.8, Ex. 4 | Gave an elasticity of R0 to the male-female contact rate of 1/2, so halving contacts cuts R0 by 29 percent, and explained weak behavioral interventions by "square-root dampening". | The chapter's balance equation ties the two directions' contact rates together, so halving contacts halves R0: the elasticity is 1. The 1/2 holds only for one-sided parameters, such as a per-contact probability. | Rewritten: the sensitivity to contact rate is 1, and the square root halves only the sensitivity to one-sided parameters. The summary and Ex. 4 follow. |
| RG-229.2 | Section 12.4.1, reader note; summary item 5 | "All four cross 1 together." | The stage numbers need not. Lowering beta, the female-to-male number falls below 1 while R0 is still above it. | R0 and the cycle number cross together; the stage numbers need not. |
| RG-229.3 | Section 12.4.1, reader note | Gave literature values for untreated gonorrhea without a source, inconsistent with an uncited range in Section 12.4.2. | The two ranges conflict. The chapter's own parameters give 3.3 to 3.5 per generation and 10.8 to 12.0 per cycle. | The note uses the chapter's own numbers (about 3.3 per generation, 11 per cycle). |
| RG-229.4 | Section 12.8, Ex. 3 | Called 0.5 contacts per day "10 times higher" than the general population's rate. | 0.1 per week is 0.014 per day, so 0.5 is 35 times higher. | "About 35 times higher". |
| RG-229.5 | Section 12.7, endemic equilibrium | Applied the equal-beta formula to the case study's unequal beta: 71 percent prevalence in each sex. R0 appeared as both 3.45 and 3.46. | Solving the coupled system gives 68.3 percent of males and 73.7 percent of females. | Says 71 percent would hold with equal beta, and gives about 68 and 74 percent, with R0 = 3.45. |
| RG-229.6 | Section 12.2, force of infection | Defined the susceptible fraction as an approximation for compartment-independent contact rates. | With the pairwise pool adopted in Chapter 11, the equality is exact. | Uses Chapter 11's pairwise pool; the equality is exact for compartment-independent rates. |

## Printed Chapter 13 (RG-231, landed v2_96_5)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-231.1 | Section 13.6 list and text; Sections 13.4.3 and 13.5.2; Fig. 13.3 caption; summary item 4; Section 13.4, Ex. 1 | Gave the sensitivity of R0 to vector mortality as -1/2, named the biting rate the most sensitive parameter, and called biting-rate reduction the most cost-effective intervention. | The case study puts survival through the extrinsic incubation period into transmission, so mortality enters twice: -1/2(1 + mu_v tau_v^E) = -1.10. Doubling mortality cuts R0 to 1.01; halving the biting rate, to 1.30. A sensitivity does not show cost-effectiveness. | Vector mortality (about -1.1) is the most sensitive parameter, then the biting rate. A sensitivity to the incubation period (about -0.6) is added. The cost-effectiveness claim is removed. |
| RG-231.2 | Section 13.4.1 | "All four quantities cross the threshold 1 together." | At the case study the stage numbers are 15.0 and 0.452: one is below 1 while R0 = 2.6. | R0 and the cycle number cross together; the stage numbers need not. |
| RG-231.3 | Sections 13.4.3 and 13.5.3 | Said that reducing the susceptible and infected exposure weights by the same factor recovers unit sensitivity. | The weights are relative. Halving both leaves R0 unchanged; protecting susceptibles alone raises it by a factor of 1.414. | Only preventing bites, which lowers the biting rate, has unit sensitivity; redirecting bites changes the weights. |
| RG-231.4 | Section 13.7, Ex. 4; Section 13.3 | Asked the reader to show that the explicit incubation compartment and the effective transmission probability give the same R0. | They agree only with exponential-sojourn survival. At the case study they give 3.196 and 2.602. | Ex. 4 states the condition and asks for the difference. Section 13.3 names the survival form it uses. |
| RG-231.5 | Section 13.7, Ex. 11(b) | Said that omitting incubation survival overestimates R0 by 1/p_EIP, about 2. | R0 scales as the square root of p_EIP, so the factor is 1.65. 1/p_EIP = 2.72 applies to the cycle number. | About 1.6 for R0, about 2.7 for the cycle number. |
| RG-231.6 | Section 13.6.2 | Said the case study's per-cycle value of about 6.75 matches published estimates of 5 to 10 for African malaria, without a source. | Smith et al. (2007, PLoS Biology) report estimates from about 1 to over 3,000. | Cites Smith et al. (2007) for that range; the case study sits at its low end. |
| RG-231.7 | Section 13.3, Ex. 1 | Wrote the vector incidence without the probability b_v, and called the rates forces "from" infection. | The section's own equations include b_v and call them forces "of" infection. | b_v added; "force of infection". |
| RG-231.8 | Ch 13 introduction | "MacDonald's refinement". | The name is Macdonald (George Macdonald). | "Macdonald's refinement". |

## Printed Chapter 14 (RG-233, landed v2_96_6)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-233.1 | Section 14.3; Section 14.4, Ex. 2 hint | The vertical term counted births to mothers infectious at delivery. The hint gave Zika's short infection as the reason its vertical contribution is small. | For a transplacental route the opportunity is being pregnant when infected. That form does not depend on the infectious period and, for Zika, is 39 times the scalar form (0.0014 against 3.5 x 10^-5). Both stay small next to horizontal R0 = 2. | New paragraph on transplacental routes. The hint compares the two forms and says the contribution is small because few infected people are pregnant. |
| RG-233.2 | Section 14.1, Table 14.1, Section 14.4.3, Section 14.4 Ex. 2 | Gave Zika's vertical transmission as 5 to 10 percent; the exercise used 0.30, 0.10 and 0.05. | The chapter's own source, Ades et al. (2021), gives 47, 28 and 25 percent by trimester of exposure, with congenital Zika syndrome in 9, 3 and 1 percent. | About 25 to 47 percent by trimester, cited, and checked against the source. The exercise uses 0.47, 0.28 and 0.25. |
| RG-233.3 | Section 14.6, Ex. 5 (rubella) | Used 0.80 as the transmission probability, which the chapter's note warns against, assumed zero transmission after the first trimester, and gave no birth rate or infectious period. | Inconsistent with the chapter's note and with the late-pregnancy rise it cites. | Restated with its inputs given, both forms of the vertical term, and a question on the note's caveat. |
| RG-233.4 | Section 14.3 | Said tau_R* goes to infinity for chronic carriers. | With background mortality it tends to 1/nu_m = tau_m, as Section 14.6 Ex. 2 uses. | "tau_R* tends to tau_m = 1/nu_m for chronic carriers". |

## Printed Chapter 15 (RG-235, landed v2_96_7)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-235.1 | Sections 15.4 and 15.5; Eqs. 15.11, 15.12, 15.14 and 15.17 | Wrote the Kermack-McKendrick equation three ways; the form said to reduce to the SIR model had no depletion factor. | Without the factor, incidence grows without limit: in a test case S falls below zero by day 130. With it the final size is 0.4220, against 0.4232 for the SIR model. | The kernel is defined at full susceptibility and the factor S(t)/N added. Section 15.5 gives the linear form as valid while S is close to N. |
| RG-235.2 | Section 15.5, AI box, structural verification | Said a units test and two limit tests each catch a wrong answer. | The integral of the infectiousness A alone passes the units test and both stated limits. | Units catch the integral of the survival F; the fast-recovery limit catches the integral of A. |
| RG-235.3 | Section 15.2, Ex. 1 | Said total population is preserved when there is no mortality. | The total changes at the birth rate B(t); it is constant only with no births as well. | Restated. |
| RG-235.4 | Section 15.2.2 | A cross-reference printed "Exercise 4". | The derivation it points to is Section 15.8, Ex. 1. | Reference corrected. |
| RG-235.5 | Section 15.8, Ex. 3 | "The SARS-CoV-2-like kernel of Section 15.7". | Section 15.7 calibrates the kernel to seasonal influenza. | "The influenza-like kernel". |
| RG-235.6 | Section 15.5, opening | Said the autoregressive coefficients sum to exactly R0, and reused the kernel's symbol for the memory length. | The sum is a Riemann sum of the kernel (1.2997 at a half-day step, against 1.3). | "Approximates R0"; memory length L. |
| RG-235.7 | Section 15.8, Ex. 6 | Left the interval in (c) open, and asked when incidence reaches 100 times its initial value. | (b) starts at zero incidence, so the question is undefined. | (c) is specified; the target is 100 cumulative infections from one index case. |
| RG-235.8 | Section 15.3, Ex. 1 | Asked for Eq. 15.9, which the next section derives. | The answer is printed on the next page. | Asks for the solution by characteristics in both cases. |
| RG-235.9 | Section 15.8, Ex. 2 | Asked for the growth rate as a formula in the birth and death rates. | The rate is fixed only implicitly. At the given values the population shrinks (-0.0051 per year). | Asks for the equation, and whether the population grows or shrinks. |
| RG-235.10 | Section 15.8, Ex. 4(b) | "Deterministic infection at day 5". | Reads as a deterministic infectious period. | "All transmission at day 5". |
| RG-235.11 | Section 15.4.2 | Said the kernel is integrated over the population's distribution of times since infection. | The kernel is per index case; nothing is integrated over a population. | Clause deleted. |
| RG-235.12 | Section 15.8, Ex. 8 | "Vaccination as a boundary term". | Vaccination at age 1 is a jump across age 1, not a condition at age 0. | Restated as a jump across age 1. |
| RG-235.13 | Section 15.8, Ex. 7 | Said the model reduces to the multigroup framework. | Integrating over age bands adds aging between groups, which that chapter does not have. | "With aging between groups as an added flow". |

## Printed Chapter 17 (RG-237, landed v2_96_8)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-237.1 | Section 17.2, Ex. 1 | Asked why splitting symptomatic and asymptomatic infection matters for R0 in a way averaging would not capture. | At the baseline a single class with the weighted mean contact rate gives the same R0 (2.449 against 2.444). | The reader shows this, then explains why the split still matters for the isolation scenario. |
| RG-237.2 | Section 17.2 | Gave the asymptomatic share as 30 to 50 percent, citing Oran and Topol (2021). | The review concludes that at least a third of infections are asymptomatic; the 50 percent is not theirs. | "At least a third", checked against the paper. |
| RG-237.3 | Section 17.4, delta method | Called the input ranges 95 percent intervals, but divided each half-width by 2; gave tau_R's variance share as 32 percent. | The reading must be stated; the share is 31.3 percent. | States that each half-width is read as two standard deviations; 31 percent. |
| RG-237.4 | End-of-chapter Ex. 3 | Asked the reader to show that p and a are not jointly identifiable from case counts. | True only when the contact rates are fitted too; otherwise p is identifiable in principle. | Adds that condition. |
| RG-237.5 | Section 17.6, Ex. 1 | Did not say whether the scenario changes are relative or absolute. | The two readings give 0.699 and 0.437; both are below 1, so the answer stands. | States the changes as factors. |

## Printed Chapter 18 (RG-239, landed v2_96_9)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-239.1 | Section 18.5, Scenario 2; Fig. 18.3 caption; Sections 18.4 and 18.6; summary | Said insecticide alone is insufficient and that the biting rate dominates. | The model replaces every mosquito that dies. If emergence is set by larval habitat, abundance falls too: the sensitivity to vector mortality is -1.26, and doubling mortality alone gives R0 = 0.84. | New paragraph on fixed or compensating emergence. The caption, summary and Section 18.4 are qualified: "when emergence replaces killed adults", "when m is held fixed". |
| RG-239.2 | Sections 18.5 and 18.6; summary | Called biting-rate interventions uniquely cost-effective. | Section 18.4 itself says an elasticity does not measure cost. | Largest proportional effect per percent of parameter change, with m held fixed; cost is a separate question. |
| RG-239.3 | Section 18.3, delta method | Labelled the vector-to-host ratio's range one standard deviation but entered it as two; listed the incubation period without a term and used the recovery rate without listing it; upper end 2.95; for a factor-2 range, [0.62, 3.48]. | Upper end 2.96. The section's own reading gives [0.90, 3.35] for a factor-2 range. The conclusion holds. | Inputs relabelled; [1.29, 2.96] and [0.90, 3.35]. |
| RG-239.4 | Section 18.3, Ex. (b) | The back-calculation counted incubation survival twice and equated the force of infection with the per-case ratio. | Section 18.3 gives a different relation. | Uses the section's quasi-equilibrium relation. |
| RG-239.5 | Section 18.3, Ex. (b) and (e) | Referred to "the companion repository's Chapter 16 notebook". | Dengue is printed Chapter 18. | Refers to the chapter's own notebook. |

## Printed Chapter 19 (RG-241, landed v2_96_10)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-241.1 | Section 19.4, lab (a) and (b) | Predicted that the high- and low-activity per-case ratios differ by about c_H/c_L, and recovered c_H from them. The model left the strata uncoupled. | Once the strata share a growth rate the ratios converge: the female ratio is 0.015, 0.12 and 0.79 in years 1, 5 and 20. The difference shows in prevalence, 12.4 times higher in high-activity females. | The lab predicts convergence and points to prevalence; (b) states that its formula holds for an isolated core. The strata are coupled by random mixing. |
| RG-241.2 | Section 19.2, per-act probabilities | Gave 0.001, 0.0005, and 0.01 to 0.03 for receptive anal exposure, citing Patel et al. (2014). | The paper gives 8, 4 and 138 per 10,000 exposures (95 percent CI 102 to 186 for the last); 0.03 lies outside it. | 0.0008, 0.0004 and about 0.014 (CI 0.010 to 0.019), checked against the paper. |
| RG-241.3 | Section 19.2 | About 39 million people living with HIV in 2023. | The UNAIDS fact sheet gives 39.9 million. | "About 40 million (39.9 million)". |
| RG-241.4 | Section 19.2 | Wrote the infectious lifetime as the sum of two times. | Competing exits add rates: 1/(nu_m + mu_d) is about 9 years, not 61. | 1/(nu_m + mu_d). |
| RG-241.5 | Section 19.5, Scenario 4 | Gave R0 as an additive total, 1.58 + 0.008. | The chapter reports rho(K): 1.585, the same 1.59. | R0 = rho(K), about 1.59. |
| RG-241.6 | End-of-chapter Ex. 4 (PrEP) | Applied PrEP to men's force of infection only, while asking for one threshold. | Men only gives 66.7 percent coverage; both sexes, 40.8 percent. | Applies to both sexes' forces. |

## Printed Chapter 20 (RG-243, landed v2_96_11)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-243.1 | Section 20.1; Fig. 20.1 caption; Section 20.3 | Said every single intervention leaves R0 near but not below threshold for every pathogen, and that only combinations achieve elimination. Section 20.3 credited ART's 0.16 to a combination. | For HIV, condoms alone (0.85) and ART alone (0.16) are single interventions below threshold. Dengue insecticide alone gives 0.84 if emergence stays fixed. | Restated: the higher the baseline R0, the less one intervention can do. Single measures fall short for COVID-19 and dengue but not for HIV. |
| RG-243.2 | Section 20.3 | Called biting-rate reduction and partnership reduction disproportionately cost-effective. | Elasticities do not measure cost. For HIV, condoms move R0 as far per percent as the partnership rate (0.79 each). | Restated as effect per percent of change; cost is a separate question. |
| RG-243.3 | Section 20.2; Fig. 20.2 row and caption | Called vector mortality burden-facing and sign-dependent, and said c_H acts through a denominator. | Vector mortality is invasion-facing twice and its sign never changes. c_H sits in the numerator of both directions. | Vector mortality invasion-facing twice: -0.760 with m fixed, about -1.26 if emergence stays fixed. The row is relabelled "sign-dependent or reinforcing" and the caption corrected. |
| RG-243.4 | Section 20.5, HIV bullet | Called each estimator a per-target-susceptible force. | J/I is a per-case ratio; J/S would be the force. | "The realized rate of new infections per current case in its stratum". |
| RG-243.5 | Section 20.3, Ex. 1 | Said square-root dampening recurs across COVID-19, dengue and HIV. | The section itself says COVID-19 has no square-root structure. | Limited to dengue and HIV; the exercise asks why it is absent from COVID-19. |
| RG-243.6 | Sections 20.4 and 20.1 | Said c_H exceeds the population average by an order of magnitude, and listed pandemic influenza at R0 about 1.5 among the extremes. | The ratio is 3.6 (10 against the low-activity rate). 1.5 lies inside the stated common range. | "Three and a half times the population average and ten times the low-activity rate"; influenza sits at the low edge of the common range. |

## Ling Xue's review: notation and dimensions (RG-246, landed v2_97_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-246.3 | Key Symbols, Ch 4, Appendices C and F, and 53 sentences across the book | Called nu_m a "migration rate", with four different definitions in four places. | In the model nu_m is a turnover rate: individuals leave at nu_m and are replaced by inflow nu_m N^c. Eighteen other sentences mean people actually arriving. | "Turnover rate" in the 53 sentences that name nu_m, with one sentence saying it combines births, deaths and migration; the 18 others unchanged. |
| RG-246.4 | Appendix A, "Dimensions and Units" | Gave contact rates as [time^-1] and beta as dimensionless. | Chapter 4's Table 4.1 and Appendix F give c_X as contacts per person per time and beta as persons per contact, the book's convention. | Appendix A follows Table 4.1; Appendix F gains a table of the dimensions of every parameter. |

## Printed Chapters 4, 6, 10, 14, 15, 17 and 19: corrections found while writing Further Reading (RG-249, landed v2_98_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-249.1 | Ch 6, the Remark after the time-varying threshold | Said the threshold quantity T is "not equal in value" to the periodic R0. | For one infected compartment, the periodic R0 of Bacaer and Guernaoui (2006) and Wang and Zhao (2008) is the factor that makes the cycle multiplier equal one, which is T. | T is the periodic R0 in the scalar case; what fails with several compartments is the formula, not the concept. |
| RG-249.2 | Ch 10, Section 10.2; Ch 14, Sections 14.1 and 14.5; Ch 15, Section 15.2; Ch 17, Section 17.2; Ch 19, Section 19.2 | Six citations were used for claims their works do not make, among them a paper on influenza myositis in children cited for SEIR modeling of influenza. | Each cited work was read: they concern other subjects. The age-structure equation was first written by M'Kendrick (1925), not by von Foerster. | Each sentence deleted or reworded to what the work supports; Busenberg and Cooke (1993) added for the theory of vertical transmission. |
| RG-249.4 | Ch 4, the baseline description | Called the baseline (R0 about 1.92, infectious period 12 days) representative of seasonal influenza. | R0 = 1.92 lies above the median estimates for seasonal influenza and near those for 1918 (Biggerstaff et al. 2014); influenza's infectious period is about 4 to 6 days. | Called a teaching baseline for a respiratory infection, with both comparisons stated. |

## All chapters: every citation checked against the cited work (RG-251, landed v2_99_0)

Each of the book's 448 citation sites (164 works) was checked against the cited work's title and abstract,
publisher page or full text. 34 sites in 21 works claimed something the work does not say. Each was corrected to what
the work supports; none was replaced by a new reference.

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-251.1 | Ch 8, the WSU reporting example | Gave a seroprevalence-based final attack rate of 44% for the WSU campus, citing a study of Japanese elementary schools. | No source for the 44% was found; the WSU modeling study reports over 10% from clinic data and no serology. | The 44% is labeled an illustrative value; the clinic figure is cited to the WSU study. |
| RG-251.2 | Ch 9, correlated parameters | Called two malaria biting parameters a "published example" of parameters correlated across settings. | The cited paper discusses no correlation; it gives separate high- and low-transmission baselines. | Reworded to the baselines the paper gives. |
| RG-251.3 | Ch 13, Section 13.4 | Described one malaria model as having a full mosquito life cycle, and attributed another's backward bifurcation to biting saturation. | The first has adult mosquitoes only; in the second the backward bifurcation comes from disease-induced death. | Both described as the papers do. |
| RG-251.4 | Ch 10 | Called the SIDARTHE model an elaboration of SEIR. | SIDARTHE has no exposed stage. | Described as splitting the infected class. |
| RG-251.5 | Ch 12 | Said a paper derives conditions under which vaccination alone eliminates a sexually transmitted infection. | The paper studies a generic acute and chronic model and shows that a backward bifurcation complicates the criteria. | Reworded to that finding. |
| RG-251.6, .7 | Ch 7 | Said the day-of-week weights were calibrated to published JHU patterns, and called a mortality-deconvolution paper a review. | Neither cited paper reports a weekday pattern; the second is a research article on 1918 influenza. | The weights are labeled illustrative; the paper is cited as an example of deconvolution. |
| RG-251.8 | Ch 11 | Cited Anderson and May, Chapter 11, for activity-level heterogeneity. | That is their Chapter 10. | Chapter 10; a duplicate entry for the same book merged. |
| RG-251.9 | Ch 9 | Said a long-COVID study applied local sensitivity analysis. | The study uses scenario simulation; its parameter ranking was right. | Reworded. |
| RG-251.10 | Ch 13 and Ch 18 | Cited a Rift Valley fever paper as a framework for rainfall and environmental drivers. | Rainfall is not modeled; the paper compares wet- and dry-season parameter sets. | Reworded to that comparison. |
| RG-251.11 | Ch 10 | Cited two HIV models as "the SEIRS literature" and "the respiratory-mortality literature". | One is an HIV treatment model, the other a staged-progression model. | Described as such. |
| RG-251.12 | Ch 13, Section 13.1 | Said comparative studies favour vector-targeted over pathogen-specific control. | The cited comparison of dengue and chikungunya calls for mitigation tailored to each disease; the second paper is a network-patch method. | Reworded; the second citation dropped here. |
| RG-251.13 | Ch 18, Lessons | Cited a SARS paper as a dengue calibration anchor. | The paper is about SARS. | Sentence deleted. |
| RG-251.14 | Ch 13 and Ch 18 | Said Xue, Fang and Hyman (2018) analyze behavior change as an intervention and show it lowers the Wolbachia coverage needed. | Behavior change enters their model as a fixed parameter; coupling with Wolbachia spread is left for future work. | Described as the paper does. |
| RG-251.15 | Ch 5, Ch 16, Ch 17 and Ch 20 | Said models with behavioral feedback outperform constant-beta and data-driven models. | The cited comparison fits no constant-beta model; no single model is best, and the feedback models often match or beat the mobility-driven one. | Reworded at all four sites. |
| RG-251.16 | Ch 7 and Ch 15 | Described a day-of-week method as a renewal-equation framework estimated jointly with R_e(t), and as the state of the art. | It fuses compartmental models with generalized additive models; renewal estimates are its comparator. | Reworded; "state of the art" dropped. |
| RG-251.17 | Ch 18 | Cited a mosquito-control trial for the precision of density estimates (a factor of two). | The trial reports no such precision. | The factor of two is labeled illustrative. |
| RG-251.18 | Ch 15 | Called a pertussis model a review of age-structured approximations. | It is a model of pertussis transmission. | Described as such. |
| RG-251.19 | Ch 10 | Credited safe burial, captured by compartmental models, with ending the Ebola epidemic. | The cited age-of-infection model attributes the decline to earlier and more frequent hospitalization; safe burial is not modeled. | Reworded to the paper's finding. |
| RG-251.20 | Ch 18, Section 18.1 | Attributed "100 to 400 million infections per year" to Bhatt et al. (2013). | They estimate 390 million (284 to 528 million), 96 million apparent. | Their figures. |
| RG-251.21 | Ch 17 | Called a one-season forecast evaluation a survey of operational forecasting. | It evaluates a real-time ensemble for one U.S. influenza season. | Described as such. |
| RG-251.22 | Ch 20 | Said behavior change was the main reason the 2014-2015 Ebola epidemic stopped. | The cited model of Monrovia finds reducing contacts of infectious people the most effective intervention; it makes no claim about what ended the epidemic. | Reworded to the model's finding. |
| RG-251.23 | Ch 7, influenza case study | Said R_e = 1.40 is comfortably within the range 1.2 to 1.6 for seasonal influenza. | Biggerstaff et al. (2014) give a median of 1.28 (IQR 1.19 to 1.37); no 1.2 to 1.6 range appears. | "A little above the median of 1.28". |
| RG-251.25 | Ch 12 and Ch 19 | Credited the 1994 paper of Hyman, Li and Stanley with the differential-infectivity formulation. | The 1994 paper lets infectivity vary with time since infection; the compartmental differential-infectivity model is from their 1999 paper. | Credited as such (confirmed by the first author). |
| RG-251.26 | Ch 8 and Ch 18 | Gave a "literature range" of 4 to 6 days for influenza's infectious period, and a typical dengue R0 of 2 to 4, with explosive and endemic ranges. | The cited shedding study gives no such range (19% still culture-positive on day 8); the dengue paper gives no R0 range, and the other ranges had no source. | 4 to 6 days labeled the book's assumption; the dengue sentence quotes the paper's benefit threshold (R0 > 3), and the unsourced ranges are gone. |
| RG-251.27 | Ch 1, Ch 5, Ch 8, Ch 9, Ch 18 and Ch 19 | Several attributions: eFAST to Marino et al., a centre-manifold result to a textbook not checked, section numbers in Li (2018), "multiple independent groups" for the WSU studies, a review described as a model. | eFAST was developed by Saltelli and co-workers; the WSU studies share an author; the subsection numbers could not be confirmed. | Each attribution corrected; Li cited by section. |

## Printed Chapters 13 and 18 (RG-252, landed v2_100_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-252.8 | Ch 18, Further Reading | Listed Wolbachia's lower birth rate among costs that move m. | In the cited model the carrying capacity sets m, so a lower birth rate leaves R0 unchanged; the lower transmissibility was omitted. | The costs listed as the paper gives them. |

## Printed Chapters 3, 7, 9, 11 to 15, 18 and 20: the sensitivity references (RG-253, landed v2_104_1)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-253.3 to .7 | 15 sites in 10 chapters | Cited a sensitivity-analysis paper, said to be in preparation, for results on the infected-viewpoint estimator and its extensions. | That paper is not in preparation. The sensitivity results are in the authors' textbook in preparation, *Foundations of Sensitivity Analysis*; the estimator's results are this book's own. | Four sites cite the textbook; eleven point to this book's own argument (Chapters 3 and 7). |
| RG-253.9 to .12 | Ch 9 | Said the sensitivity textbook has three unifying ideas, credited it with the burden indices and the term "invasion-burden partition", and cited the wrong chapter for the tornado plot's two readings. | The textbook's draft has four unifying ideas, its own equal-index case, and does not use the term. | Corrected to the textbook's content; the term is this book's. |

## All chapters: the last citation sites, read in full (RG-257, landed v2_102_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-257.1 | Ch 7, influenza case study | Took contact rates of 10, 6 and 10 a day "from contact-matrix studies for the general U.S. population". | The POLYMOD survey covers eight European countries (mean 13.4 contacts a day); the projected matrices give no daily totals; neither measures contacts while infected. | 10 a day is placed within POLYMOD's range of country means; 6 a day while infected is labeled the book's assumption. |
| RG-257.2 | Ch 4 | Credited population means of 10 to 13 contacts a day to the projected matrices. | The figures are POLYMOD's. | "The POLYMOD diaries averaged 13.4 contacts per person per day, with country means from about 8 to about 20", cited to POLYMOD. |
| RG-257.3 | Ch 6 and Ch 15 | Said an improved serial-interval method extends to "short series". | It extends to imported cases and to serial intervals estimated from known case pairs. | Described as such; the Ch 15 task follows. |
| RG-257.4 | Ch 17 | Glossed a review's asymptomatic share in terms of testing and self-isolation. | The review concludes that at least a third of infections never develop symptoms. | Its conclusion, in its terms. |
| RG-257.5 | Ch 7 | Called a ranking of data types for identifiability "empirical" and added a limit of two estimable quantities. | The ranking holds but comes from simulation; the limit is not in the paper. | "Simulation-based"; the limit removed. |
| RG-257.6 | Ch 18 | Listed specific biases of dengue surveillance under a citation. | The paper describes under-reporting from poor surveillance, low reporting and difficult diagnosis, not those biases. | The sentence says what the paper says. |
| RG-257.7 | Ch 13 | Attributed coefficients of variation of 0.51 and 0.49 to a dengue incubation study. | The study reports ranges, not CVs; the values follow from its ranges. | Stated as implied by its ranges. |
| RG-257.8 | Ch 13 | Attributed a gamma EIP of shape 3 and a disseminated-infection endpoint to a temperature study. | The study could not be read here. | The arithmetic kept without the attribution; the endpoint stated generally. |
| RG-257.9, .10 | Ch 18 | Called an EIP survival probability of 0.56 "consistent with the entomological literature" and said a laboratory study saw no transmission at cooler temperatures. | 0.56 is the book's own calculation; the study reports EIP lengths. The no-transmission clause could not be confirmed. | A 9-day EIP placed within the study's observed range; the clause removed. |
| RG-257.11 | Ch 13 | Described a classic paper as a treatment of mosquito population dynamics with acquired immunity. | It models malaria in humans and mosquitoes, with mosquito density as a state variable and immunity in humans. | Described as such. |
| RG-257.12 | Ch 11 | Said a 1985 paper introduced proportionate mixing. | That paper credits earlier work and applies the ansatz to age-dependent transmission. | "Applied" for "introduced". |
| RG-257.13 | Ch 10 | Credited two papers with four mechanisms of backward bifurcation. | They cover control policies and a contact rate that varies with the epidemic. | Each mechanism cited to a work that has it; two with no source removed. |
| RG-257.14 | Ch 1 | Assigned disease classes to density- and frequency-dependent transmission under two citations. | The cited works do not make those assignments. | "Which mode fits a given infection is an empirical question", with the citations. |
| RG-257.15 | Ch 12 | Described Hyman and Stanley (1988) as a model of high- and low-activity subpopulations. | The model distributes the population continuously by number of partners (confirmed by the first author; full text read). | Described as such, with its results on random and like-with-like mixing. |

## Printed Chapter 8: model discrepancy (RG-259, landed v2_104_0)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-259.7 | Ch 8, Scope of Uncertainty Principle (box) | Named two kinds of uncertainty and said parameter uncertainty "is reducible by collecting more data from the current outbreak". | When the model's structure is wrong, more data narrow the interval around a biased value: shown by Brynjarsdóttir and O'Hagan (2014) and, with the book's own models, by a new computed table in which the interval for the peak forecast shrinks tenfold and never covers the truth. | The box names a third kind, model discrepancy, and the reducibility sentence holds only when the discrepancy is negligible. A new section and a new pitfall develop the point. |

## Printed Chapters 9, 12, 13, 15 and 17 to 20, and Appendix F: the infected viewpoint and durations (RG-260, landed v2_105_0; Chapter 15, v2_106_0; RG-267, landed v2_107_0 and v2_107_1)

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-260.1 | Ch 9, 13, 17, 18, 19 and 20: sensitivity indices, delta-method sums and tornado plots | Reported sensitivity indices with respect to rates: vector mortality mu_v, recovery and latency rates, the turnover rate, and the HIV exit rate nu_m + mu_d. | The book's own pitfall on sensitivity analysis asks for indices with respect to mean durations. The case studies did not follow it. | Every index reported with respect to the duration (vector lifespan, infectious period, latent period, residence time). Magnitudes unchanged and signs flipped: a longer vector life raises R0 (index +1.1 in Ch 13, +0.76 in Ch 18); the HIV residence time has index +1. |
| RG-260.2 | Ch 13, 17, 18 and 19 model equations; Ch 15 (v2_106_0) | Wrote new infections with per-susceptible forces under the symbol alpha, which Chapters 3 to 12 reserve for the force from infection (per infectious individual). | The same dynamics can be written per source, as Chapter 12 already does. Every rewritten right-hand side was checked symbolically against the old one. | Forces from infection per source, with arrows where source and target both matter (alpha from vector to host and from host to vector; alpha from female to male and from male to female for HIV; one alpha per COVID-19 track; the age and time-since-infection forms in Ch 15). lambda is the force of infection throughout. The dynamics are unchanged. |
| RG-267.1 | Ch 13, Section 13.3 (bite dilution); Ch 18, Figure 18.1 caption | Said both vector-host forces are inversely proportional to the host population. | After the rewrite this is false for the force from an infectious vector, which depends on the host population only through the susceptible fraction and equals a b_h at the disease-free state. | Bite dilution now located correctly: in the force from an infectious host and in the force of infection on a susceptible host. |
| RG-267.2 | Appendix F, multi-population forces | Wrote the vector-host forces in fractions without the ratio of the two carrying capacities. | In fractions of different capacities each cross-population term needs that ratio; the formulas were short by the vector-to-host ratio m. | Written in counts, as the chapters write them, with the capacity ratio stated for fractions. |
| RG-267.6 | Ch 15, Kermack-McKendrick derivation | Defined the kernel K = A F with A containing the susceptible fraction, then multiplied by S/N again. | Read literally the susceptible fraction entered twice. | A is measured in a fully susceptible population; the susceptible fraction enters once. The fraction is the contact-weighted one of Chapter 1, S/N under equal contact rates. |

## Exercises, answers and Further Reading tasks: the full audit (RG-269, landed v2_108_0 and v2_108_1)

Every exercise in the book (276) and every Further Reading task (103) was checked against the current chapter text. Most corrections were to wording, references or tags. The rows below are those that changed a printed claim or number.

| ID | Where | What the earlier draft said or did | What the check found | Correction (as ruled) |
|---|---|---|---|---|
| RG-269.1 | Ch 1, Ch 4 and Appendix F: units of beta; three dimensional-analysis exercises | The prose called beta dimensionless; Appendix F, Table 4.1 and Section 4.5.2 gave it persons per contact. | Two conventions, and the exercises sent students to the one their answers did not use. | Both readings stated: the person and contact labels are counted units used for bookkeeping, so they are pure numbers, and the two readings agree. |
| RG-269.2 | Ch 19, Section 19.4, Exercise 1 (parameter estimation) | Said a homogeneous-mixing fit to the aggregated data reproduces the failure of Figure 19.3. | A homogeneous fit to aggregated incidence over prevalence returns 1 + r/(nu_m + mu_d), above 1 whenever the data grow, at any mixing. Only the surveyed mean partnership rate gives the failure. | The exercise asks what the fit returns and why only the mean rate fails. |
| RG-269.6 | Ch 10, Section 10.7, discussion of Figure 10.7 | Said the Erlang model peaks earlier "because a less variable generation interval grows faster at the same R0". | At a fixed mean the less variable interval grows more slowly. The Erlang model grows faster because its mean generation interval is shorter, 7.5 days against 12. | The reason corrected. |
| RG-269.7 | Ch 1, Section 1.4.3, practical rule | Said rho tau_c < 0.3 keeps the error under 15 percent. | The error is 15.75 percent at 0.3. | "Below 16 percent". |
| RG-269.8 | Ch 9, invasion-burden partition and summary | Printed the interval [0.90, 1.90]. | 1.40 (1 plus or minus 1.96 x 0.18) is [0.91, 1.89]. | [0.91, 1.89]. |
| RG-269.9 | Ch 10, Section 10.2, SIRS endemic factor | Said the factor tends to gamma_R/nu_m when omega is much larger than nu_m. | That holds only if omega is also much larger than gamma_R; in between the factor is about omega/nu_m. | Both regimes stated. |
| RG-269.10 | Ch 13, end-of-chapter Exercise 9 | Gave "typical" malaria durations of 14 days for the vector and 7 to 30 days for the host. | The chapter's own case study uses 10 and 100 days, a ratio of 0.1. | The case-study values. |
| RG-269.11 | Ch 14, Table 14.1 and Section 14.4.1 | Gave the vertical share of HIV transmission as about 5 percent. | The chapter's own computations give 4 percent (Section 14.3) and 3 percent (end-of-chapter Exercise 1). | 3 to 4 percent. |
| RG-269.12 | Ch 12 and Ch 17, Further Reading tasks | Ch 12 asked whether the HIV example "stays above threshold" with Patel's values; Ch 17 asked for the mask coverage at which the combined strategy "just reaches" R0 = 1. | The HIV example has R0 = 0.054, below threshold before any change. Without masks the combined strategy already gives R0 = 0.961. | Ch 12 asks how far below threshold the example falls (0.022 with Patel's values); Ch 17 starts from the isolation scenario. |
| RG-269.13 | Ch 20, Further Reading task on optimal control | Offered two controls, both acting on invasion. | The invasion-versus-burden question could not be posed. | One invasion-facing control (asymptomatic contacts) and one burden-facing control (treatment lowering the disease-induced death rate, which moves R0 by about 0.1 percent). |

Observations the authors are still weighing are not listed here.
