## Project Overview
A compact SQL-driven analysis of an Instagram‑style dataset that uncovers user behavior, content performance, and suspicious activity. The project uses MySQL to answer business questions such as who the most loyal users are, which accounts are inactive, which posts and hashtags perform best, and which accounts may be bots.

## Objectives
- Primary goal: Turn raw platform data into actionable insights for marketing, product, and investor decisions.
- Specific aims: identify oldest/most loyal users; find users who never posted; surface top posts and hashtags; determine best days for campaigns; estimate average posts per user; flag likely bot accounts.

## Key Findings
- Loyal users: Identified the five earliest registered accounts for targeted loyalty programs.
- Inactive users: 26 users had never posted; good candidates for onboarding campaigns.
- Top content: Located the single most‑liked photo and its owner for contest or feature opportunities.
- Hashtags: Top hashtags (e.g., smile, beach, party) that can inform creative and ad targeting.
- Ad timing: Most signups occurred on Thursday and Sunday — useful for scheduling promotions.
- Engagement metric: Average posts per user ≈ 2.57, a baseline for measuring future growth.
- Bot detection: Several accounts liked every photo and were flagged for manual review.

## Business Impact and Next Steps
- Immediate actions: run targeted re‑engagement emails for inactive users; feature high‑engagement creators; test ad campaigns on high‑signup days.
- Data hygiene: review and remove or quarantine flagged bot accounts to improve metric accuracy.
- Extensions: add cohort retention analysis, time‑series trends, follower network analysis, and automated dashboards for ongoing monitoring.
- Reproducibility: include schema.sql, seed_sample_data.sql, and individual query files in the repo so stakeholders can reproduce and extend the work.




