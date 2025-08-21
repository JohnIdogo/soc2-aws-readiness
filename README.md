# SOC 2 Readiness Project — AWS Cloud

This repository documents a hands-on **SOC 2 Type II Readiness Project** implemented on AWS cloud services.  
The project demonstrates governance, risk, and compliance (GRC) practices across the **Security, Availability, and Confidentiality Trust Services Criteria** using AWS services: **EC2, S3, IAM, CloudTrail, KMS, VPC**.

## Project Phases
- **Phase 1 – Governance & Scope**
- **Phase 2 – Risk Assessment & Control Mapping**
- **Phase 3 – Policies & Control Design**
- **Phase 4 – Monitoring, Logging & Alerting**
- **Phase 5 – Testing & Audit Preparation**
- **Phase 6 – Final Reporting & Executive Briefing**

## How to use this repo
- Excel templates: [`/templates/SOC2_AWS_Readiness_Templates.xlsx`](templates/SOC2_AWS_Readiness_Templates.xlsx)
- Save evidence (screenshots/logs) in [`/templates/Evidence/`](templates/Evidence) under the right TSC folders.
- Each phase folder contains a `README.md` with step-by-step tasks, AWS console paths, and deliverable checklists.
- Final deliverables live under `/phase-6-final`.

## Git Workflow (suggested)
```bash
git init
git add .
git commit -m "chore: scaffold SOC2 AWS readiness repo"
git branch -M main
git remote add origin YOUR-GITHUB-REPO-URL
git push -u origin main

# Work by phases
git checkout -b phase-1
# ...do work...
git add . && git commit -m "feat(phase-1): add scope statement, shared responsibility, RACI"
git push -u origin phase-1
# open PR to main
```

## Deliverables
- Governance: Scope Summary, RACI, Shared Responsibility
- Risk & Controls: Risk Register, TSC Map, Control Register
- Policies: IAM, Encryption, Logging/Monitoring
- Evidence: CloudTrail, Config, GuardDuty, Alarms
- Testing: Test cases, Audit checklist
- Final: Readiness report & Executive deck

> Generated on 2025-08-21
