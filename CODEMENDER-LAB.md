# CodeMender CI/CD Guardrail — Module 2 Lab

This repository is a hands-on lab: wire **Google CodeMender** into a CI/CD
pipeline as an autonomous security guardrail that scans, **blocks deployment on
HIGH/CRITICAL bugs**, and opens a **pull request that fixes them**. The target
app is **OWASP Juice Shop** (intentionally vulnerable).

➡️ **Students start here:** [`lab/README.md`](./lab/README.md)
➡️ **Instructors / graders:** [`lab/INSTRUCTOR.md`](./lab/INSTRUCTOR.md)
➡️ **Architecture & component flow:** [`lab/README.md#-architecture--component-flow`](./lab/README.md#-architecture--component-flow)

The pipeline lives at
[`.github/workflows/codemender-pipeline.yml`](./.github/workflows/codemender-pipeline.yml).
