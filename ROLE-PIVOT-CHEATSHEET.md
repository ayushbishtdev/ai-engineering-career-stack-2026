# Role Pivot Cheatsheet: Transitioning to 2026 AI Engineering

Don't apply to generic "AI Engineer" roles. Match your current background to the shortest on-ramp to avoid recruiter screens.

## From SRE / DevOps ➡️ AI Reliability Engineer or LLMOps Engineer
* **The Pivot Time:** 2-3 months.
* **The Gap:** Traditional SRE manages deterministic metrics (CPU, server ping). AI Reliability manages probabilistic metrics (token window inflation, hallucination loops).
* **What to learn:** Multi-provider API fallback orchestration, prompt versioning pipelines, and CI/CD for LLMs.

## From QA / Data Science ➡️ AI Evals Engineer
* **The Pivot Time:** Immediate to 2 months.
* **The Gap:** Traditional QA tests deterministic code paths. AI Evals testing builds statistical pipelines to evaluate highly non-deterministic model failure modes.
* **What to learn:** LangSmith, Braintrust, Maxim AI. You must understand the difference between an "Eval", a "Trace", and a "Span".

## From Offensive Security / Pentesting ➡️ AI Red Team Engineer
* **The Pivot Time:** 3-6 months.
* **The Gap:** 70% of pentesters fail the pivot because they rely on deterministic network code execution. AI Red Teaming requires adversarial machine learning (manipulating weights, poisoning embeddings).
* **What to learn:** OWASP LLM Top 10, MITRE ATLAS taxonomy, and automated fuzzing tools like garak, PyRIT, and promptfoo.
