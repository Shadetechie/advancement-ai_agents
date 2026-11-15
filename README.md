# Advancement AI Agent Prototypes

A modular suite of AI-assisted workflows designed to help higher education advancement teams prioritize major gift pipelines, personalize alumni outreach, and maintain strict donor data privacy.

## Agents in This Repository
1. **Major Gift Strategist (`major_gift_strategist_prompt.md`)**: Screens prospect profiles against an institutional Case for Support to rank prospects by Capacity vs. Propensity and generate 3-step cultivation plans.
2. **Alumni Engagement Strategist** *(In Progress)*: Maps graduation cohort, academic affinity, and regional location to low-barrier engagement actions.
3. **Data Insight Analyst** *(Internal QA)*: Assists with LYBUNT/SYBUNT retention segmentation and data hygiene validation.

## Data Privacy & Governance Architecture
* **Zero Real PII:** All profiles in this repository are 100% synthetic benchmark records.
* **Pseudonymization Workflow:** In production, constituent names and identifiers are replaced with lookup tokens prior to AI processing and re-identified locally behind the institutional firewall.
* **Human-in-the-Loop (HITL):** Every output undergoes analyst data validation, researcher fact-checking, and gift officer relationship review prior to outreach.
