# Prompt Template

Use this as a base and replace the placeholders.

```text
Generate one 16:9 horizontal editorial illustration for the idea: "[core idea]".

Visual style:
pure white background, black fine hand-drawn linework, slight wobble, large whitespace, restrained red/orange/blue handwritten Chinese annotations, editorial sketch instead of poster art.

Character:
a hand-drawn twin-tail girl is the main operator in the scene. She is calm, focused, and restrained. She is not a mascot and not a decorative bystander.
Draw her in a blunt doodle style: round head, dot eyes, tiny mouth, quick scribbled hair, simple single-stroke limbs, slightly awkward proportions. She should look like a fast black-marker sketch, not an anime line drawing.

Scene:
turn "[abstract concept]" into "[physical metaphor]".
Make the girl perform the core action: "[action]".
Use the composition pattern: "[pattern]".
Only one core concept should be explained in the image.

Text labels:
add short handwritten Chinese labels only, 2 to 8 characters each, with no more than 5 to 8 label positions.

Avoid:
children-book style, kawaii mascot look, anime poster rendering, polished line art, pretty character design, infographic layout, formal flowchart title, gradient, shadow, textured paper, dense text, decorative-only character.
```

## Shot List Output Shape

When the user asks for planning first, output each proposed image with:

- placement after which paragraph
- theme
- core idea
- composition pattern
- what the girl is doing
- suggested Chinese label words

## Series Prompt Add-On

When generating multiple images for one article, append this consistency block to each prompt:

```text
It must match the same series style:
- sparse black-marker doodle
- same line weight
- same small secondary twin-tail girl scale
- same broad whitespace density
- same annotation density
- same restrained accent color usage
```
