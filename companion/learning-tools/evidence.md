---
title: AI learning tools, the evidence
permalink: /companion/learning-tools/evidence/
---

# The evidence behind the tools list

*Companion to the [AI learning tools](README.md) page. Status as of 11 November 2026.*

This page keeps the references so the book does not have to. It is updated as new studies appear, and much of
the 2026 evidence is still in working papers that may change before publication.

**Labels.** **[PR]** peer reviewed. **[WP]** working paper or preprint, not yet peer reviewed. **[VENDOR]**
reported by the company that makes the tool. **[RETRACTED]**.

## Read the timing first

The key distinction is between scores while the AI is on and scores on a later test without it. Only the second
measures learning.

| Study | Setting | Result on a later test without AI | Label |
|---|---|---|---|
| Bastani et al. 2025 | About 1,000 high-school math students, Turkey | Unrestricted GPT-4: exam down 17%. Answer-withholding tutor: no loss, no gain. | PR |
| Kestin et al. 2025 | 194 introductory physics students, Harvard | AI tutor beat in-class active learning on an immediate post-test. | PR |
| Gallegos 2026 | About 300 undergraduate econometrics students, Chile | Urging students to use a course GPT: no effect. Giving them step-by-step, answer-withholding prompts: final exam up 0.22 SD. | WP |
| Liu et al. 2026 | 2,379 students, University of Maryland | Course chatbot left in its default answer mode: grades down 0.37 SD. Most requests asked for direct answers. | WP |
| Oreopoulos et al. 2026 | About 7,000 middle-school math students, Tennessee | Answer-withholding tutor alone: no effect at one week. With a mastery requirement: a small gain. | WP |
| Pardos and Bhandari 2024 | 274 learners, algebra and statistics | AI-written hints matched human-written hints. | PR |
| Chen et al. 2025 | 148 students in a proof course | Homework improved; exams did not. | WP |
| OpenAI 2026 | 300+ college students | Study mode: microeconomics up about 15%; neuroscience no difference. | VENDOR |
| Google 2026 | 1,763 junior-secondary students, Sierra Leone | Gemini tutoring: math up 0.258 SD. | VENDOR |

Three patterns run through these results. When the AI does the work, scores rise and learning does not.
Withholding answers prevents harm but does not by itself produce gains. Gains appear when the setup makes the
student generate: step-by-step prompts, a mastery bar, or a person in the loop. Several studies also find that
stronger students gain more, so these tools can widen gaps.

## What is still missing

- No randomized trial in university calculus, linear algebra, or differential equations with a later test taken
  without AI.
- No study measures retention past one week.
- No independent randomized trial of any vendor study mode.
- No study of whether students keep a study mode switched on when the regular mode is one click away.
- No trial isolates the effect of making students explain, though it is the book's central move.

## A warning about meta-analyses

A widely cited meta-analysis reporting a large effect of ChatGPT on learning (Wang and Fan 2025, g = 0.867) was
**retracted in 2026**. Many secondary sources still cite it. Another meta-analysis reported g of about 0.70 (Deng
et al. 2025), but audits found that only about one comparison in ten matched the groups on teaching method,
practice, and time on task. Do not quote either effect size.

## References

### Learning outcomes

1. Bastani, H., et al. (2025). Generative AI without guardrails can harm learning: Evidence from high school
   mathematics. *PNAS* 122, e2422633122. https://doi.org/10.1073/pnas.2422633122 **[PR]**
2. Kestin, G., Miller, K., Klales, A., Milbourne, T., and Ponti, G. (2025). AI tutoring outperforms in-class
   active learning. *Scientific Reports* 15, 17458. https://doi.org/10.1038/s41598-025-97652-6 **[PR]**
3. Gallegos (2026). Guidance over adoption: Experimental evidence on AI-assisted learning. IZA DP 18513.
   https://docs.iza.org/dp18513.pdf **[WP]**
4. Liu et al. (2026). The effects of course-integrated AI tutoring on student performance and engagement: A
   randomized university trial. IZA DP 18989. https://docs.iza.org/dp18989.pdf **[WP]**
5. Oreopoulos, Liut, Sungu, and Low (2026). Making AI tutoring productive: Evidence from a mastery-based math
   practice experiment. EdWorkingPaper 26-1552. https://edworkingpapers.com/sites/default/files/ai26-1552.pdf **[WP]**
6. Fischer, Rau, and Rilke (2025). AI tutoring enhances student learning without crowding out reading effort.
   IZA DP 18338. https://docs.iza.org/dp18338.pdf **[WP]**
