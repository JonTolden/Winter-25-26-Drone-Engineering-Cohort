# CSULB Drone Engineering Cohort Testbed

## Overview
This repository supports a small cohort of California State University, Long Beach (CSULB) Electrical Engineering undergraduates as they develop an unmanned aircraft system (UAS) testbed. The testbed is a hands-on platform for practicing PCB design, power system architecture, radio frequency (RF) design, and the fundamental engineering principles required to build robust aerial systems.

## Program Goals
- **Experiential Learning:** Provide students with an end-to-end hardware development experience that mirrors professional aerospace and defense workflows.
- **Systems Thinking:** Encourage interdisciplinary collaboration across firmware, electronic design automation (eCAD), mechanical CAD (mCAD), and test disciplines.
- **Rapid Iteration:** Promote iterative prototyping, data-driven validation, and design reviews that improve reliability with every hardware revision.
- **Documentation Excellence:** Establish thorough documentation and knowledge transfer practices that future cohorts can extend.

## Repository Structure
The repository is organized around major subsystems of the UAS testbed:

- `Firmware/` – Embedded software for flight controllers, RF subsystems, and remote interfaces.
- `eCAD_Flight_Controller/` – Schematics, layouts, and manufacturing files for the flight control PCB.
- `eCAD_Power_System_Architecture/` – Power distribution, regulation, and protection circuitry design artifacts.
- `eCAD_RF_Transceivers/` – RF board designs supporting telemetry, command, and payload data links.
- `eCAD_Remote_Controller/` – Hardware design files for the operator control unit.
- `mCAD/` – Mechanical models for airframe integration, mounting hardware, and environmental protection.
- `Other/` and `Primary Documents/` – Shared references, meeting notes, planning documents, and cohort resources.
- `test/` – Verification utilities, simulations, and hardware bring-up procedures.

## Getting Started
1. **Clone the repository** and review the relevant subsystem folders for your assignment.
2. **Set up toolchains** (KiCad, Altium, SolidWorks, MATLAB/Simulink, embedded toolchains, etc.) as required by your project lead.
3. **Review cohort documentation** in `Primary Documents/` for program guidelines, design standards, and safety checklists.
4. **Coordinate with mentors** to define deliverables, review schedules, and hardware access requirements.

## Contribution Workflow
- Branch from `main` with a descriptive name (e.g., `fc-power-stage-revA`).
- Document design intent, simulation results, and testing outcomes within the appropriate subsystem folder.
- Use version control for both native design files and exported manufacturing outputs when possible.
- Submit pull requests that summarize design changes, include validation data, and reference issue tracker items.
- Request peer and mentor reviews before merging to ensure compliance with program standards.

## Engineering Practices
- **Design Reviews:** Schedule formal reviews at major milestones (schematic completion, layout freeze, firmware release) and capture action items in repository documentation.
- **Testing & Validation:** Develop verification plans early, execute lab tests with proper instrumentation, and upload logs, plots, and photos to the relevant subsystem directories.
- **Safety & Compliance:** Follow CSULB laboratory policies, ensure power systems are fused and monitored, and observe RF emissions regulations.
- **Configuration Management:** Maintain clear versioning for PCB revisions, BOM updates, and firmware releases to support traceability across cohorts.

## Support & Communication
- Use the cohort's designated communication channels (e.g., Slack, Teams, email) for daily coordination.
- Log meeting notes, design decisions, and action items within `Primary Documents/` to preserve institutional knowledge.
- Reach out to faculty advisors and industry mentors for guidance on complex design challenges.

## Acknowledgements
This initiative is made possible by the dedication of CSULB Electrical Engineering faculty, mentors, and students who collaborate to advance unmanned aircraft system capabilities while providing meaningful experiential learning opportunities.
