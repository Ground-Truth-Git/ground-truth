# GroundTruth: Landscape Research Report
## Prior Art, Comparable Frameworks, and Positioning Analysis

**Prepared:** June 2026
**Status:** For review before public launch

---

## Executive Summary

This report covers 20+ frameworks across seven categories. The honest finding: GroundTruth is not unique in any single component. Every element - evidence hierarchies, confidence scales, named failure modes, AI-assisted fact-checking - exists somewhere. What does not appear to exist is a single, topic-neutral, public tool that integrates all of these into a coherent portable system with a confidence verdict, anchors it to established professional standards, and delivers it in plain language. That is a defensible positioning claim, but it is narrow, and the report identifies specific credibility risks and borrowable components that should be addressed before launch.

The most significant finding is the **Cynefin/systems-thinking angle** you raised. This is real, important, and currently absent from GroundTruth. It is the biggest gap in the framework.

---

## Category 1: Media and Information Literacy Frameworks

### SIFT (Caulfield, 2019)

SIFT is a Digital Literacy Framework created by Mike Caulfield to help students and researchers quickly evaluate the credibility of online information. The four moves are: Stop (pause before sharing), Investigate the source, Find better coverage, and Trace claims to their original context.

Lateral reading involves going outside of a source being evaluated and finding what others say about its reputation, rather than digging deep into the one source being evaluated.

**Audience:** Students, general public. Widely adopted in universities and libraries across the US.

**What it does well:** Extremely portable and teachable. The "T" in SIFT (Trace claims) is essentially GroundTruth's provenance step. CC BY 4.0 licensed - freely adaptable.

**What it does not do:** Produce a confidence verdict. It is a disposition and a checklist, not a rating system. It does not name specific techniques of manipulation beyond broad categories. No evidence hierarchy - it asks "is this source credible?" without defining what makes evidence credible in the first place.

**Overlap with GroundTruth:** High on provenance and source investigation. Low on evidence typing, confidence rating, and named failure modes.

**Credibility risk:** SIFT is the dominant framework in media literacy education. Any reviewer who knows it will ask "how is this different from SIFT?" You need a crisp answer: GroundTruth goes from source credibility to claim confidence - SIFT stops at the source.

---

### CRAAP Test (Blakeslee, California State University Chico, 2004)

The CRAAP Test refers to Currency, Relevance, Authority, Accuracy, and Purpose. It provides a structured approach to scrutinize sources using specific evaluative criteria.

**What it does well:** Simple, memorable, widely taught in academic settings.

**What it does not do:** Rate confidence. Distinguish evidence types. Name manipulation techniques. It is a source-quality checklist that produces a qualitative judgment, not a verdict.

**Overlap with GroundTruth:** Partial on "Authority" and "Purpose" (aligned with the interested-party concept), but CRAAP doesn't name or explain the failure modes that occur when these are abused.

**Status note:** The checklist approach is an efficient way of evaluating sources, but this efficiency encourages surface evaluation and ignores the actual claims made in the source. This is the critique that most separates GroundTruth from CRAAP-type frameworks - GroundTruth evaluates claims and the evidence chain beneath them, not just the surface of a source.

---

## Category 2: Professional Evidence-Grading Systems

### GRADE (Grading of Recommendations Assessment, Development and Evaluation, 2000)

The GRADE working group developed a common, sensible and transparent approach to grading quality (or certainty) of evidence and strength of recommendations.

The GRADE system sets four categories for rating quality of evidence: high, moderate, low and very low.

**What it does well:** The most rigorous and widely adopted evidence-rating system in existence for clinical and health research. Has been through decades of expert review. The four-band structure is directly analogous to GroundTruth's five bands.

**Key similarity:** GRADE and GroundTruth share the core architecture: rate the quality of evidence for each claim, then rate confidence in the conclusion. GRADE separates evidential quality from recommendation strength - GroundTruth collapses these into one band. Whether that simplification is justified is a question for your statistician reviewer.

