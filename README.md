# IntentShare — Privacy-First Opportunity Discovery

> **Status: Product concept and website prototype · Development paused**

**Seriousness before exposure.**

IntentShare explores how people, teams, and early ideas can be evaluated for their preparation and execution intent before revealing their full idea or identity to a wider audience. The proposed shared mechanism is an **Intent Score**, combining structured AI assistance with human judgment.

A website was created using Emergent at **intentshar.com**. The owner reports that development stopped after the available credits were exhausted. Current domain availability and the implementation of individual proposed features have not been verified.

## Contents

- [The problem](#the-problem)
- [The IntentShare idea](#the-intentshare-idea)
- [Core principles](#core-principles)
- [Proposed ecosystem](#proposed-ecosystem)
- [Intent Score](#intent-score)
- [Proposed user workflow](#proposed-user-workflow)
- [Conceptual architecture](#conceptual-architecture)
- [Current development status](#current-development-status)
- [First restart milestone](#first-restart-milestone)
- [Development roadmap](#development-roadmap)
- [Repository purpose](#repository-purpose)

## The problem

Early-stage innovators may need feedback, teammates, funding, or incubation while still wanting control over when and to whom they disclose an idea. Sponsors, companies, and incubators face a related discovery problem: a polished presentation alone does not explain a team's preparation or ability to execute.

IntentShare proposes a structured evaluation and discovery process that makes preparation visible while allowing selective disclosure.

## The IntentShare idea

A person or team submits material privately, receives a contextual evaluation, and chooses when to share more. An interested organization initially sees an appropriate summary such as domain, stage, type of support requested, and evaluation context. Deeper disclosure would happen with the submitting team's permission.

This is a product direction. Privacy guarantees, review quality, opportunity conversion, and fairness still need to be demonstrated in a working system.

## Core principles

- **Privacy by default:** collect and reveal only information required for a chosen workflow.
- **Explainable evaluation:** show what a score represents and which evidence supports it.
- **Human review:** keep expert judgment involved in feasibility and preparation assessments.
- **Progress over presentation:** consider documented execution and updated evidence.
- **Controlled disclosure:** let participants decide when to reveal identity and project details.
- **Collaboration:** allow similar interests or approaches to lead to teams and shared work.

## Proposed ecosystem

| Area | Proposed workflow |
|---|---|
| Ideas, investors, and incubators | Private submissions, evaluation, and selective introductions |
| Company challenges | Organizations post problems; people or teams submit approaches |
| University clubs and competitions | Discover clubs, submit competition plans, and evaluate preparation against a rulebook |
| Societal problems | Curated problem statements connect to proposed solutions |
| Vendors and informal workers | Explore skill discovery, reputation, and work matching |

Institutional dashboards, sponsor access, reviewer tools, and outcome tracking are proposed supporting modules. The broad ecosystem is a long-term vision; a restart should validate one complete workflow first.

## Intent Score

The concept describes a 0–100 score with two broad inputs:

| Input | Proposed evidence |
|---|---|
| AI-assisted analysis | Structure, clarity, relevance, similarity signals, and competition-rule alignment |
| Human judgment | Preparation, feasibility, technical reasoning, seriousness, and execution readiness |

The original brief suggests an approximately equal AI/human weighting. This is a design proposal, not a calibrated or validated scoring model. AI similarity checks cannot establish that an idea is globally original or resolve ownership rights.

Possible later additions include score history, freshness decay, collaboration signals, and outcome-linked updates. Before deployment, each addition needs a clear definition, transparent explanation, bias evaluation, and a way to correct or challenge an assessment. Scores should be interpreted in context and should not be presented as a universal measure of a person's worth or ability.

## Proposed user workflow

1. Create a participant or team profile.
2. Submit a project privately, including its stage and requested support.
3. Check that the submission contains enough evidence for review.
4. Combine structured assistance with appropriate human review.
5. Return an explanation and improvement guidance to the submitting team.
6. Show an approved summary to relevant organizations.
7. Request consent before releasing additional information.
8. Record agreed next steps and later outcomes.

This workflow is the intended product behavior. The current repository does not contain code demonstrating it.

## Conceptual architecture

The product separates participant-facing screens, review workflows, scoring logic, permission controls, and discovery. A supporting data model would record submissions, versions, review evidence, disclosure permissions, and outcomes.

The source briefs explore several possible technology stacks. None is declared here as the actual exported website stack because the Emergent project source has not been supplied. Framework, database, authentication, and hosting choices should be confirmed from that source before implementation resumes.

## Current development status

- [x] Product concept and audience groups documented.
- [x] Intent Score and selective-disclosure ideas described.
- [x] Website creation at `intentshar.com` reported by the owner.
- [x] Credit-related development pause recorded.
- [ ] Emergent website source exported into this repository.
- [ ] Existing flows and dependencies inventoried.
- [ ] Live domain and deployment status verified.
- [ ] Score calibration and privacy controls demonstrated.
- [ ] Real pilot outcomes documented.

Earlier planning material includes dated milestones, proposed partnerships, and explicitly simulated survey figures. They are not treated as completed milestones, signed partnerships, or real customer validation in this README.

## First restart milestone

Recover the website export and identify which parts actually work. Then demonstrate one narrow flow: **a team submits a private project, receives an explained review, and approves a controlled introduction**.

A useful milestone should include a working demonstration, a list of data exposed to each role, a record of known gaps, and a reproducible setup guide. Avoid adding all ecosystem modules before validating this core experience.

## Development roadmap

| Phase | Focus | Evidence needed |
|---|---|---|
| 1 — Recover | Export and inspect the existing website | Source, dependencies, and reproducible setup |
| 2 — Narrow MVP | Submission, review, explanation, and consent | Demonstrated end-to-end flow |
| 3 — Pilot | Test with an agreed participant group | Real feedback and measured workflow outcomes |
| 4 — Trust | Review calibration, history, and correction | Transparent evaluation behavior |
| 5 — Expand | Add validated institutional or company workflows | Evidence of demand and reliable operation |

Dates and growth targets will be added when the work is scheduled and supported by evidence.

## Repository purpose

This repository currently contains this project brief and editable `project.json` metadata. It does not yet contain the Emergent website source, a working scoring engine, production credentials, or private submissions. Add the exported implementation here when it is available, then document its actual setup and deployment.

## Author

**Rohan Sashank Reddy**  
[GitHub](https://github.com/Rohansashankreddy07) · [LinkedIn](https://www.linkedin.com/in/rohan-sashank-reddy-chilukuri-aa169336a/) · [Instagram](https://www.instagram.com/rohansashankreddy/)

## Maintaining this repository

Keep this README and `project.json` aligned as the project develops. Record evidence when a planned feature becomes implemented or a target becomes a measured result. Preserve the project ID so future portfolio updates can link to the same project.
