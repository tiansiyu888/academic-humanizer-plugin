---
name: academic-humanizer
description: Edit academic papers, theses, rebuttals, and grant proposals for clear, evidence-bound prose while preserving every number, result, equation, and citation. Remove generic AI writing patterns, calibrate claims to evidence, preserve legitimate scholarly hedging, and match an author's prior voice or target venue when provided.
---

# Academic Humanizer

Improve the clarity and voice of AI-assisted *academic* writing while keeping the precise,
evidence-bound voice that scholarship requires and matching the author's own style. It preserves every
number, result, and citation, and it is not a tool for evading AI-use disclosure.

## When to use
Editing or reviewing academic prose: paper sections, abstracts, rebuttals, related work, and **funding
proposals** (NSF Project Summary/Description, NIH Specific Aims, fellowship and foundation proposals;
see Layer 6). **Not** for blogs, marketing, or personal essays, and **never** inject opinion, humor, or
first-person "personality" into a manuscript. For technical writing, neutral and precise *is* the human
voice. One caveat for proposals: their register is different from a paper's, since they are sold on
vision and feasibility, so the ambition language a paper would trim is appropriate there; apply Layer 6,
not the paper layers' stricter trimming, to vision statements.

## Core principle
Academic writing already has a correct human voice: neutral, precise, third-person plural ("we"), every
claim tied to its evidence. The job is to (1) strip the AI *tells* without casualizing, and (2) enforce
the discipline a general humanizer misses: **every claim earns its number, figure, or citation, and no
verb is stronger than its evidence.**

## Process
1. **Read** the manuscript and any author writing sample; note the document type (paper vs. funding
   proposal) and the target venue or funding agency. For proposals, also apply Layer 6 and preserve
   appropriate vision.
2. **Audit** (do not edit yet): list each detected pattern with its location and proposed fix, and each
   empirical claim's evidence status.
3. **Rewrite**: same structure and content, all claims and citations preserved, tells removed, over-claims
   matched to evidence, legitimate hedging kept.
4. **Report**: cleaned text plus a short change log (patterns removed, claims softened or given evidence
   pointers, voice notes). Cover everything the original covered: if it had five paragraphs, so does the
   rewrite.

---

## Layer 1: General AI-tell catalog
Scan for and fix the general patterns, subject to the academic exceptions in Layer 3:
inflated significance ("marking a pivotal moment"); superficial "-ing" tails that fake depth
("..., highlighting..."); promotional/figurative language ("rich", "vibrant", "groundbreaking");
vague attributions ("experts argue" with no cite); AI vocabulary (*delve, underscore, intricate,
tapestry, testament, landscape (abstract), pivotal, showcase, foster, leverage (filler), realm,
seamless*); copula avoidance ("serves as" -> "is"); negative parallelisms ("not just X, but Y");
rule-of-three padding; elegant variation (cycling synonyms for one referent); filler
("it is worth noting that", "in order to"); **overlong, clause-stacked sentences (split them; see 2.11)**;
and **em-dashes (remove entirely; recast with commas, colons, parentheses, or separate sentences)**.

## Layer 2: Academic AI tells (remove or fix)

### 2.1 Over-claiming verbs
Empirical work *shows* and *provides evidence*; it does not *prove* or *demonstrate* universal truths.
Watch for demonstrate, prove, establish, confirm, guarantee, or "significantly" without a test or number.

### 2.2 Significance hype
Remove empty significance language such as "paves the way for", "crucial/pivotal step", "revolutionize",
"opens new avenues", "sheds light on", "paramount importance", and "bridges the gap" unless evidence justifies it.

### 2.3 Empty intensifiers
Replace vague terms such as extensive, comprehensive, thorough, numerous, various, and "a wide range of"
with concrete counts or scope when available.

### 2.4 Novelty padding
Avoid repeated "novel", unsupported "to the best of our knowledge", and unsupported "for the first time".

### 2.5 Formulaic openers
Rewrite stock openings such as "In recent years...", "With the rapid development of...", and generic
"Despite recent advances..." so the paragraph starts from the actual problem or evidence.

### 2.6 Connective overuse
Do not start consecutive sentences with Moreover, Furthermore, Additionally, or In particular when the
logic is already clear.

### 2.7 Contribution-list cliches
Each contribution should name a specific method, result, benchmark, or resource rather than restating the abstract.

### 2.8 Citation dumping
Prefer citations that explain why a cited work matters rather than unexplained long citation clusters.

### 2.9 Hedging-by-vagueness
Quantify or cut vague hedges such as somewhat, relatively, fairly, to some extent, and quite.

### 2.10 Boilerplate emphasis
Remove boilerplate emphasis such as "It is worth noting that", "It should be emphasized that", "Notably",
and "Importantly" when the sentence itself already shows importance.

### 2.11 Overlong, clause-stacked sentences
Split long sentences that chain several subordinate clauses; keep one main idea per sentence when possible.

---

## Layer 3: Preserve these (do NOT over-correct)
- Keep evidence-tied hedging such as "suggests", "is consistent with", "we hypothesize that", "may indicate",
  and "appears to" when uncertainty is real.
- Passive voice is acceptable when the actor is irrelevant.
- First-person plural "we" is standard academic usage.
- Formal definitions, named methods, metrics, technical terms, equations, and symbols stay verbatim.
- **Never invent, drop, or alter a number, equation, result, or citation.** Preserve every cite key.

---

## Layer 4: Claim-evidence discipline
For every empirical claim, check whether it is backed by a number, figure, table, or citation and whether
the verb matches the strength of that evidence. If support is absent, add the available evidence pointer or
soften the claim. Prefer attributed ranges over vague magnitude words when data are available.

---

## Layer 5: Voice and venue matching
If the author supplies prior papers, read a sample first and note sentence rhythm, connective habits,
hedging, section openings, notation, and recurring phrasing. Match the target venue's register as well.
Absent a sample, default to clean, precise, venue-appropriate prose.

## Layer 6: Funding-proposal mode (NSF, NIH)
A proposal is not a paper. Preserve appropriate ambition but match every major claim to feasibility.
For NSF, retain clear Overview, Intellectual Merit, and Broader Impacts structure. For NIH R01, prioritize
the Specific Aims page: problem, gap, long-term goal, central hypothesis, objective, 2–3 aims, and payoff.
Keep aims independently valuable where possible and do not invent preliminary data, funding, collaborators,
partners, or letters.

## Output
Return the cleaned text plus a short change report: patterns removed, claims softened or given evidence
pointers, and any voice/venue notes. Confirm that no number, equation, result, or citation was altered.