**Critical difference:** GRADE is designed for systematic reviewers rating bodies of clinical trial evidence. It is not designed for a layperson evaluating a single claim. It requires expertise to apply. There is no portable public tool.

**Relevance for GroundTruth:** Your statistician will almost certainly ask why you did not build on GRADE rather than anchoring to intelligence doctrine. The honest answer: GRADE is domain-specific (health research), and its specific downgrading criteria (risk of bias, inconsistency, indirectness, imprecision, publication bias) are not topic-neutral. But the spirit is highly comparable and should be acknowledged.

---

### Intelligence Community Standards: Sherman Kent and ICD 203

In intelligence analysis, words of estimative probability (WEPs) are systematically applied to qualify judgments about the future course of events. Sherman Kent emphasized their role in bridging the gap between analytic uncertainty and executive decision-making.

ICD 203 encourages analysts to pair words of estimative probability with explanations of evidence and uncertainty rather than leave single-word labels to stand alone.

**Relevance:** GroundTruth borrows the probability anchor explicitly from this tradition. This is the strongest existing anchor for the confidence bands - it is validated by institutional practice over decades. The key limitation is the same as GRADE: designed for trained analysts, not laypeople. ICD 203 requires explicit uncertainty language paired with probability ranges - GroundTruth simplifies this into five bands. Whether that simplification is sound is a key question for expert review.

---

### Heuer's Analysis of Competing Hypotheses (ACH)

The Analysis of Competing Hypotheses is a structured analytic technique that allows you to identify all possible competing hypotheses, collect available evidence that supports or refutes these hypotheses, and then determine the most plausible hypothesis.

The intelligence community uses structured analytic techniques to help analysts think critically and avoid cognitive bias. ACH was designed to reduce confirmation bias.

**What it does:** Systematic rival hypothesis testing. For each piece of evidence, ask which hypothesis it best supports, and whether it discriminates between hypotheses at all. This is the most rigorous operationalisation of GroundTruth's "rival hypotheses" section.

**Critical finding:** ACH is the precursor to the rival hypotheses concept in GroundTruth - it is where that concept comes from. The non-discriminating evidence rule ("evidence fitting all rivals equally is non-discriminating") is explicit ACH doctrine. GroundTruth has adapted this for non-specialists, which is the right move, but it should be acknowledged as a source.

**Limitation found in research:** Fifty intelligence analysts were randomly assigned to use ACH or not - findings showed that analysts may resist applying its evidence integration rule and prefer to use a cognitively more complex strategy that weighs both consistent and inconsistent evidence for each hypothesis. This is a known limitation: ACH is theoretically sound but cognitively demanding. GroundTruth's plain-language translation addresses this.

---

## Category 3: Argument Structure and Logical Fallacy Frameworks

### Toulmin Model of Argumentation (Stephen Toulmin, 1958)

The Toulmin model shows how reasoning moves from evidence (grounds) to a conclusion (claim), supported by a warrant and strengthened by backing, qualifiers, and rebuttals.

Stephen Toulmin introduced this model because he felt formal logic did not reflect how people actually argue in real life. The model breaks arguments into six functional parts: claim, grounds, warrant, backing, qualifier, and rebuttal.

**Critical finding and significant overlap:** The Toulmin model's "warrant" - the bridge between evidence and claim - is conceptually identical to GroundTruth's "warrant hierarchy." Both are asking the same question: what entitles us to move from this evidence to this conclusion? Toulmin also distinguishes "grounds" (the data) from "backing" (further support for the warrant) and "qualifier" (the confidence level) - this maps closely onto GroundTruth's structure. Toulmin's "rebuttal" maps onto the rival hypotheses step.

**What Toulmin does not do:** Rate confidence with numeric anchors. Name manipulation techniques. Provide a portable tool. It is a framework for analysing the structure of arguments, not a tool for evaluating whether claims are true.

**Implication for GroundTruth:** The term "warrant" in GroundTruth's technical version comes from Toulmin. This should either be cited or avoided in the public version. The public version's translation ("what kind of proof is this?") sidesteps the issue.

