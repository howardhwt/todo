# Todo & Pipeline Tracker

GitHub repo: `howardhwt/todo`

## Workflow

- "Add todo" / "add task" = create a GitHub issue on this repo
- "Add prospect" / outreach = create issue with full outreach template (see below)
- Always add issues to the appropriate project board

## Project Boards

- **Pilot Pipeline** (project 1) — active customer tasks
- **Outreach Pipeline** (project 2) — prospect tracking

## Labels

### Customer labels (`customer:*`)
Pilot customers: coffeelabs, univr.se, facemeet, openart, sekai
Create new `customer:` labels as needed for new prospects.

### Stage labels (`stage:*`) — outreach pipeline
prospecting → outreach → demo-scheduled → evaluating → negotiating → closed-won / closed-lost

### Source labels (`source:*`)
linkedin, cold-email, referral, inbound, event

### Category labels
onboarding, follow-up, blocker, renewal, internal, urgent

## Outreach Issue Template

When creating prospect/outreach issues, **require all these fields** (ask if missing):

```
**Contact:** Name, Role
**Company:** Name, ~size employees, brief description
**Email:** address (note if needs verification)
**Use case:** 1-line what they'd use Viggle for

**Outreach sent:** YYYY-MM-DD
- Channels used (email, LinkedIn, etc.)

**Follow-up cadence:**
- Day 3-4: LinkedIn message if accepted, otherwise wait
- Day 7: Follow-up email with new value (demo clip, case study)
- Day 14: Final touch / breakup email

**Next step:** Immediate next action
```

**Required labels for outreach:** one `customer:*`, one `source:*`, one `stage:*`
**Default stage:** `stage:prospecting` unless outreach already sent (then `stage:outreach`)

## Regular Task Issues

For non-outreach todos, just need a title and relevant `customer:` label. No template required.
