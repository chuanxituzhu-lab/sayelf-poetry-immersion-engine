# SayElf Poetry Immersion Engine Skill

## Purpose

Transform one classical Chinese poem into a compact, evidence-aware content delivery pack for human review and creative production.

## Core sequence

1. Identify the poem, author, period, and scene.
2. Separate claims into:
   - `C` — primary text or directly observable wording;
   - `E` — historical, biographical, or textual evidence;
   - `S` — synthesis, interpretation, or creative transformation.
3. Mark interpretation as interpretation; do not present it as historical fact.
4. Build a scene, character, object, space, light, and style continuity lock.
5. Produce one image prompt per key frame.
6. Produce one video storyboard prompt per key frame.
7. Check that storyboard count equals key-frame count.
8. Adapt the approved material to the selected platform.
9. Run the delivery QA checklist.

## Public-release boundary

The public demo is a local, single-file artifact. It must not contain private contact images, credentials, unpublished datasets, customer information, or complete commercial package contents. Commercial extensions remain placeholders in this repository.

## Evidence labels

- `Observation` — directly present in the source text or visible artifact.
- `Inference` — a reasoned reading supported by observations.
- `Hypothesis` — a creative or historical possibility that still needs checking.
- `Fact` — a claim supported by a named source or explicit project evidence.

When evidence is incomplete, keep the label visible and route the item to human review.
