# Launch Checklist: [Feature Name]

**Launch date:** [Date]
**Launch type:** Soft launch / GA / Phased rollout
**Owner:** [Name]
**PRD:** [Link]

---

## Pre-launch (T-2 weeks)

### Product
- [ ] Final scope locked, no new requirements
- [ ] All P0/P1 bugs closed or accepted
- [ ] Analytics events instrumented and verified in staging
- [ ] Feature flag configured, default OFF
- [ ] Rollback plan documented

### Engineering
- [ ] Load tested at expected peak + 2x
- [ ] Monitoring and alerts in place
- [ ] On-call rotation aware
- [ ] DB migrations dry-run on staging
- [ ] Third-party dependencies notified if relevant

### Design / Content
- [ ] All copy reviewed and finalized
- [ ] Empty states, error states, loading states all designed
- [ ] Accessibility pass complete (keyboard nav, screen reader, contrast)

### GTM
- [ ] Positioning and messaging approved
- [ ] Launch comms drafted (blog, email, social, in-product)
- [ ] Sales / CS / Support enabled with talking points and FAQ
- [ ] Pricing changes (if any) reviewed by finance

## Launch day (T-0)

- [ ] Final smoke test on production
- [ ] Feature flag flipped on for target cohort
- [ ] Comms published
- [ ] Team available on Slack / war room
- [ ] First-hour metrics dashboard open

## Post-launch (T+1 day to T+2 weeks)

### Day 1
- [ ] Error rates within tolerance
- [ ] Support volume monitored
- [ ] User feedback channels watched

### Week 1
- [ ] Adoption metrics reviewed against forecast
- [ ] Support tickets triaged for emerging patterns
- [ ] Top 3 bugs from production prioritized

### Week 2 / launch retro
- [ ] Retro scheduled
- [ ] Success metrics measured against PRD targets
- [ ] Follow-up roadmap items captured

## Communication plan

| Audience | Channel | Message | Owner | Status |
|---|---|---|---|---|
| Internal | Slack #launches | | | |
| Existing users | Email | | | |
| Public | Blog + social | | | |
| Customers | In-product | | | |

## Rollback criteria

We roll back if:
- Error rate > [X]% for > [Y] minutes
- P0 user-facing bug with no quick fix
- Core metric regresses > [X]% within first 24h

Rollback owner: [Name]
Rollback procedure: [Link to runbook]
