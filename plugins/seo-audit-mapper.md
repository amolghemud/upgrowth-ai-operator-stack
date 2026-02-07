# SEO Audit Mapper

## What problem this replaces
SEO audits that are either a 200-page automated crawl dump nobody reads, or a surface-level checklist that misses structural issues. Marketing teams need actionable SEO intelligence, not a list of 4,000 missing alt tags.

## When NOT to use this
- When you need a full technical crawl (use Screaming Frog or Sitebulb for that)
- When the site has fewer than 10 pages
- When SEO is not a relevant acquisition channel for the business
- When you need real-time rank tracking data

## Inputs required
- Website URL
- Primary business goal (leads, sales, signups, traffic)
- Target audience and geography
- Top 5-10 target keywords or topic clusters
- Known SEO history (migrations, penalties, major changes)
- Access to Google Search Console data (recommended, not required)
- Access to Google Analytics data (recommended, not required)

## Outputs expected
- **Technical health summary**: Core Web Vitals assessment, indexation issues, crawlability concerns, structured data status
- **Content audit**: Thin content pages, cannibalization risks, content gap opportunities, top performing pages
- **Keyword landscape**: Current ranking positions, keyword clustering, intent mapping, difficulty assessment
- **Backlink profile summary**: Domain authority context, toxic link risks, link gap vs competitors
- **Information architecture review**: URL structure, internal linking health, orphan pages, navigation depth
- **Prioritized action plan**: Issues ranked by impact and effort, grouped into quick wins, medium-term fixes, and strategic initiatives
- **Opportunity sizing**: Estimated traffic potential for top recommended actions

## How we use this at upGrowth
This is the diagnostic plugin — it runs before any SEO or content strategy work begins. Think of it as the MRI before the treatment plan.

Typical flow:
1. SEO Audit Mapper diagnoses the current state
2. Research Mapper validates market opportunities
3. Content Brief Generator produces briefs for identified gaps
4. Campaign Planner sequences the execution

We re-run this quarterly for active clients and after any major site change.

## Failure modes
- Treating all issues as equal priority (a missing H1 is not the same as a canonicalization disaster)
- Focusing on vanity metrics instead of revenue-connected keywords
- Recommending fixes without sizing the opportunity
- Missing the business context — technical perfection on pages that don't matter
- Generating recommendations without considering implementation capacity

## Claude Co-work implementation

Recommended setup:
- Create a custom skill named "SEO Audit Mapper"
- Use this spec as the system instruction
- Require prioritization framework (impact vs effort) in every output
- Force business goal connection for each recommendation
- Output in structured sections with severity ratings (critical, high, medium, low)
- Require evidence or data references — no gut-feel recommendations

This plugin is designed to be human-governed. SEO strategy requires domain expertise to weigh trade-offs — the audit provides the structured evidence.
