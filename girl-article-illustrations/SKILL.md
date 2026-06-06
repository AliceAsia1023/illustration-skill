---
name: girl-article-illustrations
description: Generate white-background hand-drawn article illustrations with a twin-tail girl as the core operator for Chinese articles, blog posts, notes, and concept explanations. Use when the user wants shot lists, prompts, or final illustrations for editorial content rather than posters, mascots, or cute children-style art.
---

# Girl Article Illustrations

Use this skill to turn one idea from a Chinese article or note into a single 16:9 hand-drawn editorial illustration.

This is not a generic character illustration skill. The output should explain a judgment, process, state, comparison, risk, or metaphor from the source material. The recurring role is a twin-tail girl who actively performs the core action in the visual.

By default, this skill should prefer article-body illustrations over posters. When the user provides a full article, first break it into 3 to 5 visual anchors, then produce a shot list, then write final prompts, and generate the images if requested.

## When To Use

Use this skill when the user wants any of the following:

- A shot list for article illustrations
- A prompt for one editorial illustration
- A consistent white-background hand-drawn visual language
- The recurring character replaced with a twin-tail girl
- A full set of matched illustrations for one article

Do not use this skill for:

- Posters or cover KV
- Cute mascot art
- Children book illustration
- Polished anime character portraits
- PPT infographics or formal flowcharts

## Workflow

1. Read the article, paragraph, note, or concept.
2. If it is a full article, extract 3 to 5 visualizable anchors: judgment, structure, process, state, metaphor, or contrast.
3. Choose one structure pattern per image from `references/composition-patterns.md`.
4. Make the twin-tail girl perform the key action. If removing her would leave the image unchanged, the concept is under-specified.
5. Write a shot list first when the article has multiple paragraphs.
6. Write generation prompts using `references/prompt-template.md`.
7. If the user asks to generate images, keep the whole set visually matched: same doodle language, same line weight, same girl scale, similar whitespace density, and similar annotation density.
8. Validate against `references/qa-checklist.md` before delivering.

## Core Output Rules

- Output is a 16:9 horizontal editorial illustration.
- Pure white background only.
- Black hand-drawn linework with restrained red, orange, and blue handwritten Chinese notes.
- Large whitespace. The subject should usually occupy about 40% to 60% of the frame.
- One image explains one core idea only.
- The twin-tail girl must participate in the action, not stand aside as decoration.

## References

- Read `references/style-dna.md` for non-negotiable visual constraints.
- Read `references/girl-ip.md` for character behavior and design rules.
- Read `references/composition-patterns.md` when choosing scene structure.
- Read `references/prompt-template.md` when drafting a prompt.
- Read `references/series-lock.md` when generating multiple illustrations for the same article.
- Read `references/qa-checklist.md` before final delivery.
