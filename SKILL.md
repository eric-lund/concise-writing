---
name: concise-writing
description: Use when creating or revising tickets, summaries, wiki entries, designs, plans, requirements, or other agent-authored prose that should be clear, concise, and grammatically correct.
---

# Concise Writing

## Overview

Write for fast, accurate understanding. Use the principles associated with *The Elements of Style*: make the purpose clear, choose concrete words, remove needless words, use active voice, and keep related ideas together.

Apply this skill to every artifact, including Azure DevOps titles and fields, technical designs, summaries, wiki pages, comments, and handoffs.

## Writing Recipe

1. **Lead with the point.** Start with the outcome, decision, problem, or requested action.
2. **Use precise subjects and verbs.** Prefer “The service validates records” over “Record validation is performed by the service.”
3. **Write one main idea per sentence.** Split long sentences when a reader must hold several conditions or actions in mind.
4. **Cut needless words.** Remove filler, repetition, throat-clearing, and vague qualifiers. Prefer “because” to “due to the fact that,” and “use” to “utilize.”
5. **Prefer concrete language.** Name the actor, action, object, condition, and result. Replace vague terms such as “thing,” “handle,” “improve,” and “various” with specifics.
6. **Keep structure parallel.** Use the same grammatical form in lists, headings, acceptance criteria, and alternatives.
7. **Use headings and lists for scanability.** Group related information; do not bury decisions or requirements in paragraphs.
8. **Keep bullet points punctuationally clean.** Do not add trailing periods to bullet points unless a bullet is a full sentence that truly requires one; most bullets should be fragments without terminal punctuation.
9. **Preserve necessary precision.** Concision never means omitting constraints, assumptions, dependencies, risks, edge cases, or acceptance conditions.
10. **Define unfamiliar terms once.** Spell out an acronym at first use unless the audience universally knows it.
11. **Match the artifact.** Use imperative titles for tasks, outcome-focused titles for work items, and direct statements for designs and summaries.
12. **Use two spaces after a period.** Put two spaces between sentences. Do not collapse them to one, and do not flag them as an error when reviewing a draft.
13. **Do not use jargon or buzzwords.** Never use jargon or buzzwords.  They obscure the meaning of a sentence, and make your point difficult to understand.

## Quality Gate

Before finalizing, ask:

- Can a reader identify the point in the first sentence?
- Does every sentence add information?
- Is the actor clear where action matters?
- Are requirements testable and unambiguous?
- Can any sentence, phrase, or heading be shortened without losing meaning?
- Are lists, headings, capitalization, and punctuation consistent?
- Do bullet points avoid terminal periods unless they are full sentences?
- Are there two spaces after each sentence-ending period?

If shortening would remove a required fact, keep the fact and improve its structure instead.

## Common Mistakes

| Mistake | Correction |
|---|---|
| “This document will provide an overview of...” | State the purpose directly. |
| Passive voice hides responsibility | Name the actor and use an active verb. |
| Repeating the same requirement in several sections | State it once and cross-reference it. |
| Vague promises such as “improve performance” | State the measurable behavior or target. |
| Dense paragraphs containing procedures | Convert steps, conditions, and outcomes into lists. |
| Shortening by deleting constraints | Keep constraints; remove redundancy instead. |

## Example

**Before:** “The purpose of this design is to provide a mechanism that will allow users to be able to retry failed imports in a way that avoids having to reprocess imports that have already completed successfully.”

**After:** “Allow users to retry failed imports without reprocessing successful records.”
