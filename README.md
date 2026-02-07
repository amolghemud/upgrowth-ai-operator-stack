# upgrowth-ai-operator-stack
Open-source AI operator workflows, plugins, and playbooks used by upGrowth to diagnose growth problems, make decisions, and execute with leverage.

## Why this exists
Most teams use AI for writing.
We use AI to think, decide, and execute.

This repository documents the AI operator systems, plugins, and playbooks we use at UpGrowth to diagnose growth problems and ship outcomes with leverage.

## Who this is for
- Founders
- CMOs
- Growth leaders
- Operators who care about systems, not hacks

## What's inside
- Curated AI plugin marketplaces
- Operator-grade plugins for marketing teams (research, SEO, content, campaigns, competitive intel, funnel optimization, brand)
- Playbooks used in real client work
- Principles behind how we deploy AI

## Plugin catalog

| Plugin | What it does |
|--------|-------------|
| [Research Mapper](plugins/research-mapper.md) | Structured, source-backed market and industry research |
| [Content Brief Generator](plugins/content-brief-generator.md) | Strategic content briefs with search intent, competitor gaps, and outlines |
| [Competitor Teardown](plugins/competitor-teardown.md) | Systematic competitive analysis with positioning and strategic recommendations |
| [SEO Audit Mapper](plugins/seo-audit-mapper.md) | Actionable SEO diagnostics with prioritized fixes and opportunity sizing |
| [Funnel Diagnostics](plugins/funnel-diagnostics.md) | Conversion funnel analysis to identify leaks and size revenue impact |
| [Campaign Planner](plugins/campaign-planner.md) | Integrated multi-channel campaign planning with measurement frameworks |
| [Brand Voice Calibrator](plugins/brand-voice-calibrator.md) | Brand voice analysis and guidelines for consistent communication |

### How these connect

```
Research Mapper ──→ Competitor Teardown ──→ Campaign Planner
       │                    │                      ↑
       ↓                    ↓                      │
SEO Audit Mapper ──→ Content Brief Generator       │
       │                    ↑                      │
       ↓                    │                      │
Funnel Diagnostics ─────────┴──────────────────────┘
                            ↑
                  Brand Voice Calibrator
```

Start with diagnostics (Research Mapper, SEO Audit, Funnel Diagnostics), then move to strategy (Competitor Teardown, Campaign Planner), then execute (Content Brief Generator with Brand Voice Calibrator).

## Repository structure
- /marketplaces – curated plugin marketplaces
- /plugins – operator-grade plugin definitions
- /playbooks – real workflows we run
- /principles.md – how we think about leverage

## Using these plugins in Claude

These plugins are specifications, not executable code.

To use them:
1. Open Claude → Co-work
2. Create a custom skill, command, or agent
3. Paste the plugin specification
4. Adapt inputs to your workflow

This repository defines the thinking layer.
Claude executes it.
