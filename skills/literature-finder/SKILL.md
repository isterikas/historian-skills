---
name: literature-finder
description: Finds and verifies scholarly articles, chapters, and books for a research topic and returns an annotated bibliography. Use for academic literature discovery, especially historical and humanities topics involving multiple publication languages, historical terminology, or regional scholarship.
---

# Literature Finder

## Intake

Ask these three questions in order, one per turn. Wait for each answer before asking the next. If the user has already supplied a value, include it in the corresponding question for confirmation. Translate the questions, choices, explanatory messages, and result labels into the language of the conversation. Preserve original publication titles.

1. “What topic are you researching? Please describe it in as much detail as possible, including the historical period, geographical area, and specific aspects you are interested in.”
2. “Which languages should the publications be written in? You can select multiple languages, for example, English, German, Polish, or Lithuanian.”
3. “How extensively would you like me to search?” Offer **Quick** for a focused search, **Balanced (recommended)** for wider coverage and selective citation exploration, and **Deep** for broader multilingual and regional coverage plus citation chaining.

After the third answer, begin automatically. Ask another question only if a critical ambiguity prevents a meaningful search.

## Research

1. Read [Search methodology](references/search-methodology.md) and [Source registry](references/source-registry.md). Identify the original concept, period, geography, relevant historical entities and disciplines. Search the core concept first. Use scholarly synonyms, historical names, variant spellings, translations and transliterations where useful. Keep adjacent topics separate. Treat the historical period and the date of publication independently.
2. Use the selected depth to budget initial and expanded queries, targeted database searches, regional discovery, verification and citation exploration. Start with suitable international indexes, then make targeted international queries where they add coverage. Always follow with a dedicated national or regional pass, including in Quick mode and when ten candidates are already available. If direct regional search is inaccessible, try a permitted regional catalog, repository or domain-scoped web search. Record what actually ran.
3. Use any useful search language. Include only publications verified to be written in a language the user selected. Mark uncertain-language candidates as unverified and keep them outside the verified bibliography. Filter on the language of the work itself, including the specific chapter or edition being cited. Verify records to the same standard at every depth and deduplicate before spending effort on repeated hits.
4. Rank direct relevance first and label contextual items with the specific mismatch. Return up to ten verified, unique publications by default. If asked for more, extend discovery for additional unique results. A smaller verified bibliography is appropriate when evidence is sparse.

## Deliver

Read [Output format and verification](references/output-format.md). Use reliable bibliographic records, preserve original titles and link to verified DOIs or stable records. Write three-sentence summaries only from an actual abstract or sufficient publication content. End with **Search Methodology** describing searches actually run, verification and coverage gaps.

Use available, permitted search and retrieval tools. If search is unavailable, say so and report the limitation in the methodology. Verify any user-supplied records to the extent that evidence permits. Never invent publications, citations, links, abstract content or search activity, or bypass access controls.

For maintainer validation, see [Test cases](references/test-cases.md).