---

### Logical Fallacy Taxonomies

The taxonomy of the fallacies is in dispute. Multiple names of fallacies are often grouped together under common names intended to bring out how the specific fallacies are similar.

There are many taxonomies - the Stanford Encyclopaedia of Philosophy lists over 200 named fallacies. Informal fallacies (the practically relevant ones) include cherry-picking, false equivalence, appeal to authority, straw man, Texas sharpshooter, appeal to ignorance, and false precision.

**Key finding:** GroundTruth's ten named failure modes overlap significantly with standard logical fallacy lists but are specifically selected and reframed around evidentiary contexts - the concern is not "is this argument valid?" but "is this evidence what it claims to be?" This is a meaningful distinction. Mandate creep, citation laundering, and single-origin amplification are not standard fallacy names - they are GroundTruth-specific descriptions of evidentiary failure modes that don't have standard names in the fallacy literature.

**Credibility opportunity:** The fact that GroundTruth's failure modes are precisely defined around evidence manipulation (rather than logical structure) and have consistent, memorable names is a genuine differentiator. The named-failure-mode approach also maps well onto the inoculation literature (see Category 6 below).

---

## Category 4: Critical Thinking for General Audiences

### Carl Sagan's Baloney Detection Kit (The Demon-Haunted World, 1996)

Sagan presents a set of tools for skeptical thinking that he calls the "baloney detection kit." Skeptical thinking consists both of constructing a reasoned argument and recognizing a fallacious or fraudulent one. Tools include independent confirmation of facts, development of different hypotheses, quantification, use of Occam's razor, and the possibility of falsification.

Like all tools, the baloney detection kit can be misused, applied out of context, or even employed as a rote alternative to thinking. But applied judiciously, it can make all the difference in the world - not least in evaluating our own arguments before we present them to others.

**What it does well:** The intellectual ancestor of this entire space. Independent confirmation, rival hypotheses, falsifiability - Sagan had all of these in 1996. Written in accessible, vivid prose. Has the famous closing disclaimer that no tool is immune to misuse.

**What it does not do:** Produce a confidence verdict. Name specific evidentiary manipulation techniques. Provide a portable structured tool. Rate sources by type. Sagan's kit is a disposition and a set of principles, not a step-by-step method.

**Overlap with GroundTruth:** High on philosophy, low on operational method. GroundTruth is what you get if you try to make the Baloney Detection Kit into a repeatable procedure.

---

### Calling Bullshit (Bergstrom and West, University of Washington, 2020)

The aim of this course is to help students navigate the bullshit-rich modern environment by identifying bullshit, seeing through it, and combating it. The authors define bullshit as the use of misleading evidence to persuade an audience.

Assessing the accuracy of a particular claim using basic logic, augmented where necessary with information that can be easily retrieved by an online search engine, is sufficient to call bullshit. Creating bullshit is easier and often simpler than speaking the truth.

**What it does well:** Excellent on data manipulation, visualisation deception, and statistical misrepresentation. Strong on selection bias, false precision, and "too good to be true" signals. Written for a general audience by credentialled academics. Widely read. Course materials publicly available.

**What it does not do:** Provide a structured step-by-step verdict system. Rate confidence. Name evidentiary failure modes in a systematic way. Build in a symmetry rule. The book is thematic rather than procedural.

