# Content Brief Generator

## What problem this replaces
Vague content assignments that lead to off-strategy articles, wasted writer hours, and content that ranks for nothing and converts no one. Most briefs are either a keyword and a word count, or a 15-tab research session that never gets documented.

## When NOT to use this
- When you need a quick social post or caption
- When the content format is purely creative (brand film, moodboard)
- When you already have a validated brief from a subject-matter expert
- When the topic has no search intent or distribution strategy behind it

## Inputs required
- Target keyword or topic cluster
- Content goal (rank, convert, educate, link-build)
- Target audience segment
- Funnel stage (awareness, consideration, decision)
- Competitor URLs (optional, up to 3)
- Brand voice guidelines (optional, or reference Brand Voice Calibrator output)

## Outputs expected
- Working title and angle recommendation
- Search intent classification (informational, navigational, transactional, commercial)
- Target structure (H2/H3 outline with recommended sections)
- Key questions to answer (sourced from People Also Ask, forums, related searches)
- Competitor content gap analysis (what existing top results miss)
- Internal linking opportunities
- CTA recommendation tied to funnel stage
- Word count range with justification
- Source and citation requirements

## How we use this at upGrowth
We run this plugin before assigning any long-form content to writers or editors. It sits between the SEO Audit Mapper (which identifies what to write) and the actual content production workflow.

Typical flow:
1. SEO Audit Mapper identifies content opportunities
2. Content Brief Generator produces the brief
3. Writer executes against the brief
4. Editor reviews against brief requirements

This eliminates the back-and-forth cycle of "this isn't what we meant" revisions.

## Failure modes
- Generating briefs that are keyword-stuffed outlines instead of strategic documents
- Ignoring search intent and defaulting to "informational" for everything
- Producing generic structures that could apply to any topic
- Missing the competitive angle — what makes this piece worth publishing
- Over-specifying tone when brand voice hasn't been calibrated

## Claude Co-work implementation

Recommended setup:
- Create a custom skill named "Content Brief Generator"
- Use this spec as the system instruction
- Require search intent classification before outline generation
- Force competitor gap analysis in every brief
- Output in structured markdown sections with clear writer instructions

This plugin is designed to be human-governed. The brief is a starting point — the editor finalizes before handoff.
