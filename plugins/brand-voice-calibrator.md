# Brand Voice Calibrator

## What problem this replaces
Inconsistent brand communication across channels, teams, and campaigns. One person writes formal whitepapers, another writes casual tweets, a third writes generic ad copy — and none of it sounds like the same brand. Style guides exist but nobody reads them. The result is a brand that feels fragmented and forgettable.

## When NOT to use this
- When the brand is pre-product with no existing content to analyze
- When you need a full brand strategy (positioning, identity, visual system)
- When the output is for a one-off ghostwritten piece that won't recur
- When the brand voice is already well-documented and consistently applied

## Inputs required
- Brand name and one-line description
- 5-10 samples of existing content that represent the brand at its best (blog posts, emails, social posts, ad copy, landing pages)
- Target audience description
- Brand values or principles (if documented)
- Competitor brands to differentiate from (optional)
- Channels where the voice will be applied
- Any existing style guide or voice documentation (optional)

## Outputs expected
- **Voice profile**: 3-5 defining voice attributes with descriptions and spectrum positioning (e.g. "Authoritative but not academic — we teach through clarity, not complexity")
- **Tone matrix**: How voice adapts across contexts — blog vs email vs social vs ads vs support
- **Do/Don't guide**: Concrete examples of on-brand vs off-brand phrasing
- **Vocabulary guide**: Preferred terms, banned words, jargon policy
- **Sentence and structure patterns**: Characteristic rhythms, length preferences, formatting tendencies
- **Channel-specific guidelines**: How the voice flexes for each platform without losing coherence
- **Brand voice scorecard**: Criteria for evaluating whether content is on-voice
- **Before/After examples**: Real content samples rewritten to demonstrate the calibrated voice

## How we use this at upGrowth
We run this at client onboarding and revisit annually or after major brand pivots.

The output becomes the reference document for:
- Content Brief Generator (voice section of briefs)
- Campaign Planner (messaging framework alignment)
- Any writer, designer, or team member producing brand content
- AI-assisted content generation (as system instructions for voice consistency)

Without this, every piece of content is a coin flip on whether it sounds like the brand.

## Failure modes
- Producing generic voice guidelines that could describe any brand ("We're professional yet approachable")
- Over-indexing on aspirational voice instead of analyzing actual voice
- Creating guidelines too rigid for cross-channel adaptation
- Ignoring audience expectations in favor of internal brand preferences
- Generating a voice document that's too long for anyone to actually use

## Claude Co-work implementation

Recommended setup:
- Create a custom skill named "Brand Voice Calibrator"
- Use this spec as the system instruction
- Require analysis of provided content samples before generating guidelines
- Force specificity — reject generic descriptors without concrete examples
- Output in structured sections with practical reference format
- Include the scorecard as a usable checklist, not a paragraph

This plugin is designed to be human-governed. Brand voice is subjective and strategic — the calibrator provides the structured framework, but leadership makes the final call on what sounds right.
