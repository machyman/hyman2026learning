# AI tools for teaching preparation

*A companion working guide for* Learning with AI: A Framework for Students, Instructors, and Universities.
*See Part II, "AI tools for teaching preparation."*

The book names the durable categories and leaves the practical detail here, where it can be kept
current. Products change names, merge, and disappear. The categories persist, and so does the way you
use them well. This note is meant to be updated as the tools change, which they will. Tool names,
free-tier limits, and which tools lead all reflect mid-2026; check each tool's own site before you rely
on it.

**Set the context before you ask.** Before you ask for anything, tell the AI who you are, what the
course is, and who the students are. Paste the syllabus, or the unit you are working on. Describe the
class in general terms (a first-year non-majors section, mixed preparation, most without calculus)
rather than uploading anything that identifies an individual student; that line is drawn in *Before you
upload anything*, below. The same request returns generic filler on its own and something close to
usable once the tool knows the setting. This single step does more for the quality of what you get back
than any other.

**Show it what good looks like, and push past the first draft.** The tool's first answer is a starting
point, not the finished product. Paste an example of the quality or style you want and ask it to match
that, not just your description of it. Then react to what comes back: ask for a stronger version, ask
what it would change, ask for two or three options and choose. The output improves faster when you push
on a draft than when you re-prompt from scratch.

**The one rule that governs all of it.** Every capability below produces a draft. The instructor who
uses it is responsible for verifying the result, the same standard the book asks of students. None of
these tools knows your course, your students, or what you meant to teach. They remove the friction of a
first draft. They do not remove your judgment or your responsibility for what you hand out.

**Which kind of tool to reach for.** Two families cover most of this work. In 2026, the general assistants
(ChatGPT, Claude, Google Gemini) are the workhorses. They handle almost every task below, they have free
versions, and a clear prompt with your own material attached gets further than any menu of buttons. The
teacher-specific tools (Diffit, MagicSchool, and others) wrap those same models in a fixed workflow,
which saves setup time for a narrow task. Much of that ecosystem was built for K-12; a university
instructor will often get more from a general assistant given good instructions. Where a specialist tool
earns its place, it is named below.

**One boundary.** These uses share a low-risk profile because they act on your own materials, not on
student assessment. Using AI to give feedback on student work or to grade is different in kind and
carries real risk. The book treats those with the boundaries they require in the feedback-and-grading
section. They are not repeated here.

**Before you upload anything.** Student work and student data are governed by your institution's policy
and by law (FERPA in the United States). Check what you are permitted to upload before you paste a
roster, a graded exam, or anything that identifies a student into an external tool. Your own lecture
notes and reading lists carry no such restriction.

---

## Rewrite a reading at several levels

**Good for.** Meeting a mixed-preparation class where each student can reach an idea, and producing a
plain-language version of a dense passage.

**Using it well.** Give the tool the actual passage and ask for two or three versions at named levels
("a version for a first-year non-major," "a version that keeps the technical precision"). Read the
simplest version against the original with one question in mind: did it drop a qualification that
matters? Simplification smooths away exactly the caveat a careful reader needs, and it does this most
often with technical or mathematical claims. A good result keeps the meaning intact at every level and
changes only the reach, not the truth.

**Getting the tools.** Any general assistant does this from a pasted passage. Diffit is a specialist
built for it; it rewrites a text or a web page at several reading levels and across languages, with a
free tier.

## Turn an outline into draft materials

**Good for.** Escaping the blank page: a slide sequence, a lesson plan, a set of worked examples, or a
problem set with solutions.

**Using it well.** Feed it your outline and your emphasis, and it will draft the structure in
seconds. The work that remains is the work that makes the material yours. Check every
worked example and every solution by hand; generated mathematics is confident and often wrong. Ask
whether the emphasis matches what you want students to carry away, because generated material drifts
toward the generic. A good result is a scaffold you can teach from after your edits, not a finished
handout you trust on sight.

