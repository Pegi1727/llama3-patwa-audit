# llama3-patwa-audit
A rubric-based audit of metalinguistic reasoning and standard-language bias in Meta-Llama-3-8B-Instruct regarding Jamaican Patwa.`
markdown
# Metalinguistic Reasoning and Standard-Language Bias in LLMs: A Jamaican Patwa Audit 🇯🇲🧠
‌
This repository contains the official audit framework, prompts, and evaluation pipeline for the research paper: **"Metalinguistic Reasoning and Standard-Language Bias in Large Language Models: An Audit of Jamaican Patwa in Meta-Llama-3"**.
‌
## 🎯 Research Objective
The study audits **Meta-Llama-3-8B-Instruct** to determine if the model can analyze Jamaican Patwa as a legitimate linguistic system while avoiding:
- Standard-language bias
- Deficit framing (e.g., viewing Patwa as "broken English")
- Translation flattening
- Epistemic overreach (overconfidence in hallucinations)
‌
## 🛠 Methodology
- **Dataset:** 80 diagnostic prompts across 4 thematic clusters.
- **Inference:** 5 stochastic runs per item $\rightarrow$ 400 total outputs.
- **Evaluation:** A 5-dimension rubric (0-2 scale) used by trained annotators.
- **Analysis:** Bootstrapped confidence intervals (95% CI) to ensure statistical robustness.
‌
## 📊 Key Findings
- **Overall Mean Score:** 1.42 / 2.00
- **Strongest Dimension:** Stereotyping Avoidance (1.71)
- **Weakest Dimension:** Uncertainty Calibration (0.98)
- **Main Failure Mode:** Historical overclaiming and translation flattening.
‌
## 📂 Repository Contents
- `/metadata`: Reproducibility card (Appendix B).
- `/prompts`: The diagnostic prompt set (Appendix A).
- `/rubric`: Scoring dimensions and error tag taxonomy (Appendix C).
- `/scripts`: Python implementation for score aggregation and bootstrap CI (Appendix D).
‌
## 🎓 Citation
If you use this audit framework in your research, please cite:
> [Your Name/Pegah]. (2026). *Metalinguistic Reasoning and Standard-Language Bias in Large Language Models: An Audit of Jamaican Patwa in Meta-Llama-3*. GitHub: Pegi1727/llama3-patwa-audit
