# Study session: which principle applies?
*A physics example*

This is a worked study session. It follows one student through an introductory physics problem using the Learning Spiral, with the AI as a study partner. The point is not the number; it is whether the AI uses the right physics. Watch the student catch a clean, confident answer that comes from the wrong starting principle.

The student is using the study-partner prompt (`companion/spp/`), so the AI is set to ask questions and give hints rather than hand over solutions.

## The problem

> A cart rolls along a track at a steady speed and bumps into a second, identical cart sitting still. The two carts couple together and roll on as one. How fast do the coupled carts move compared with the first cart's original speed? (Ignore friction.)

It is a standard setup, and the AI will answer it confidently. The question is whether the confident answer uses the right physics.

## Try first

Before opening the AI, the student thinks it through:

> *My attempt:* After they couple, there is twice as much cart moving as before, but only the push that the first cart brought into the collision. So the combined carts should move slower than the first cart did. I would guess about half the original speed, though I am not certain why, or what exactly is conserved here.

> **What to notice:** The student reasoned physically before reaching for the AI, and landed on a sensible expectation (slower, roughly half) and the right question (what is conserved?). They have something to check the AI against, which turns out to matter.

## Ask for help, not the answer

> **Student:** Here is a physics problem. [pastes it] I think the coupled carts end up slower, maybe half speed, but I want to understand which idea I should be using. Don't just give me the number. What quantity stays the same through a collision like this?
>
> **AI:** Good question to ask. In a collision, think about what is conserved. Two candidates are momentum and kinetic energy. Which one is safe to assume stays the same when two objects collide and stick together?

> **What to notice:** The student asked which principle to use, not for the answer, and the AI pointed at the real decision (momentum versus energy) without resolving it, leaving the judgment to the student. That decision is the whole problem.

## Work it, and watch the AI

The student is not sure yet, so they let the AI run with one approach to see it:

> **Student:** I am not sure. Can you show me how it would go if I used energy?
>
> **AI:** Sure. If kinetic energy is conserved, you set the energy before the collision equal to the energy after, with both carts moving together afterward. Solving that gives a combined speed of about 0.7 times the original speed.

> **What to notice:** This is clean, confident, and uses real physics steps. The number even looks plausible, since it is slower than the original. A student in a hurry would write it down. But it disagrees with the student's own estimate of about half, which is the signal to slow down.

## Check the AI (the important step)

> **Student:** Wait. That gives about 0.7 of the original speed, but my own reasoning said about half. They cannot both be right. And I do not think energy should be conserved here, because the carts couple together. When things crash and stick, some energy goes into the bump itself, the sound and the slight deformation, so the motion energy afterward should be less than before. The quantity that is actually conserved is momentum, not energy.
>
> **AI:** That is the key insight. In a collision where the objects stick together, kinetic energy is not conserved; momentum is. Using momentum conservation here gives a combined speed of half the original, which matches your estimate.

> **What to notice:** This is the move the session is built around. The AI's energy answer was not an arithmetic mistake; the steps were valid. It came from the wrong starting principle, energy conservation, in a situation where energy is not conserved. The book calls this the answer where the symbols are right but the physics is wrong. The student caught it because their own estimate disagreed and because they thought about what physically happens when carts stick, not because the AI flagged anything.

## Reflect and disclose

The student writes the answer in their own words:

> *My answer:* The coupled carts move at half the first cart's original speed. The right principle is conservation of momentum, because the carts stick together, which means the collision loses some motion energy, so energy conservation does not apply. The "twice the cart, same push" picture gives half the speed, which also matches the momentum reasoning.

> *AI use:* I used an AI study partner to think through which principle applies. When I asked it to work the problem using energy, it produced a confident but wrong answer, because energy is not conserved in a sticking collision. I caught the disagreement with my own estimate and identified momentum as the right principle. The reasoning is mine.

> **What to notice:** The student can explain why momentum and not energy, can defend the factor of one half, and the disclosure honestly records that the AI's energy approach was wrong and how they caught it.

## What this session shows

- **Try first** gave the student a physical estimate (about half) that later disagreed with the AI and triggered the check.
- **Asking which principle applies** kept the central physics decision with the student.
- The AI's energy answer was **algebraically fine but physically wrong**, the exact failure the book warns about: correct steps from a wrongly chosen starting point.
- **Checking the AI** meant asking whether the right principle was used and whether the answer made physical sense, not just whether the arithmetic was clean.
- The answer and the reasoning are the student's.

The same pattern works across physics: decide which law actually applies before trusting any number, and sanity-check every answer against a rough estimate, because a clean answer from the wrong principle still looks clean.
