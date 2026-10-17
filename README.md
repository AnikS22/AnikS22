<div align="center">

<img src="assets/portrait-sf.svg" width="300" alt="Anik Sahai, rendered as a dot matrix">

# Anik Sahai

**I work on embodied AI that can tell when it is about to fail, and on how people perceive the AI systems they talk to.**

AI Research Lead, SIMA Lab, FAU Center for Connected Autonomy & AI · Founder, AuthAI · Co-founder, [The Ethics Lab](https://ethicslabs.ai) · Non-Trivial Fellow

[aniksahai.com](https://aniksahai.com) · [LinkedIn](https://www.linkedin.com/in/aniksahai/) · [X](https://x.com/n1kdev) · aksahai07@gmail.com

</div>

---

I'm a junior at FAU High in Boca Raton, dual-enrolled at Florida Atlantic University. Most of my time goes
to robot policies and the tooling around them: getting a vision-language-action model or a navigation
stack off the simulator and onto real hardware, and finding the runs where it breaks. I work across the
whole stack, from wiring and firmware to ROS 2, perception, and models.

## Research

| Work | Role | Status |
|---|---|---|
| **GAIN: Grounded Active Interactive Navigation in State-Dependent Environments.** A robot that notices it has to change its environment (open a door, call an elevator) before it can keep navigating. A foundation model decides what has to change; separate grounding and control modules decide where and how to act. In Isaac Sim, 90.8% success on doors and 86.7% on elevators, against 41.7% on elevators when the VLM is asked directly. Deployed on a Ranger Mini 3 + xArm6 in a campus building. [Robot stack →](https://github.com/AnikS22/utp_robot) | First author | Under review, ICRA 2027 |
| **PhysMent: An Interactive Approach for LLM Reasoning in Physics Problems.** A benchmark where LLMs have to run experiments in a MuJoCo simulator through a 26-function API to answer physics questions. 105 scenes, 7 models; accuracy falls from up to 80% on simple qualitative scenes to under 30% on the hardest ones. | Co-author (5th of 9), Algoverse | AI for Math Workshop, ICML 2026 (PMLR 306) |
| **Who Do You Think You're Talking To?** An IRB-approved study with 60 undergraduates over three sessions. Everyone talked to the same model, but people who were told their partner was human rated it warmer, more trustworthy and more equal, from the first session on (Wilks' Λ = .609, η² = .391). | With Vito Borio | Under review |
| **FLARE: failure prediction from frozen VLA activations.** A small MLP probe on the hidden states of OpenVLA and ACT predicts task failure (AUC 0.83 and 0.89, against 0.79 for linear-probe baselines) for under 1 ms per step. Using the probe to steer the policy did not help: a random correction direction did as well as the learned one. | First author | Unpublished |

## Projects

- **[utp_robot](https://github.com/AnikS22/utp_robot)**: the physical stack for GAIN. ROS 2 Jazzy, a fail-closed safety mux, a VLM + open-vocabulary detector for finding ADA push plates, and an experiment log that records the failures as well as the successes.
- **[golf-cart-code](https://github.com/AnikS22/golf-cart-code)**: converting a 2018 GEM e4 into a drive-by-wire autonomous vehicle at FAU. Firmware, ROS 2 stack, and a Gazebo twin of the Boca campus.
- **[MidasMap](https://github.com/AnikS22/MidasMap)**: detecting immunogold particles in TEM synapse images (CenterNet, CEM500K backbone, BiFPN).
- **[larvatrack](https://github.com/AnikS22/larvatrack)**: measures how far Drosophila larvae crawl, from a phone video. Built for Drosophila motor-behavior experiments in an FAU neurobiology course.
- **[EEG-Signal-CoLabs](https://github.com/AnikS22/EEG-Signal-CoLabs)**: emotion decoding from EEG on BS-HMS (Random Forest, 89% happy vs. sad).
- **[DR_Project](https://github.com/AnikS22/DR_Project)**: on-device diabetic-retinopathy screening from a live camera feed. Built in 8th grade; 1st place at the Florida state middle-school science fair ([AP](https://www.csmonitor.com/USA/Education/2024/0507/Florida-school-creative-curriculum-inspires)).

## Experience

- **AI Research Lead & MPCR Fellow**, SIMA Lab, FAU Center for Connected Autonomy & AI (advisor: Dr. Minghan Wei) · Sep 2025 to present
- **Founder, AuthAI**: prior-authorization automation for medical practices, piloted with a spine practice and a surgery center
- **Co-founder, [The Ethics Lab](https://ethicslabs.ai)**: free AI-ethics curriculum for K–12 classrooms; 500+ students so far · Nov 2025 to present
- **AI Engineer, LVNG.AI**: production ML, computer vision and NLP systems (PyTorch, AWS, GCP) · Aug 2025 to Jan 2026
- **Investment Research Intern, Canvas Prime**: digital health · Apr to Sep 2025
- **Non-Trivial Fellow** (2026)

## Recognition

- Diamond Challenge: 1st place, New York regional; international finalist (2026)
- Congressional App Challenge, FL-23 winner, for SunGuard, a skin-cancer screening app ([entry](https://www.congressionalappchallenge.us/25-FL23/), 2025)
- FAU Business Pitch Competition: Student Track runner-up, AuthAI ([Venture Tech Chronicle](https://www.vtchronicle.com/blog/the-next-generation-of-founders-takes-flight-at-faus-2026-business-pitch-competition), 2026)
- FAU Biotech Hackathon: 2nd prize, Health Lens AI (2026)
- DECA: state 1st, Independent Business Plan; ICDC competitor (2026)
- Congressional Debate: Harvard National quarterfinalist, Tournament of Champions and NSDA Nationals competitor (2026)
- Eagle Scout
- Best in Show, Junior Division, Palm Beach Regional Science & Engineering Fair ([FAU](https://adhus.fau.edu/news/science-fair-regionals-awards-23/))

Press: [Inc.](https://www.inc.com/georgia-fearn/america-startup-boom-just-hit-record-high-criticis-say-not-what-it-seems/91381351) ·
[Associated Press / CS Monitor](https://www.csmonitor.com/USA/Education/2024/0507/Florida-school-creative-curriculum-inspires) ·
[GoDaddy Research](https://www.godaddy.com/research/discover-the-most-entrepreneurial-cities-of-2026/) ·
[The Step One Podcast](https://podcasts.apple.com/us/podcast/can-ai-be-trusted-healthcare-ethics-and/id1895502241?i=1000788073320)

## Tools

Python · PyTorch · ROS 2 / Nav2 · Isaac Sim · MuJoCo · LIBERO · Hugging Face · CUDA · SLURM · C++ · Swift

<sub>Interested in runtime monitoring for embodied policies, interpretability, and evals. Happy to talk.</sub>
