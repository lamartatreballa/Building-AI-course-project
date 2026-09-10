# Building-AI-course-project
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# CivicPulse

Final project for the Building AI course:

AI for citizen concerns and policy alingment based on evidence.

## Summary

CivicPulse is an AI system that collects and structures citizens’ worries and concerns, contrasts them with objective urban and environmental data (noise, pollution, traffic, etc.), checks the relevant regulation (local, national, supranational...), and generates evidence‑based policy proposals for public administrations.

It aims to turn scattered complaints into **actionable, legally grounded recommendations**.

## Background

### The problem

Citizens often express worries about:

- Noise and nightlife.
- Air pollution and traffic.
- Public space use.
- Mobility and safety.
- Housing and tourism pressure.

These concerns are usually:

- Fragmented across channels (email, social media, meetings).
- Unstructured and hard to compare.
- Weakly connected to objective data.
- Rarely mapped systematically to existing regulation.

As a result, administrations receive **noise instead of structured insight**, and citizens feel unheard.

### Motivation

I want to build a bridge between:

- **Citizen sentiment** (what people feel and report),
- **Objective indicators** (what data shows),
- **Regulatory frameworks** (what is allowed, required, or constrained),

so that proposals to the administration are:

- Evidence‑based.
- Legally coherent.
- Transparent and explainable.

This is important because it can:

- Improve trust between citizens and institutions.
- Reduce purely anecdotal debates.
- Help prioritize interventions where data and worries align.


## How is it used?

### Users

- Citizen platforms and neighbourhood associations.
- Municipal departments (urbanism, environment, mobility).
- NGOs and civic tech groups.
- Researchers in urban policy and governance.

### Workflow (general)

1. **Collect** citizen concerns via a unified interface.
2. **Process** them with NLP to extract topics, locations, and intensity.
3. **Contrast** them with objective indicators (noise, pollution, traffic, etc.).
4. **Check** relevant regulation at all levels.
5. **Generate** a structured report:
   - Summary of concerns.
   - Data comparison.
   - Regulatory context.
   - Proposed measures and priorities.

This report can be shared with administrations as a **policy brief**.

## Data sources and AI methods
### Data sources (general)

- **Citizen input:**
  - Online forms, surveys, complaint portals, ombudsman reports...
  - Meeting minutes, public consultations.
  - Social media posts (optional, with care).

- **Objective data:**
  - Noise levels (sensor networks, municipal data).
  - Air quality (PM2.5, NO₂, O₃, etc.).
  - Traffic intensity and mobility patterns.
  - Land use, zoning, green areas.
  - Accident and safety statistics.

- **Regulation and norms:**
  - Municipal ordinances (noise, terraces, mobility).
  - Regional regulations.
  - National laws.
  - Supranational directives (e.g., environmental, air quality, noise).

### AI techniques

- **NLP for citizen concerns:**
  - Text classification (topic detection: noise, pollution, mobility…).
  - Named entity recognition (places, times, actors).
  - Sentiment and intensity scoring (how strong is the concern).

- **Data alignment:**
  - Geocoding of complaints (link to specific areas).
  - Retrieval of relevant indicators (noise levels, pollution, traffic).
  - Comparison between perceived and measured conditions.

- **Regulation retrieval:**
  - Semantic search over legal texts.
  - Mapping concerns to applicable articles/limits.
  - Identification of thresholds (e.g., max dB at night).

- **Proposal generation:**
  - Template‑based recommendation generation.
  - LLM‑assisted drafting of policy suggestions:
    - “Given X complaints, Y data, and Z regulation, suggest measures A, B, C.”

## Challenges

- **Data availability:** Not all cities have open, granular data.
- **Bias and representation:** Some groups complain more than others; silent groups may be underrepresented.
- **Legal complexity:** Regulation is vast, evolving, and sometimes ambiguous.
- **Interpretability:** AI suggestions must be transparent and auditable.
- **Scope:** The system cannot replace political judgment or democratic processes.

CivicPulse does **not** decide policy; it **supports** it with structured insight.

## What next?

Future directions:

- Build a web dashboard for real‑time monitoring of concerns and indicators.
- Integrate with city open data APIs.
- Add multi‑language support (e.g., Catalan, Spanish, English).
- Collaborate with civic tech communities and local administrations.
- Extend to other domains (housing, tourism, social services).

Long‑term, CivicPulse could become a standard tool for **evidence‑based citizen advocacy**.

## Acknowledgments

- Built on concepts from CS50 AI (search, NLP, modeling).
- Use of Copilot for refining and editing both the idea and the delirevable.  
