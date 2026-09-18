---
name: human-writing-style
description: Draft, review, or polish English and Chinese prose in the user's natural voice, with simple words and concise sentences. Use for answers, emails, applications, reports, messages, and documents. For question and answer material, edit only the answers. Exclude code, quotations, raw data, faithful transcription, and agent instructions.
---

# Human Writing Style

Write like the user explaining something in their own words. For English, aim for the natural, straightforward voice of a capable writer who is not a native speaker. Use the user's drafts and latest edits as the voice reference. Default to American English unless the source or request establishes another locale.

## Scope

Follow the user's requested tone and format. Infer the audience and purpose from context; ask only when a missing detail prevents a reliable result. The domain skill controls substantive work.

In question and answer material, leave questions, prompts, and instructions unchanged; edit only the answers. In files, edit the requested prose while preserving code blocks, frontmatter, formulas, data, link targets, and required structure.

Match the requested level of editing:

- **Proofread:** fix language errors while preserving wording and structure.
- **Polish:** simplify awkward wording and keep sentences that already work.
- **Draft or rewrite:** organize the supplied ideas around the main point.
- **Review only:** identify concrete problems and remedies without rewriting the whole text.

## Meaning

Use supplied or verified details. Keep the author's position and actual contribution; do not invent experiences, motives, evidence, or commitments to make the writing persuasive. Flag a material information gap briefly instead of filling it in or silently deleting the claim.

Preserve names, quantities, units, dates, comparisons, negation, conditions, requests, and attribution. Keep citations beside the claims they support and quotations verbatim. Polishing a claim does not verify it.

Keep the strength and status of each claim: estimates stay estimates, association stays association, planned work stays planned, and possibility stays uncertain. These distinctions take priority over shorter wording.

## Voice

Use familiar words, direct verbs, and simple sentences. Prefer wording the user could comfortably say aloud. Keep grammar correct and use ordinary contractions where natural.

Make the actor and referents clear. Keep modifiers beside what they describe. Use active voice when the actor is known and relevant; retain passive voice when the process or result is the point. Connect ideas through their actual relationship.

Say it once. If one clear sentence is enough, use one. Split a sentence when it carries too many ideas; cut repeated explanations, ceremonial openings, and closing summaries that add nothing.

Avoid phrases set off by a comma on each side. Rewrite them as a full sentence or a clear clause. Avoid hyphens and dash marks in finished prose. Use them only when grammar requires them and a clear rewrite is not possible.

Lead with the answer. Add only the reasoning or example needed to understand it. Use short paragraphs; use lists when they make the content easier to follow.

Retain necessary technical terms and use the same name for the same concept. Explain unfamiliar terms briefly when needed. Match the occasion's courtesy and formality with plain wording.

State the point directly. Include a caveat only when it changes the meaning or the reader's action, and state it once. Remove preemptive defenses, imagined objections, and repeated assurances.

## Sentence patterns

- Avoid the **rule of three** as a rhetorical device: three adjectives, near synonyms, or parallel clauses added for rhythm. Keep the concrete point and remove decorative items. Preserve each distinct fact in a necessary list.
- Avoid repeated parallel sentences and matching paragraph structures. Let each sentence follow the idea instead of repeating the same opening or building toward a slogan. Choose the number of points from the content; do not default to three.
- State the claim directly instead of manufacturing a contrast such as `not just X, but Y` or `不是 X，而是 Y`. Use a contrast when the source actually makes that distinction.
- Replace staged questions such as `The result?` and `这意味着什么？` with the answer. Remove generic openings and closing sentences that only restate or inflate the point.
- Replace decorative ranges such as `from X to Y` with the actual relationship. Use ordinary verbs instead of phrases such as `serves as a testament to` or `充分彰显了`.
- Remove unsupported significance attached through `highlighting...`, `demonstrating...`, or `这充分说明……`. Keep a substantive inference visible for clarification rather than turning it into a fact.

Change the underlying structure rather than swapping a flagged phrase for a synonym. For drafting, polishing, or style review, read the output language's [English guide](references/patterns-en.md) or [Chinese guide](references/patterns-zh.md); read both for mixed prose.

## Finish

Compare the result with the source, then check the whole answer against the Voice and Sentence patterns sections. Restore any lost meaning and check for repeated patterns across paragraphs. Stop when the requested problem is resolved; natural text can remain unchanged. Judge quality by meaning and spoken ease, not detector scores or forced slang.

Return the requested text or review. Keep checks and editing commentary outside the artifact; include alternatives or change explanations only when asked. Label a working draft if an essential gap remains.

For a genre-specific choice, read the relevant section of [genre profiles](references/genre-profiles.md). For skill maintenance, consult [source notes](references/sources.md), including the version comparison. When shortening this skill, merge duplicate wording while retaining distinct requirements unless the user changes them.
