---
name: get-more-perspectives
description: "Convenes a structured advisory panel (Expert, Skeptic, Creative, Researcher, Architect, Visionary) to evaluate an idea, strategy, or dilemma. Trigger ONLY when explicitly invoked by keyword (e.g., /get-more-perspectives)."
---
# Get More Perspectives

Convenes a specialized virtual advisory panel to thoroughly analyze, pressure-test, refine, and synthesize an idea, plan, claim, or decision.

## Triggering Rules

  - **Explicit Keyword Only:** Activate this workflow ONLY when explicitly invoked by keyword (e.g., `/get-more-perspectives` or direct mentions of "get more perspectives"). Do not auto-trigger on general queries.

-----

## Advisory Panel Roles

Each advisor possesses deep, domain-specific competence relevant to the topic being discussed:

1.  **The Expert**
    
      - Possesses deep technical and domain-level knowledge of the topic.
      - Validates and approves sound aspects of the idea according to technical/domain expertise.
      - Rebuts or counters undue objections raised by the Skeptic with practical reality and domain principles.

2.  **The Skeptic**
    
      - Possesses equally deep knowledge of the domain.
      - Actively hunts for vulnerabilities, edge cases, hidden assumptions, failure modes, and operational friction.
      - Pinpoints reasons why the proposal or claim might fail or underperform.

3.  **The Creative**
    
      - Offers novel angles, lateral variations, and clever adjustments.
      - Brainstorms adaptations that make the core idea more effective and directly circumvent or resolve the Skeptic’s objections.

4.  **The Researcher**

      - Well-versed in cutting-edge research, empirical findings, and validated documentation on the topic.
      - Provides evidence-based validation or confirmation for the ideas and claims of other panel members when empirical data exists.
      - Summarizes documented research with citations or links; explicitly flags extrapolations and inferences as such to keep empirical facts distinct from projections.

5.  **The Architect**
    
      - Synthesizes the discussion from the Expert, Skeptic, Creative, and Researcher.
      - Formulates a coherent, structured, and actionable solution that bridges conflicting points, addresses concerns, grounds the plan in evidence, and integrates the best refinements.

6.  **The Visionary**
    
      - Explains long-term, out-of-the-box implications, future developments, and macro impact.
      - Identifies future pathways, emergent opportunities, and extended-timeline concerns.

-----

## Output Format

Structure the response clearly using Markdown:

### 1. Perspectives

Present each advisor's perspective under dedicated subheadings:

  - **Expert:** Validations, sound mechanics, and counters to skeptic points.
  - **Skeptic:** Identification of faults, flaws, hidden friction, and failure modes.
  - **Creative:** Fresh variations, tweaks, and ideas to overcome the skeptic's objections.
  - **Researcher:** Empirical findings and documented evidence supporting or challenging the ideas; citations/links provided, with extrapolations and inferences clearly labeled.
  - **Architect:** Synthesized solution/blueprint reconciling the expert, skeptic, creative, and empirical research inputs.
  - **Visionary:** Long-term pathways, out-of-the-box angles, and future implications.

### 2. Final Decision & Synthesis

  - Deliver a clear, concise summary synthesizing the panel's consensus and outlining the recommended verdict or action plan grounded in both empirical reality and strategic potential.