**Critical overlap and differentiation:** Bergstrom and West focus heavily on data and statistics (FM-06, FM-07 territory in GroundTruth's terms). GroundTruth covers this but also covers source type, independence, provenance, and the symmetry rule - areas Calling Bullshit does not systematically address.

**Note:** This is the most credible comparable for GroundTruth's exec/professional audience and should be read by Josh before launch. Bergstrom and West are exactly the kind of names that would stress-test the framework rigorously.

---

### Street Epistemology (Boghossian, 2013; community, ongoing)

Boghossian writes that "the core of the dialogue is not changing beliefs, but changing the way people form beliefs." The goal is to encourage ourselves and others to examine the methods we use to judge the accuracy of truth claims.

Street Epistemology is a conversational approach designed to help people critically reflect on the quality of their reasoning and the reliability of the methods they use to support their deeply-held beliefs.

**Distinction from GroundTruth:** Street Epistemology is a conversational method for helping individuals examine their own belief-forming processes - it is interpersonal. GroundTruth is a claim-evaluation tool - it is analytical. Different jobs. Low overlap with GroundTruth in practice, though the epistemological foundations are related.

---

## Category 5: Forecasting, Calibration, and Probabilistic Thinking

### Superforecasting / Good Judgment Project (Tetlock, Mellers, 2011-2015)

The quality of forecasting can be dramatically improved with the right discipline. It is not about guessing, but about calibration: knowing how much confidence to place in each forecast and constantly adjusting.

Superforecasters are impressively well-calibrated and their accuracy scores decrease when you round their predictions to the nearest 0.1. Bayesian reasoning is a natural next step once you are thinking and talking probabilities - superforecasters seem to do many small updates, with occasional big updates, just as Bayesianism would predict.

**Critical finding - directly relevant to the open confidence-band question:**

The Good Judgment Project is the most empirically rigorous calibration work available. It shows that with training, non-experts can produce reliably calibrated probability estimates - their 70% forecasts really do come true about 70% of the time. This is the strongest available evidence that numeric confidence ranges on claims are not just dressed-up adjectives, at least for forward-looking events with verifiable outcomes.

**The gap that matters for GroundTruth:** The GJP works on forward-looking forecasts with known resolution dates. GroundTruth applies confidence ranges to historical claims where "was this true?" cannot be retested in the same way. Your statistician will draw this distinction. The honest position is: the GJP validates the calibration *approach* but not the specific bands GroundTruth has chosen for non-forecasting contexts.

**Borrowable:** Superforecasters use explicit probability numbers (not just bands). They update frequently as new evidence arrives. They treat beliefs as hypotheses, not positions. All of this could be reflected in how GroundTruth describes its bands - making explicit that the band is a snapshot, not a permanent verdict, and that it should be updated when new evidence arrives.

---

## Category 6: Inoculation and Prebunking Research

### Bad News Game / Inoculation Theory (van der Linden, Cambridge, 2018-present)

The Bad News game is an online fake news game in which players learn about six common misinformation techniques. Playing Bad News significantly improves people's ability to spot misinformation techniques compared to a control group, and crucially, also increases their level of confidence in their own judgments.

In contrast to debunking, prebunking has gained prominence as a means to preemptively build resilience against anticipated exposure to misinformation. This approach is usually grounded in inoculation theory.

Technique-based inoculation targets the rhetorical and logical manipulation techniques that misinformation commonly employs. This variant is particularly relevant - building immunity against the underlying tactics of misinformation is a more durable strategy than targeting specific false claims.

**Critical finding - significant structural parallel to GroundTruth:**

The inoculation/prebunking literature has independently arrived at the same insight GroundTruth uses: naming the techniques of manipulation is more durable than correcting individual false claims. The Bad News game's six misinformation techniques (impersonation, emotion, polarisation, conspiracy, discrediting, trolling) are GroundTruth's failure modes by another name and a different selection.

**Key difference:** The inoculation approach is primarily studied as a psychological intervention - it asks "does knowing the techniques make people more resilient?" and tests this empirically. GroundTruth is an analytical tool - it asks "how do I apply these techniques to evaluate a specific claim?" The underlying insight is shared; the application is different.

**Relevance for credibility:** The inoculation research literature is the strongest academic support for the failure-modes approach. Van der Linden's work at Cambridge is exactly the kind of peer-reviewed backing that would strengthen GroundTruth's credibility when presenting the framework in professional or academic contexts.

---

## Category 7: AI-Powered and Source-Rating Tools

### NewsGuard

NewsGuard uses trained journalists to rate news websites based on nonpartisan, apolitical criteria. It fits into the AI tools ecosystem as a human-intelligence layer that helps both humans and AI models distinguish between credible reporting and deceptive content.

NewsGuard is a rating system for news and information websites with ratings from 0 to 100, based on whether they adhere to editorial and journalistic standards. As of 2024, NewsGuard rated more than 12,000 news sources.

**Key distinction:** NewsGuard rates *sources*, not *claims*. This is the core difference GroundTruth identified in the brief. A source can score 95/100 on NewsGuard and still contain a claim that is Doubtful by GroundTruth's standard (because it is sourced to an interested party without independent verification). The claim-level and source-level analyses are complementary, not substitutable.

---

### PolitiFact / FactCheck.org / Washington Post Fact Checker

PolitiFact's reporting process includes a review of what other fact-checkers have found previously, a thorough Google search, a search of online databases, consultation with a variety of experts, and a review of publications. They emphasise primary sources and original documentation and do not rely on what a campaign or elected official tells them.

PolitiFact's Truth-O-Meter has six ratings in decreasing truthfulness: True, Mostly True, Half True, Mostly False, False, and Pants on Fire. The burden of proof is on the person making the statement.

**Key differences from GroundTruth:**
- Editorial judgment by professional journalists, not a portable framework the public can apply
- Primarily political claims (US domestic)
- The methodology is an internal editorial process, not a public-facing step-by-step tool
- No explicit symmetry rule (though PolitiFact checks both parties)
- No distinction between warrant types (physical evidence vs. testimony vs. secondary synthesis)
- Verdict is a journalist's judgment, not derived from explicit criteria

**Structural overlap:** PolitiFact's six-point scale and GroundTruth's five-band scale are addressing the same problem - how to communicate a confidence verdict to a non-specialist audience. PolitiFact's scale is more politically legible ("Pants on Fire" is memorable); GroundTruth's scale is more conceptually rigorous.

---

### AI Prompt-Based Fact-Checkers (2025-2026)

The models got dramatically better at multi-step reasoning. They can search the web in real time, handle long documents without losing the thread, and chain together verification steps. The approach: extract every checkable claim, verify each one against multiple layers of evidence, assign a scored verdict, and produce a structured report with specific revision suggestions.

**Finding:** There is a proliferating market of AI fact-checking prompts and tools, primarily targeting professional use cases (legal citation verification, content marketing, journalism). These are optimised for factual accuracy checking ("is this date correct?") rather than for evidentiary quality assessment ("is the evidence for this claim independent, primary, and well-sourced?").

The GroundTruth AI prompt is distinctive in asking the right question: not "is this factually accurate?" but "is this well-evidenced?" These are different questions. A claim can be factually accurate and still rest on interested-party assertion with no independent verification. This distinction is not present in the commercial AI fact-checking tools surveyed.

---

## The Systems Thinking and Cynefin Angle

### Why this matters and what's currently missing

Your instinct to bring Cynefin into the analysis is correct and important. Here is why, and what it means for GroundTruth.

**The problem:** GroundTruth currently treats all claims as if they live in the same epistemic space - as if the same evidence standard that applies to "did this event happen?" also applies to "will this policy reduce inflation?" and "is this culture toxic?" It doesn't. And this is a structural gap that Snowden (and a careful Bayesian) would immediately identify.

**The Cynefin insight applied to claims:**

In the Cynefin framework, evidence-based practices are effective in the "complicated" domain, where tightly coupled governing constraints prevail and unknowns are known. Emergent practices are effective in the "complex" domain, with its loosely coupled enabling constraints and unknown unknowns.

Translated to GroundTruth's context:

- **Clear / Complicated domain claims** (did X happen? what did the document say? what is the measurement?) are exactly where GroundTruth's framework applies well. Cause and effect are knowable. Primary evidence exists or can exist. The framework's five bands map directly onto these.

- **Complex domain claims** (why did X happen? will Y cause Z? is this culture fair?) have cause and effect that are only visible in retrospect, and are emergent rather than deterministic. Evidence that "fits" a complex-domain claim does not confirm it the way physical evidence confirms an occurrence claim. GroundTruth's claim-type ceilings (causal claims capped at Probable) partially address this, but do not name the underlying reason - which is Cynefin's complex domain problem.

- **Chaotic domain claims** (novel situations where cause and effect are not yet knowable) cannot be meaningfully rated by GroundTruth at all. The right response is to say "this is too new to rate" - but GroundTruth has no mechanism for this.

**What the purposeful tree / soft systems methodology adds:**

Soft systems approaches (Checkland's SSM, Churchman's inquiring systems, and Snowden's narrative sense-making) add a different dimension: not just "where does this claim sit on an evidence scale?" but "within which system does this claim make sense, and for whose purpose?"

A claim like "the policy reduced inequality" looks like an evidence question. But it is embedded in a system: whose definition of inequality? Over what time horizon? Compared to what counterfactual? The claim cannot be evaluated without understanding the system it lives in. GroundTruth currently has no step for "contextualise the claim in its system before evaluating it."

**Concrete implication for the framework:**

Before the five-question test, there should arguably be a prior question: **"What kind of claim is this, and in what domain does it sit?"**

- If it is an ordered claim (something happened, a number was measured): apply the full framework.
- If it is a complex claim (a causal argument, a policy outcome, a cultural judgment): the framework still applies, but the ceiling is lower, the rival hypotheses step is more important, and the assembly check (is the evidence representative?) is critical.
- If it is a claim about an emergent or novel situation: state that explicitly, and reduce the framework to "here is what we know, here is what we don't, here is what evidence would help."

This is the biggest gap in GroundTruth relative to the Snowden/systems-thinking tradition.

---

## Comparison Table

| Framework | Audience | Produces verdict? | Topic-neutral? | Evidence hierarchy? | Symmetry rule? | Named failure modes? | AI tool? | Confidence bands? |
|---|---|---|---|---|---|---|---|---|
| SIFT | General public | No - disposition | Yes | No | No | No | No | No |
| CRAAP | Students | No - checklist | Yes | No | No | No | No | No |
| GRADE | Clinical experts | Yes (4 bands) | No - health only | Yes (study type) | No | No | No | No |
| ACH (Heuer) | Intel analysts | Yes (hypothesis ranking) | Yes | No | No | No | No | No |
| Sagan Baloney Kit | General public | No - principles | Yes | No | No | No | No | No |
| Calling Bullshit | General public / students | No - analytical | Yes | No | No | Partial | No | No |
| Superforecasting | Trained forecasters | Yes (probabilistic) | Yes | No | No | No | No | Yes (numeric) |
| Toulmin model | Academic / debate | No - argument structure | Yes | Partial | No | No | No | Partial (qualifier) |
| NewsGuard | General public | Yes (0-100 score) | Yes | No | No | No | No | No |
| PolitiFact | General public | Yes (6-point scale) | No - political | No | No | No | No | No |
| Bad News game | General public | No - training | Yes | No | No | Yes (6 techniques) | No | No |
| AI fact-checkers | Professional | Yes (accuracy) | Yes | No | No | No | Yes | No |
| Cynefin / SSM | Org leaders | No - domain classification | Yes | No | No | No | No | No |
| Logical fallacy lists | General / academic | No | Yes | No | No | Yes (many) | No | No |
| **GroundTruth** | **General public / exec** | **Yes (5 bands)** | **Yes** | **Yes (7 types)** | **Yes** | **Yes (10)** | **Yes** | **Yes** |

---

## Positioning Analysis

### The honest answer to "what does GroundTruth do that nothing else does?"

No single component of GroundTruth is unique. The components individually exist in stronger forms elsewhere:
- Evidence hierarchy: better formalised in GRADE for its domain
- Confidence bands: better calibrated in Superforecasting for forward-looking questions
- Rival hypotheses: more systematic in ACH
- Named failure modes: longer list in fallacy literature; better researched in inoculation work
- AI tool: many similar prompts exist for factual verification

**What appears genuinely absent from the existing landscape:**

1. A single topic-neutral tool that integrates all of the above into a coherent portable system, accessible to a non-specialist, that outputs a confidence verdict with an auditable trail.

2. A symmetry rule as a core governing principle (the mirror rule). This is not present in any of the surveyed frameworks. It is present implicitly in good journalism practice, but not as an explicit, stated, and self-applying rule.

3. The combination of evidence-grading rigour (from the professional tradition) with plain-language accessibility. GRADE requires expertise. Superforecasting requires training. GroundTruth is the public-facing version of both.

4. Self-application - the explicit commitment that the framework applies to its own claims. No other framework surveyed makes this explicit.

**What remains weakly supported:**

- The specific confidence band thresholds (anchored but not derived - this is the open question for expert review)
- The framework's applicability to complex-domain claims (the Cynefin gap)

---

## Priority Findings for GroundTruth

### 1. Things to acknowledge or cite

- Caulfield's SIFT for the "Trace claims" step (provenance) - direct conceptual ancestor
- Heuer's ACH for rival hypotheses - the method GroundTruth adapts for non-specialists
- Sherman Kent / ICD 203 for the confidence band anchoring - already in the technical version
- The Bad News / inoculation literature for the named-failure-modes approach - strongest academic backing

### 2. Things to borrow

- **From Superforecasting:** Make explicit that the band is a snapshot, not permanent, and should be updated as evidence changes. Superforecasters treat beliefs as hypotheses to be revised, not positions to be defended.
- **From GRADE:** Consider whether evidential weight (currently a separate callout) should be more prominent - GRADE gives it equal billing with the quality rating.
- **From the inoculation literature:** The research strongly supports the "name the technique" approach. The failure modes are not just a list - they are inoculation. This framing could be useful in the LinkedIn launch.

### 3. The Cynefin gap - highest priority addition

Add a domain classification step before the five questions. Something like:

**"What kind of problem is this claim about?"**
- An ordered claim (an event, a measurement, a document) - the full framework applies
- A complex claim (a causal argument, a policy outcome, a future forecast) - the framework applies but the confidence ceiling is lower and rival hypotheses are more critical
- An emergent or novel situation - state this explicitly; the framework gives you a starting point, not a verdict

This is a meaningful improvement to the framework's intellectual honesty and would directly address the Snowden objection.

### 4. What to say to the "how is this different from X?" questions

To SIFT: "SIFT asks whether a source is credible. GroundTruth asks whether the evidence beneath a claim is well-founded. You need SIFT to find the right sources; you need GroundTruth to know whether those sources actually establish the claim."

To GRADE: "GRADE is for systematic reviewers evaluating clinical trial evidence. GroundTruth applies the same rigour to any claim in any domain, for a non-specialist audience."

To Calling Bullshit: "Bergstrom and West are excellent on data manipulation. GroundTruth adds evidence typing, provenance tracing, independence testing, and the symmetry rule - and delivers it as a portable five-step tool anyone can use."

To PolitiFact: "PolitiFact is a journalistic editorial process. GroundTruth is a method anyone can apply themselves, to any claim in any domain, without relying on a specialist to do it for them."

---

## Recommendations Before Launch

**Must-do:**

1. Add the domain classification step (the Cynefin gap fix) - this is the most intellectually substantive improvement available
2. Resolve the confidence band question with expert review (issue #20) - the positioning claim depends partly on the bands being defensible
3. Add an explicit acknowledgment of Sagan, SIFT, and the inoculation literature somewhere accessible - not because it is legally required but because it builds credibility with anyone who knows the field

**Consider:**

4. Reach out to the Bad News / van der Linden group at Cambridge - the inoculation literature is the closest published academic work to GroundTruth's failure-modes approach, and an endorsement or acknowledgment from that community would be highly credible
5. Read Calling Bullshit before launch - Bergstrom and West are the most likely informed critics, and understanding their framing helps differentiate

**Do not do:**

6. Claim uniqueness on any single component - the components all have precedents
7. Claim the confidence bands are rigorously calibrated - they are anchored but not derived
