# Codex implementation task

Implement the AI Skills productivity environment within this repo subdirectory.

## Steps
1. Inspect operating system, Git state, Python, Git, Node.js (require >=22.20.0), npm and Codex capabilities. Inspect licenses, scripts, SKILL.md and supply-chain/security risks for every source in skills.json. Record upstream commit SHA.
2. Core: install find-skills, skill-creator, frontend-design, planning-with-files using project-local `npx skills add SOURCE --skill NAME -a codex --copy -y`, if reviewed and supported.
3. Optional: after risk review and authorization, install agent-browser, baoyu-xhs-images, last30days. Check browser/CLI dependencies, image backend, optional API keys without recording secrets.
4. Superpowers: separately assess and install through supported Codex plugin UI/mechanism if accessible. If not, report manual steps, not successful installation.
5. Verify project-local `.agents/skills/NAME/SKILL.md` files exist, then run four safe functional smoke tests: find a skill, draft a new skill, create demo HTML, and make a 3-step plan.
6. Record statuses per item (installed and tested, installed but dependency missing, blocked, failed), tool versions, evidence and errors in `INSTALL_REPORT.md`.
7. n8n, Make, NotebookLM, Claude Cowork, Cursor and Canva are separate products: write integration guidance, do not pretend they are Skills or install third-party accounts/services without permission.
8. Do not change any files outside this project. Never expose tokens or grant yourself elevated permissions.

**Done only when statuses are evidence-backed, tests have been run and outstanding manual work is clear.**
