# Capitol Contracts LLC — What Really Happened (WRH) Trauma Psychoeducation Program | Official 30-Session Pilot Deployment Package v4.0

Capitol Contracts LLC presents the **What Really Happened (WRH) Trauma Psychoeducation Program**, an official 30-session pilot deployment package designed for federal contracting and institutional implementation. This repository serves as the consolidated, definitive source for the WRH program, integrating comprehensive facilitator materials with a modern web portal for digital delivery.

## Program Overview

The WRH program is a psychoeducational curriculum focused on understanding the mechanisms of complex trauma and nervous system dysregulation. It provides concrete tools for pattern interruption and executive function restoration without requiring trauma disclosure or traditional therapy modalities. The program is specifically tailored for high-risk populations, including veterans, justice-involved adults, recovery populations, and transitional-support participants.

### Key Upgrades in Version 4.0:
- **Tactical Cockpit Layout:** Every session is structured for rapid facilitator navigation with [Facilitator Action] and [Script/Cue] tables.
- **Fidelity Checkpoints:** Integrated callouts every 15-20 minutes to ground the facilitator and ensure room control.
- **Whiteboard Blueprints:** Text-based diagrams (Code Blocks) for mapping nervous system logic live in the room.
- **Glossary Linking:** Consistent use of `Code Text` for key program terms (e.g., `The Hum`, `The Pattern Veto`).
- **Executive Function Arc:** Completion of Sessions S25–S30 focusing on `Executive Function Restoration` and `Rewriting the Code`.

## Pilot Site A: Stepping Stones Recovery of Arkansas
We have officially locked in **Stepping Stones Recovery of Arkansas** (Hartman, AR) as Pilot Site A. This residential recovery program serves as our primary proof-of-concept for the 2026 deployment roadmap. For detailed site-specific logistics, see the [Stepping Stones Pilot Addendum](./pilots/Stepping_Stones_Pilot_Addendum.md).

## How to Deploy

This repository supports two primary deployment methods:

### 1. Facilitator-Led Sessions

The `manual/` directory contains the complete 30-session facilitator manuals (Version 4.0), designed for in-person, cohort-based delivery. Each session is structured for 75-minute facilitator-led engagement, utilizing a "Kali Reaper Tone" (analytical, high-velocity systems language). Key operational materials such as the Facilitator Readiness Checklist, Plan B Wallet Card, and a comprehensive Glossary are available in the `checklists/`, `assets/`, and `manual/` directories respectively.

### 2. Digital Delivery via Web Portal

The `portal/` directory houses a full-stack TypeScript application that serves as the digital delivery platform for the WRH program. This web portal provides an interactive interface for participants to access session content, resources, and other program materials. The portal is designed to load and serve the 30 session manuals as interactive web views, offering a modern and accessible experience.

## Folder Structure Map

```
WRH-Pilot-Deployment-Package/
├── README.md                     # This file
├── SUMMARY.md                    # Master navigation and program overview
├── assets/                       # General program assets (e.g., Plan B Wallet Card, VA Program Description)
├── checklists/                   # Facilitator checklists and safety rules
├── digital-assets/               # Consolidated images and PDFs from other repos
├── legal/                        # Legal and business documents (e.g., Capability Statement, Program Description)
├── manual/                       # Official 30-session facilitator manuals and Glossary
├── pilots/                       # Site-specific pilot deployment plans
└── portal/                       # Full-stack web application for digital content delivery
    ├── client/                   # Frontend React application
    ├── server/                   # Backend tRPC API and database logic
    ├── shared/                   # Shared types and constants
    ├── drizzle/                  # Drizzle ORM schema and migrations
    └── ... (other portal configuration files)
```

## Program Positioning

| Category | Description |
| :--- | :--- |
| **Delivery Model** | Cohort-based psychoeducational instruction |
| **Session Length** | 75 minutes per session, including anchor, hook, mechanism, and mirror segments |
| **Target Populations** | Veterans, justice-involved adults, recovery populations, and transitional-support participants |
| **Instructional Style** | **Kali Reaper Tone:** Analytical, unsentimental, high-velocity systems language |
| **Deployment Use** | Facilitator-led training environments requiring consistent delivery and clear participant safeguards |

## Key Documents

| Document | Link |
| :--- | :--- |
| **Master Summary (All Sessions)** | [Open Summary](./SUMMARY.md) |
| **Stepping Stones Pilot Addendum** | [Open Addendum](./pilots/Stepping_Stones_Pilot_Addendum.md) |
| **WRH Program Description (Federal)** | [Open Description](./legal/WRH_Program_Description_Federal.md) |
| **Safety & Participation Rules** | [Open Rules](./checklists/Safety_and_Participation_Rules.md) |
| **Facilitator Readiness Checklist** | [Open Checklist](./checklists/Facilitator_Readiness_Checklist.md) |
| **WRH Glossary** | [Open Glossary](./manual/WRH_Glossary.md) |
| **Plan B Wallet Card** | [Open Asset](./assets/Plan_B_Wallet_Card.md) |
| **Capability Statement** | [Open Capability Statement](./legal/Capability_Statement.md) |

## License

MIT License

## GitHub Topics

`capitol-contracts`, `sdvosb`, `trauma-psychoeducation`, `cptsd`, `wrh`, `veterans`, `executive-function`, `pilot-program`