**Getting the tools.** A general assistant drafts lesson plans, worked examples, and problem sets from
your outline. For slides, Gamma builds a designed deck from a prompt or a document and exports to
PowerPoint or PDF on a free tier; Google Slides with Gemini and Copilot in PowerPoint do the same inside
those suites. Expect to fix the exported file; the design rarely survives the export cleanly.

## Draft assessment questions and rubrics

**Good for.** Candidate quiz or exam questions drawn from your content, and a first-pass rubric for an
assignment you describe.

**Using it well.** Give it your material and ask for more questions than you need, then cut. Check that
each question tests the reasoning you care about and cannot be answered by pattern-matching or a quick
search. For a rubric, check that the criteria reward the thinking, not the surface features that are
easy to score. Treat the output as raw material for an instrument you build, not the instrument. A good
result is a short list of questions you would actually put on the exam and a rubric a second reader
would grade consistently. (Grading student work with AI is the different, higher-risk activity covered
in the book's grading section.)

**Getting the tools.** A general assistant does this well from your content. MagicSchool and similar
teacher suites offer fixed quiz and rubric generators with free tiers if you want the workflow rather
than the flexibility.

## Convert materials for accessibility

**Good for.** An audio version of a reading for students who learn by listening or who have print
disabilities, described alternatives for figures, and captions for recorded material.

**Using it well.** Generate the conversion, then check it where a small error changes the meaning:
technical terms, equations, symbols, and anything a screen reader will voice literally. A described
figure has to carry the information the figure carries, not just say that a figure is present. A good
result is a version a student could rely on without seeing the original.

**Getting the tools.** NotebookLM turns your uploaded sources into an audio overview for free. General
assistants draft figure descriptions and clean up auto-generated captions. Your institution's
disability-services office often has vetted tools and standards; ask before building your own.

## Draft routine communication

**Good for.** A syllabus announcement, an FAQ built from recurring questions, a first pass at
administrative correspondence.

**Using it well.** These are logistics, and a general draft handles logistics well. The line to hold:
anything carrying a judgment about a specific student must be written or substantially rewritten by you.
A recommendation letter or a comment on a student's standing is your assessment of a person, and a
generic draft cannot make it. A good result reads in your voice and says nothing about a student you did
not decide to say.

**Getting the tools.** Any general assistant drafts this from a short description of what you need to
say.

## Turn a recorded lecture into notes

**Good for.** A searchable transcript and a summary of a session, for a student who missed it or as a
study resource.

**Using it well.** Transcribe first, then summarize from the transcript. Check the transcript on
technical vocabulary, where these tools fail most, and check that the summary kept the emphasis that
made the session worth attending. Automatic summaries flatten what mattered. A good result is a
transcript a student can search and a summary that would not mislead someone who was not there.

**Getting the tools.** Otter.ai captures a live lecture and produces a transcript on a free tier, though
it handles STEM terms and strong accents poorly, so read its output for your own field with care.
NotebookLM does not record, but it turns a transcript or a posted recording into a source-grounded study
guide for free, and it stays inside the material rather than inventing.

## Gather sources for course design

**Good for.** A survey of a topic or a set of candidate readings when you are building or updating a
course.

**Using it well.** Ask for the survey, then verify every source before it goes near students. This is
the capability most prone to fabricated citations and confident misdescription. Check that each
reference is real and says what the summary claims, exactly as the book asks students to do with their
own AI-sourced work. A good result is a reading list you have personally confirmed, not a list you trust
because it looked plausible.

**Getting the tools.** General assistants with a current search or research mode do this; the
verification burden is the same whichever you use.

---

## Why this is a companion, not a book chapter

A printed list of tools would be wrong within a year, and the book's argument is about judgment, not
tools. This guide can be concrete where the book stays durable, and it can be revised. If you adapt it,
or find a category worth adding, that is the intended use. Treat every AI output as a draft to verify,
and follow your institution's policy on data privacy and permitted use before you upload student work or
student data to any tool.
