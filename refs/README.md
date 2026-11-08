# Good Reads

1. **[Sparks of Weight-Space Programming](https://rikiyat.github.io/blog/weight-space-programming/)**  
   Takehi, Teoh, Zhang & Khattab · MIT CSAIL · Nov 2026  
   The original. Start with Experiment 8 (the math fix) and the Gemma follow-up.

2. **[RikiyaT/lm_understand-logs](https://github.com/RikiyaT/lm_understand-logs)**  
   GitHub  
   Every prompt, reply, line of code and score from that post. We replay their fix from these.

3. **[Rikiya Takehi’s site](https://rikiyat.github.io/)**  
   rikiyat.github.io  
   The lead author’s other work; follow-ups will appear here.

4. **[Weight-Space Programming and Gradient Optimization on Nonconvex Algorithmic Tasks](https://github.com/Fchaubard/WSP-for-turing-complete/blob/main/paper.pdf)**  
   Francois Chaubard & Astra · Stanford · Nov 2026  
   [Thread](https://x.com/francoischauba1/status/2119160536927699426) · [Code](https://github.com/Fchaubard/WSP-for-turing-complete)  
   WSP versus normal training on tiny networks. Astra is better at guessing the underlying rule, worse at fitting the data, and the authors say there’s no fair way yet to compare their costs. Our budget tracking is meant to fix that.

5. **[Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?](https://arxiv.org/abs/2504.13837)**  
   Yue et al. · 2025  
   Shows normal RL training mostly sharpens and doesn’t expand. The result we’re trying to beat.

6. **[LFM3: launch post](https://www.liquid.ai/blog/lfm3)**  
   Liquid AI · Nov 2026  
   Where our six benchmarks come from, and the “getting stuck” comparison between Qwen3.5-2B and LFM3.

7. **[LiveCodeBench](https://arxiv.org/abs/2403.07974)**  
   Jain et al. · 2024  
   The teacher’s target benchmark: contest problems graded by running tests.

8. **[SWE-bench](https://arxiv.org/abs/2310.06770)**  
   Jimenez et al. · 2023  
   The bug-fixing benchmark every lab competes on.

9. **[Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374)**  
   Chen et al. (Codex) · 2021  
   Where the pass@k formula comes from.

10. **[“Turns out you can teach a 35B model to weight-space program better than Opus”](https://x.com/neilkale/status/2118897078550307050)**  
    Neil Kale on X · Nov 7, 2026  
    An open model trained to do WSP: a possible free teacher.

11. **[One-shot weight-space programming results](https://x.com/alexkrentsel/status/2118845418411045034)**  
    Alex Krentsel on X · Nov 6, 2026  
    A leaderboard of models doing WSP. Shows how fast this is moving.

12. **[Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409)**  
    Yang et al. · 2023  
    An AI improving something by reading its own past attempts and scores. The same loop as our teacher, but for text instead of weights.

13. **[karpathy/autoresearch](https://github.com/karpathy/autoresearch)**  
    GitHub  
    AI agents that run training experiments on their own: the other route, where the AI writes training code instead of editing weights. My [gpu-setup post](https://blog.arjansuri.com/gpu-setup.html) covers running it.
