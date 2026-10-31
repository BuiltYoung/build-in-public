# Build in Public

A Claude skill from Built Young that helps any founder or business owner plan, write and run build-in-public content: sharing the real story of building their business while it happens.

- Works across industries (B2B SaaS, consumer apps, e-commerce, local businesses, service businesses, creators) and stages, from idea to growth
- Gets to know the company in 3 to 5 questions, then gives a short profile the user pastes back next session to pick up where they left off
- Turns raw notes, metrics and customer feedback into ready-to-post drafts for X, LinkedIn, Instagram, TikTok, 小红书 (RED), Threads and Reddit, plus messages for Discord, WeChat and WhatsApp groups
- Plans content calendars, community engagement, launch warm-up and launch day, and reviews post performance
- Three sharing levels: process only, some metrics, or full openness including revenue
- Honesty guardrails: never invents numbers, quotes or customers; flags consent and competitively sensitive details; bans marketing clichés in English and Chinese
- Replies and writes in the user's language

## Install in Claude
1. Download this repo as a ZIP. GitHub names the folder `build-in-public-main`, so rename it to `build-in-public`; the folder name must match the skill name. Re-zip the folder.
2. In claude.ai, go to Customize → Skills → + → Create skill → Upload a skill, and upload the ZIP.

## Try it
- "I run a small pottery studio and want to start posting on Instagram. Where do I start?"
- "Here's what happened this week: [your notes]. Turn it into posts for LinkedIn and X."
- "We launch on the 3rd of next month. Plan the four weeks before and launch day."
- "我开了一家面包店，想在小红书上记录创业过程，这个月该发什么？"
- In later sessions, paste your saved profile first.

## Layout
| Path | What it holds |
|---|---|
| `SKILL.md` | Instructions Claude follows: workflow, writing principles, sharing levels, honesty checks, self-review checklist |
| `references/onboarding.md` | First-use questions, defaults, and a short explainer for people new to build in public |
| `references/voice-and-banned-phrases.md` | Matching the founder's voice; banned clichés in English and Chinese |
| `references/content-pillars.md` | Six content pillars and how to find stories in raw material |
| `references/content-calendar.md` | Cadence, pillar mix by stage, repurposing across platforms |
| `references/platforms.md` | Format, length, tone, hashtags and cadence for each platform |
| `references/by-stage-and-industry.md` | Strategy by stage and by industry |
| `references/examples.md` | Weak vs. strong post pairs across platforms and industries |
| `references/community-playbook.md` | Comment prompts, polls, replies, involving early users, running a group |
| `references/launch-playbook.md` | Warm-up, launch day and the two weeks after |
| `references/performance-review.md` | Reading post numbers and deciding what to change |
| `templates/company-profile.md` | The profile users save and paste back |

Every company, person and number in the examples is fictional. Platform limits were checked in October 2026; platforms change them often.
