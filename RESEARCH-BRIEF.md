# Research Brief: Existing Frameworks for Claim Evaluation and Misinformation Resistance

## Purpose

Before launching GroundTruth publicly, establish what already exists in this space. This protects against three risks:

1. **Reinvention** - building something that materially duplicates an established, better-resourced tool, which undermines the "why does this exist" question on launch.
2. **Credibility exposure** - a reviewer or critic asking "how is this different from [well-known framework]?" and the author having no crisp answer.
3. **Missed improvement** - existing frameworks may contain components (calibration methods, source taxonomies, teaching approaches) worth borrowing or adapting, especially relevant given the open questions about the confidence bands.

The goal is NOT to confirm GroundTruth is original. It is to find the strongest existing work and honestly locate GroundTruth relative to it - including the possibility that something already does this better.

## Core research question

**What existing frameworks, methods, tools, or curricula help a non-specialist evaluate whether a claim is true or well-supported - and how does each compare to GroundTruth on scope, method, audience, and rigour?**

## What GroundTruth actually is (the thing we are comparing against)

So researchers can assess "does this already exist," here is the precise shape of GroundTruth:

- A **topic-neutral** method for evaluating any factual claim (not domain-specific to health, politics, climate, etc.)
- Aimed at **non-specialists** (general public, executives, students) - not professional analysts or academics
- Combines several components into one system:
  - A **ranked hierarchy of evidence types** (re-testable > physical > contemporaneous record > inference > testimony > expert summary > assertion)
  - A **provenance discipline** (trace claims to origin; repetition is not evidence)
  - An **independence test** (sources only count as separate if they differ on origin, method, data, institution, motive)
  - A **five-band confidence scale** (Established / Probable / Contested / Doubtful / Refuted) anchored to intelligence-community and legal standards
  - A **symmetry rule** ("mirror rule" - apply the same standard regardless of which conclusion a source supports)
  - **Ten named failure modes** (citation laundering, single-origin amplification, etc.)
  - An **AI prompt tool** that operationalises the whole method
- Delivered as a **free public website** plus a **portable AI prompt**

## Categories to investigate

Research should cover these distinct domains. Each likely has its own established frameworks.

### 1. Information / media literacy frameworks
- SIFT (Stop, Investigate, Find better coverage, Trace claims) - Mike Caulfield
- Lateral reading (Stanford History Education Group / Wineburg)
- CRAAP test (Currency, Relevance, Authority, Accuracy, Purpose)
- News Literacy Project resources
- IFLA infographic / "How to Spot Fake News"
- UNESCO media and information literacy curriculum
- Key question: how do these compare on rigour and on producing a confidence judgment vs just a checklist?

### 2. Evidence-grading systems (professional / academic)
- GRADE (medical evidence grading)
- Cochrane / systematic review hierarchies
- Oxford Centre for Evidence-Based Medicine levels of evidence
- Intelligence community standards (ICD 203, Sherman Kent estimative probability, Heuer's ACH)
- Key question: GroundTruth borrows from these - are there others it should know, and do any target non-specialists?

### 3. Fact-checking methodologies
- IFCN (International Fact-Checking Network) code of principles
- ClaimReview / schema.org structured fact-check markup
- Methodologies published by Snopes, PolitiFact, Full Fact, FactCheck.org
- Full Fact's automated fact-checking tools
- Key question: do any expose a reusable *method* for the public, or are they internal editorial processes?

### 4. Reasoning / critical thinking frameworks
- Argument mapping (Rationale, Kialo)
- Bayesian reasoning popularisations (e.g. for forecasting)
- The "Calling Bullshit" course (Bergstrom & West, University of Washington)
- Street Epistemology
- Carl Sagan's "Baloney Detection Kit"
- Key question: which target laypeople, and which produce an actionable verdict vs teaching disposition?

### 5. Forecasting / calibration frameworks
- Superforecasting / Good Judgment Project (Tetlock)
- Metaculus, calibration training tools
- Brier scoring and calibration methods
- Key question: directly relevant to the open question about whether GroundTruth's bands should be probabilistic - what do serious forecasters actually do?

### 6. AI-powered claim-checking tools (most direct competitors)
- Existing GPT/Claude prompts and custom GPTs for fact-checking
- Browser extensions (NewsGuard, etc.)
- Automated verification tools (Full Fact AI, Google Fact Check Explorer)
- Any "paste a claim, get a verdict" AI tools
- Key question: this is the closest analogue to GroundTruth's tool - what already exists and how good is it?

### 7. Source-reliability rating systems
- NewsGuard
- Media Bias/Fact Check
- Ad Fontes Media (Media Bias Chart)
- Wikipedia's perennial sources list
- Key question: these rate *sources*; GroundTruth rates *claims and the evidence under them* - confirm that distinction holds.

## For each framework found, capture:

- **Name and origin** (who built it, when, institutional backing)
- **What it does** (the actual method, briefly)
- **Audience** (specialist or general public?)
- **Output** (a checklist? a disposition? a verdict? a confidence level?)
- **Scope** (topic-neutral or domain-specific?)
- **Strengths** (what it does well that GroundTruth may not)
- **Limitations** (gaps GroundTruth might fill)
- **Reach / adoption** (widely used, taught in schools, niche?)
- **Overlap with GroundTruth** (high / partial / low - on which components)

## The synthesis we need at the end

1. **A comparison table** - GroundTruth vs the most relevant frameworks across the dimensions above.
2. **The honest positioning answer** - in one paragraph: what, if anything, does GroundTruth do that the existing landscape does not? Candidate differentiators to test (do not assume true):
   - Combining evidence-grading rigour (usually professional-only) with a public, plain-language delivery
   - Producing a *confidence verdict* rather than a literacy *checklist*
   - The symmetry/mirror rule as an explicit operating principle
   - The portable AI prompt as the delivery mechanism
   - Topic-neutrality across all domains in one tool
3. **The uncomfortable finding, if it exists** - if something already does this well, say so plainly. Better to learn it now.
4. **Borrowable components** - anything from the existing landscape that would strengthen GroundTruth, especially on the confidence-band question.

## Out of scope

- Academic epistemology literature for its own sake (only insofar as it produced a usable framework)
- Platform content-moderation systems (different problem)
- Deep dives on misinformation *causes* or *psychology* (we want evaluation methods, not why people believe falsehoods)

## Method note

Desktop research: web search and authoritative sources (academic pages, the frameworks' own sites, reputable overviews). Apply GroundTruth's own standard to the research itself - trace claims about what a framework does to primary sources (the framework's own documentation), not to third-party blog summaries. Note where adoption/reach claims are weakly sourced.

## Deliverable

A written research report with the comparison table, the positioning answer, and a short prioritised list of borrowable components and credibility risks. Length: comprehensive but skimmable - findings first, detail beneath.
EOF
echo "Brief written"