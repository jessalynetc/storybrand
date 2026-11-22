# Personal StoryBrand Builder

An AI agent skill that helps professionals build an evidence-backed personal brand using the 7-part StoryBrand structure. The hiring audience is the hero, and you are the guide.

It turns scattered career material (resumes, case studies, recommendations, self-reflection, target job descriptions) into:

- An **evidence ledger** that separates what is verified from what is self-reported, projected or conflicting
- **Strength patterns** found across your projects
- **Audience research** from the job descriptions you actually want
- A **BrandScript** built one approved stage at a time
- **Ready-to-use copy:** portfolio hero, LinkedIn, resume summary, interview intros
- **Tailored pitch kits** for specific roles
- **Per-application workspaces and pitch decks** for top-priority roles, built from the same approved claims

The brand keeps evolving. Each new project, metric or recommendation goes through a simple update protocol, so approved decisions are never silently overwritten.

## Why it's different
- **Honest by design.** Every claim carries an evidence label. Projections are never shown as results.
- **Contradiction checks.** It compares numbers, dates and ownership across all your materials, including applications you've already sent.
- **Market-tested positioning.** It counts what your target JDs actually ask for and maps that to your strengths.
- **Your voice.** It learns how you write and keeps it.
- **Missing evidence never blocks progress.**

## Structure
```
personal-storybrand-builder/
├── SKILL.md                      # The workflow (phases 0–9)
├── references/
│   ├── storybrand-framework.md   # The 7 elements, adapted for personal brands
│   ├── evidence-rules.md         # Labels, contradiction checks, calibrated wording
│   ├── stage-guide.md            # What each stage delivers
│   ├── clarity-audit.md          # 12-point editorial audit
│   ├── voice-and-copy.md         # Voice rules and channel specs
│   └── iteration-protocol.md     # How the brand evolves with new material
└── templates/
    ├── 00-strengths-intake.md
    ├── 00-jd-intake.md
    ├── knowledge-base-files.md   # Skeletons for files 01–10
    ├── 11-job-pitch-kit.md
    └── application-repo/         # Per-application workspace + 10-slide deck outline (Tier A roles)
```

## How to use
1. Add the folder to your agent's skills directory (for example `~/.claude/skills/` for Claude Code), or upload it as a skill in Claude.
2. Start with: *"Help me build my personal StoryBrand."*
3. Share your materials and 5 to 10 target job descriptions.
4. Approve each stage as you go. Ask for applications or a role-specific pitch when ready.

## Credit
The 7-part structure comes from Donald Miller's *Building a StoryBrand*. This skill summarizes the ideas in its own words and adapts them for personal career branding. It is not affiliated with StoryBrand.
