# Campaign Planner

## What problem this replaces
Campaigns planned in silos — paid team does their thing, content team does theirs, email runs independently. The result is fragmented messaging, wasted budget on overlapping efforts, and no coherent customer journey across channels. Campaign planning shouldn't be a calendar of disconnected activities.

## When NOT to use this
- When running a single-channel tactical push (just an email blast, just one ad)
- When the campaign objective hasn't been defined yet (define the goal first)
- When you don't have budget or resource constraints to plan around
- When the campaign is purely brand/awareness with no measurable KPIs

## Inputs required
- Campaign objective (specific, measurable: e.g. "Generate 200 SQLs in Q2")
- Target audience segments (with detail on pain points and buying stage)
- Available channels (paid search, paid social, email, content, organic social, partnerships, etc.)
- Budget range and constraints
- Timeline and key dates (launch, milestones, deadlines)
- Existing assets (landing pages, content, email lists, creative)
- Competitor activity context (optional, or reference Competitor Teardown output)
- Funnel data (optional, or reference Funnel Diagnostics output)

## Outputs expected
- **Campaign architecture**: How channels work together, not independently
- **Audience journey map**: What each segment experiences across touchpoints
- **Channel strategy**: Role of each channel, budget allocation rationale, expected contribution
- **Messaging framework**: Core message, channel-specific adaptations, proof points per stage
- **Content requirements**: What needs to be created, repurposed, or updated
- **Timeline and milestones**: Phased rollout with dependencies mapped
- **Budget allocation**: Spend distribution with rationale tied to expected ROI
- **KPI framework**: Leading and lagging indicators per channel and overall
- **Risk register**: What could go wrong and contingency plans
- **Measurement plan**: How success will be tracked, attribution approach, reporting cadence

## How we use this at upGrowth
This is the execution blueprint. Nothing ships without a campaign plan.

We build campaign plans after the diagnostic plugins have run:
1. Research Mapper provides market context
2. Competitor Teardown identifies positioning opportunities
3. Funnel Diagnostics reveals where to focus
4. Campaign Planner turns insights into a coordinated execution plan

We review plans weekly during active campaigns and adjust based on performance data.

## Failure modes
- Planning channels independently instead of as an integrated system
- Optimizing for vanity metrics (impressions, clicks) instead of business outcomes
- Ignoring resource constraints and creating plans that can't be executed
- Front-loading all activity without a sustain phase
- Missing the feedback loop — plans without built-in checkpoints and adjustment triggers
- Assuming last-touch attribution tells the full story

## Claude Co-work implementation

Recommended setup:
- Create a custom skill named "Campaign Planner"
- Use this spec as the system instruction
- Require channel interdependency mapping — no channel exists in isolation
- Force budget justification tied to expected outcomes
- Output in structured sections with timeline visualization
- Require measurement plan with attribution model recommendation

This plugin is designed to be human-governed. Campaign execution requires real-time judgment calls — the plan provides the strategic framework and guardrails.
