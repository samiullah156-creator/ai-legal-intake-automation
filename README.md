<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=AI%20Legal%20Intake%20%26%20Law%20Firm%20Automation&fontSize=31&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20AI%20automation%20in%20n8n&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="AI Legal Intake & Law Firm Automation" />

**An n8n system with AI agents that takes a law firm's client intake, case processing, follow-ups and deadlines off the team's desks.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/AI%20automation%20in%20n8n-9533fa?style=flat-square" alt="AI automation in n8n" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI-231f20?style=flat-square" alt="OpenAI" />
  <img src="https://img.shields.io/badge/AI%20Agents-231f20?style=flat-square" alt="AI Agents" />
  <img src="https://img.shields.io/badge/Vapi-231f20?style=flat-square" alt="Vapi" />
  <img src="https://img.shields.io/badge/REST%20APIs-231f20?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Email-231f20?style=flat-square" alt="Email" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#screens">Screens</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![n8n workflow for AI legal intake and law firm automation](assets/cover.webp)

## Overview

A legal team handled client intake, case information, follow-ups and deadlines by hand, so leads and tasks slipped through. We built one production workflow in n8n, triggered by calls and web enquiries, where AI agents read each new matter, create the right tasks and records, send client updates and alert the team across their channels. The firm now runs intake, tasks and deadlines through one automated system with no manual data entry.

## The challenge

Client intake, case details, follow-ups and deadlines were all handled manually. New enquiries waited, information was re-typed between tools, and tasks were easy to miss when the team was busy.

## The solution

A production n8n workflow with AI agents: smart client intake from calls and forms, AI case processing and task creation, automated client follow-ups and updates, deadline and document handling, and team notifications across channels.

## How it works

```mermaid
flowchart LR
    A(["A new<br/>enquiry arrives"]) --> B
    B["AI reads and<br/>classifies the case"] --> C
    C["Tasks, records and<br/>deadlines created"] --> D
    D(["Client and<br/>team updated"])

    classDef box fill:#1d1726,stroke:#167dfe,color:#e5e7eb
    classDef ends fill:#2e1065,stroke:#9533fa,color:#ffffff
    class B,C box
    class A,D ends
```

1. **A new enquiry arrives.** A call through the voice agent or a web form starts the workflow. The caller's details and the facts of the matter are captured once.
2. **AI reads and classifies the case.** AI agents extract the key facts, classify the matter type and check what information is still missing.
3. **Tasks, records and deadlines created.** The right tasks, case records and deadline reminders are created automatically, with no re-typing.
4. **Client and team updated.** Follow-up messages go to the client and the team is notified on the channels they already use.

## Key features

- Smart legal client intake from calls and web forms
- AI case processing and task creation
- Automated client follow-ups and status updates
- Deadline and document handling
- Team notifications across channels

## Results

- Intake, tasks and deadlines run through one automated system
- No manual data entry between intake and case records

## Tech stack

![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI-1d1726?style=for-the-badge) ![AI Agents](https://img.shields.io/badge/AI%20Agents-1d1726?style=for-the-badge) ![Vapi](https://img.shields.io/badge/Vapi-1d1726?style=for-the-badge) ![REST APIs](https://img.shields.io/badge/REST%20APIs-1d1726?style=for-the-badge) ![Email](https://img.shields.io/badge/Email-1d1726?style=for-the-badge) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-1d1726?style=for-the-badge)

## Screens

![How AI Legal Intake & Law Firm Automation works: Call or web form, AI intake agent, Case record and tasks, Deadline reminders, Client and team updated](assets/screen-1.webp)

![AI Legal Intake & Law Firm Automation: before and after](assets/screen-2.webp)

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/ai-legal-intake-automation

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
