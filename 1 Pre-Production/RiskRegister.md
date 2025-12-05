# Risk Register – 90-Day VNRPG
**Project:** GRASP  
**Last updated:** 12/5/2025
**Owner:** Kaleb Sabo

| ID | Risk Description | Likelihood (1–5) | Impact (1–5) | Score | Mitigation Plan | Status / Notes | Owner | Early Warning Sign
|----|------------------|------------------|--------------|-------|-----------------|---------------|-------|-------------------
| R01 | Scope creep (adding new endings, locations, mechanics) | 4 | 5 | 20 | Freeze features at end of pre-production (Day 18). Any new idea goes into “Post-Release” backlog. | Active | You | New feature requests after Day 18
| R02 | Underestimating writing time – dialogue takes 2–3× longer than expected | 5 | 4 | 20 | Write 1 full scene now as benchmark. Allocate 35 % of total time to writing. | Active | You | <10 scenes finished by Day 40
| R03 | Burnout / life events (holidays, illness, job) | 3 | 5 | 15 | Build 1-week buffer into schedule. Work max 5 days/week. Daily cap 6 hrs. | Active | You | Missing 3+ consecutive days
| R04 | Art bottleneck (custom sprites/backgrounds take too long) | 4 | 4 | 16 | Day 14 decision: 80 % free/paid assets + 20 % custom, OR full custom with strict limit (5 backgrounds, 4 characters). | Active | You | No final art by Day 60
| R05 | Choosing wrong engine mid-project (e.g. start in Ren’Py, switch to Godot) | 2 | 5 | 10 | Final engine decision by Day 15. No switch allowed after Day 20. | Active | You | “Maybe X engine is better” discussions
| R06 | Audio copyright strikes or missing SFX/Music | 3 | 4 | 12 | Use only CC0 or purchased assets with proof of license saved in repo. | Active | You | Last-minute scramble for music
| R07 | Git/repo chaos (lost work, broken builds) | 2 | 4 | 8 | Commit daily, push to GitHub every night. Use clear branch names. Keep builds folder ignored. | Active | You | “Where did my script go?”
| R08 | No players/feedback – release into void | 3 | 3 | 9 | Post weekly devlogs on Twitter/Reddit/itch from Day 10. Build tiny community early. | Monitoring | You | Zero wishlists 2 weeks before release
| R09 | Computer/hardware failure | 1 | 5 | 5 | Daily backup to GitHub + external drive/Google Drive. Keep project <2 GB. | Active | You | Laptop dies
| R10 | Demotivation / loss of passion halfway | 3 | 5 | 15 | Celebrate every milestone publicly. Keep a “wins” log. Remember: done > perfect. | Active | You | “This sucks” mood >3 days

### Risk Scoring
- 15+ = Critical – must solve now
- 10–14 = High – active mitigation
- 5–9 = Medium – monitor
- <5 = Low

### How to use this file
1. Review & update every Friday (5-minute task).
2. When a risk turns red, stop everything and execute the mitigation.
3. Once a risk is fully solved or no longer relevant, mark Status → Resolved.