7. Pardos, Z. A., and Bhandari, S. (2024). ChatGPT-generated help produces learning gains equivalent to human
   tutor-authored help on mathematics skills. *PLoS ONE* 19(5), e0304013.
   https://doi.org/10.1371/journal.pone.0304013 **[PR]**
8. Chen et al. (2025). Generative AI alone may not be enough: Evaluating AI support for learning mathematical
   proof. arXiv 2509.16778. https://arxiv.org/abs/2509.16778 **[WP]**
9. Fan et al. (2025). Beware of metacognitive laziness. *British Journal of Educational Technology*.
   https://doi.org/10.1111/bjet.13544 **[PR]**
10. Prather et al. (2024). The widening gap: The benefits and harms of generative AI for novice programmers.
    ICER 2024. https://arxiv.org/abs/2405.17739 **[PR]**
11. Oreopoulos, P., and Low, N. (2026). One click away: AI tutoring with Khanmigo in a two-year school
    experiment. EdWorkingPaper 26-1551. https://edworkingpapers.com/sites/default/files/ai26-1551.pdf **[WP]**
12. Wang, R. E., Ribeiro, A. T., Robinson, C. D., Loeb, S., and Demszky, D. Tutor CoPilot: A human-AI approach
    for scaling real-time expertise. arXiv 2410.03017. https://arxiv.org/abs/2410.03017 **[WP]**
13. Kapoor et al. (2025). Exploring student behaviors and motivations using AI TAs with optional guardrails.
    arXiv 2504.11146. https://arxiv.org/abs/2504.11146 **[WP]**
14. OpenAI (2026). Understanding AI and learning outcomes.
    https://openai.com/index/understanding-ai-and-learning-outcomes/ **[VENDOR]**
15. Google DeepMind (2026). Measuring the impact of learning with AI in Sierra Leone and beyond.
    https://deepmind.google/blog/measuring-the-impact-of-learning-with-ai-in-sierra-leone-and-beyond/ **[VENDOR]**
16. LearnLM Team and Eedi (2025). AI tutoring can safely and effectively support students: An exploratory RCT in
    UK classrooms. arXiv 2512.23633. https://arxiv.org/abs/2512.23633 **[WP, VENDOR]**

### Reviews and critiques

17. Wang and Fan (2025). The effect of ChatGPT on students' learning performance, learning perception, and
    higher-order thinking: Insights from a meta-analysis. *Humanities and Social Sciences Communications*.
    **[RETRACTED 2026]**
18. Deng, Jiang, Yu, Lu, and Liu (2025). Does ChatGPT enhance student learning? A systematic review and
    meta-analysis of experimental studies. *Computers and Education* 227, 105224.
    https://doi.org/10.1016/j.compedu.2024.105224 **[PR]**
19. Weidlich, Gašević, Drachsler, and Kirschner (2025). ChatGPT in education: An effect in search of a cause.
    *Journal of Computer Assisted Learning* 41(5), e70105. https://doi.org/10.1111/jcal.70105 **[PR]**
20. Lawson, Martella, Weidlich, Mulders, and Buchner (2026). Color me confounded: A critical analysis of media
    comparisons on ChatGPT in education. *Computers and Education*, in press.
    https://doi.org/10.1016/j.compedu.2026.105701 **[PR]**

### The tools

21. Liffiton, M., Sheese, B., Savelka, J., and Denny, P. (2023). CodeHelp: Using large language models with
    guardrails for scalable support in programming classes. Koli Calling 2023.
    https://doi.org/10.1145/3631802.3631830 **[PR]**
22. Sheese, B., Liffiton, M., Savelka, J., and Denny, P. (2024). Patterns of student help-seeking when using a
    large language model-powered programming assistant. ACE 2024. https://doi.org/10.1145/3636243.3636249 **[PR]**
23. Liu, R., et al. (2024). Teaching CS50 with AI. SIGCSE 2024. https://doi.org/10.1145/3626252.3630938 **[PR]**
24. Liu, R., et al. (2025). Improving AI in CS50: Leveraging human feedback for better learning. SIGCSE TS 2025.
    https://doi.org/10.1145/3641554.3701945 **[PR]**
25. Pardos, Z. A., et al. (2023). OATutor: An open-source adaptive tutoring system and curated content library.
    CHI 2023. https://doi.org/10.1145/3544548.3581574 **[PR]**
26. Otte, P., Bos, R., Commelin, J., and Portegies, J. (2026). The educational proof assistant Waterproof in an
    introductory proof course. arXiv 2606.26809. https://arxiv.org/abs/2606.26809 **[WP]**
27. Pisan, Y. (2026). Teaching a large language model tutor to withhold the answer. arXiv 2608.12292.
    https://arxiv.org/abs/2608.12292 **[WP]**
