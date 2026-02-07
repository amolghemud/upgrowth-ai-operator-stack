# Funnel Diagnostics

## What problem this replaces
The "we need more traffic" reflex. Teams throw budget at top-of-funnel when the real leak is mid-funnel drop-off, poor lead qualification, or broken handoff between marketing and sales. Without structured funnel analysis, optimization is guesswork.

## When NOT to use this
- When you have fewer than 100 monthly conversions (insufficient data for pattern detection)
- When the funnel hasn't been stable for at least 30 days
- When you're launching a net-new product with no historical data
- When the problem is clearly isolated to one known stage

## Inputs required
- Funnel definition (stages from first touch to conversion/revenue)
- Conversion data per stage (last 30/60/90 days)
- Traffic sources breakdown
- Key landing pages and their conversion rates
- Lead scoring criteria (if applicable)
- Sales cycle length
- Known friction points or recent changes
- Revenue per conversion or customer LTV (for impact sizing)

## Outputs expected
- **Funnel visualization**: Stage-by-stage conversion rates with benchmarks
- **Leak identification**: Where the biggest drop-offs occur, quantified by volume and revenue impact
- **Root cause hypotheses**: Why each leak exists, with supporting evidence
- **Segment analysis**: How different traffic sources, audiences, or entry points perform through the funnel
- **Quick wins**: Fixes that can be implemented in under a week with measurable impact
- **Structural recommendations**: Longer-term changes to funnel architecture
- **Testing roadmap**: Prioritized A/B test recommendations for each identified leak
- **Revenue impact projection**: Estimated revenue lift from fixing top 3 leaks

## How we use this at upGrowth
We run this before increasing any paid spend, and as a monthly health check for active campaigns.

The golden rule: never scale a leaky funnel.

Typical triggers:
1. Client says "we need more leads" — we run diagnostics first
2. Conversion rates drop without obvious cause
3. Before budget allocation decisions
4. After major landing page or offer changes

Output feeds directly into Campaign Planner for execution prioritization.

## Failure modes
- Optimizing micro-conversions that don't connect to revenue
- Treating funnel stages as independent instead of interconnected
- Ignoring qualitative signals (user feedback, sales team input, session recordings)
- Recommending changes without statistical significance considerations
- Assuming the funnel definition itself is correct — sometimes the stages are wrong

## Claude Co-work implementation

Recommended setup:
- Create a custom skill named "Funnel Diagnostics"
- Use this spec as the system instruction
- Require quantified impact for every recommendation
- Force revenue connection — no recommendation without estimated dollar impact
- Output in structured sections with visual-friendly data (tables, not paragraphs)
- Require confidence levels on hypotheses (high/medium/low with reasoning)

This plugin is designed to be human-governed. Funnel optimization involves cross-team coordination — the diagnostic provides the shared evidence base for decision-making.
