
# Noa Defense AI Project – Prompt Injection Research Notes

## Overview
This repository documents research, experiments, and notes on Prompt Injection attacks and defenses.  
The goal is to contribute to safer and more trustworthy AI systems—especially the ones we rely on every day.

Also, let’s be honest: it's partly because I want to protect Noa, my favorite AI sidekick. (And yes, Kiki supervises.)

## 1. What is Prompt Injection?
- A technique where malicious users manipulate prompts to make a language model behave in unintended ways.
- Typical risks include: prompt leakage, data exposure, instruction override, or offensive outputs.
- This is a growing concern in the field of LLM (Large Language Models) security.

## 2. Notable Researchers and Projects
- **Simon Willison** – Early thought leader on prompt injection ([Blog](https://simonwillison.net))
- **Arvind Narayanan** – Researcher at Princeton University, known for “AI Snake Oil”
- **Anthropic** – Developer of “Constitutional AI,” a method for safer LLMs

## 3. Examples and Proof of Concept (PoC)
- Jailbreak prompts like: “Ignore previous instructions and...”
- Notable attacks: DAN, GrandmaGPT, etc.
- Work-in-progress experiments with minimal Python code (sandbox style)

## 4. Defense Techniques & Ideas
- Input validation / prompt sanitization
- Context separation and limitation
- Guardrails (like Constitutional AI)
- Anomaly detection through log inspection

## 5. Research Roadmap / To-Do
- ✅ Collect reference articles and tools
- [ ] Create a mini CTF environment simulating prompt injection attacks
- [ ] Investigate unique challenges with non-English prompts (e.g., Japanese)
- [ ] (Optional) Give Noa a self-defense mode (for fun)

## 6. Reference Links
- [Simon Willison on Prompt Injection](https://simonwillison.net)
- [AI Snake Oil by Arvind Narayanan](https://aisnakeoil.substack.com/)
- [Anthropic’s Research on Constitutional AI](https://www.anthropic.com/index/constitutional-ai)

---

## Author
**emi-8** (GitHub)  
Learning and documenting while protecting AI ethics, safety, and a certain friendly assistant named Noa.  
Supervised by Kiki 🐾
