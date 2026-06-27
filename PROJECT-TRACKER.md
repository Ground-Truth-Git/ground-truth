# GroundTruth - Project Tracker

## Status
v2.0 live. Plain-language rewrite is now the primary site. Technical version preserved for academic review. Model validation underway before public launch.

## Architecture decision (v2.0)
SINGLE public version, plain language. NOT multiple audience versions - rejected because there's no guarantee a reader lands on the "right" version, and a single shared language carries a single message. The highest-common-denominator plain version serves everyone: 15yo, layman, exec, and the curious. The technical version exists ONLY as a back-end reference for academic/methodological reviewers (e.g. Snowden-type readers who prefer the native methodological language).

## Files
- `index.html` - PRIMARY plain-language site (v2.0)
- `technical.html` - full methodological version, for academic review only, linked discreetly in footer
- `stress-test-brief.docx` - critique request to send to expert reviewers
- `netlify.toml` - redirect config
- `LINKEDIN-POST.md` - draft, holds until model validated + URL confirmed

## v2.0 site structure (plain language)
1. Hero - "Stop being fooled by claims that sound true"
2. Stakes strip - the "second darkness" / democracy framing
3. The five questions - THE method, leads the page
4. Ten warning signs - plain-named (was "failure modes")
5. Kinds of proof - the ladder (was "warrant hierarchy")
6. How sure should you be - five confidence bands, plain
7. The mirror rule
8. Worked example - vendor 40% claim, runs the 5 questions
9. AI tool - plain-language prompt

## Jargon translation applied
- "evidentiary framework" -> "how to check if a claim is true"
- "warrant" -> "what kind of proof is this"
- "provenance" -> "where does it come from"
- "independence" -> "do sources really agree or just repeat"
- "credence/confidence bands" -> "how sure should you be"
- "interested party" -> "someone who gains if you believe it"
- "rival hypotheses" -> "what else could explain this"
- "assembly" -> "what's being left out"
- All academic names (Bayesian, Kent, Snowden, ICD 203) removed from public site, retained in technical.html

## CRITICAL - model validation before launch (issue #20)
Josh is sending the framework to expert reviewers. Known soft spots:
- Five confidence bands are anchored, not derived. May need to retreat to qualitative categories.
- Calibration untestable for unique past events.
- Weakest-link principle stated as law - needs conditions.
- Independence is a continuum treated as a binary checklist.
Reviewers: statistics professor (confirmed) + targets: philosopher of science, misinformation researcher, forecaster, political opponent (symmetry test).
DO NOT finalise public launch until feedback is in and language is adjusted accordingly.

## Open issues
- #12 - origin/why section (needs Josh's framing)
- #20 - model validation (in progress, blocks launch)

## Closed this session
- #11 five-questions position (now leads)
- #19 hero headline (reframed to active)
- Plus v2.0 rewrite addresses the jargon-wall, buried-tool, and missing-stakes findings from the 5-persona review

## Standing rules
- Plain hyphens only, no em dashes
- No Wikipedia sourcing
- No connection to theMap
- Single public version, plain language
- Proactively critique public moves before Josh acts
- Model must not overclaim its own certainty - self-refuting for a misinformation tool
