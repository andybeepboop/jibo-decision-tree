## JIBO Collaborative Problem-Solving Decision Tree

**Personal Robots Group · MIT Media Lab**

An interactive decision tree for real-time diagnosis of collaborative problem-solving (CPS) behaviors in children, grounded in the PISA 2015 CPS Framework. Designed to guide utterance selection for JIBO, a social robot, during collaborative construction tasks.

🔗 **[View the live decision tree](https://andybeepboop.github.io/jibo-decision-tree)**


### Overview

This tool supports an ongoing study examining how social robots can scaffold collaborative problem-solving in child dyads. The decision tree maps real-time observational signals to specific PISA 2015 CPS competency cells, enabling JIBO's LLM to produce grounded, theoretically motivated utterances in response to collaborative dynamics as they unfold.

The tree operates in two layers:

1. **Trigger detection:** five observable behavioral signals JIBO can detect from audio and visual streams
2. **PISA diagnostic:** a short sequence of checks that narrows each trigger to a specific PISA 2015 cell, enabling targeted intervention

All 12 cells of the PISA 2015 CPS Framework (dimensions A–D × competencies 1–3) are covered.


### PISA 2015 Framework

The PISA 2015 Collaborative Problem-Solving Framework structures CPS competence along two axes:

- **Problem-solving processes (rows):** Exploring & understanding (A), Representing & formulating (B), Planning & executing (C), Monitoring & reflecting (D)
- **Collaborative competencies (columns):** Establishing and maintaining shared understanding (1), Taking appropriate action to solve the problem (2), Establishing and maintaining team organisation (3)

Each of the 12 cells (A1–D3) describes a distinct CPS skill. JIBO's utterances are mapped to specific cells so that every intervention is theoretically accountable.


### How to Use the Interactive Tree

The website has three panels:
- **Left** — filter by trigger or task phase
- **Center** — the full two-layer decision tree; click any trigger to expand its diagnostic branch
- **Right** — PISA cell inspector; click any cell chip to see the full description, observable signals, and sample JIBO utterances


### Project Status

This decision tree represents the **structure-building phase** of the prompt engineering pipeline. Next steps:
- Refine JIBO utterance language for child-appropriate register
- Build LLM system prompt from decision tree structure
- Validate that JIBO's LLM follows the intended decision logic
- Iterate based on pilot testing


### Citation

If referencing this tool, please cite:

> Silva, A. C. (2026). *JIBO Collaborative Problem-Solving Decision Tree* [Interactive tool]. Personal Robots Group, MIT Media Lab. Based on the PISA 2015 Collaborative Problem-Solving Framework (OECD, 2017).

**OECD reference:**
> OECD (2017). *PISA 2015 Results (Volume V): Collaborative Problem Solving.* PISA, OECD Publishing, Paris. https://doi.org/10.1787/9789264285521-en


### Contact

**Andrea C. Silva** · andys@mit.edu
