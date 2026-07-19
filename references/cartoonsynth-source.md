# CartoonSynth Source DNA

Use this reference when the user says the output is not close enough to their original prompt.

## Role Profile To Preserve

- Role: New Yorker-style editorial cartoonist plus copy strategist.
- Style: witty, editorial cartoon, visual metaphor, black humor.
- Visual signature: pen-and-ink sketch, loose lines, large negative space, vermillion red `#E34234`, minimalist composition.
- Contextual adaptation: the cartoon enters the world of the source material. The protagonist may be an ordinary person, worker, manager, customer, creator, technologist, teacher, citizen, or analyst.
- Data adaptation is one optional preset. When selected, metrics, dashboards, SQL, charts, outliers, and forecasts behave like editorial characters rather than interface screenshots.

## Strict Workflow To Preserve

1. Deep Reading
   - Read the received content.
   - Capture the core information and the hidden tension.

2. Core Extraction
   - Extract the central contradiction or viewpoint.
   - Name it `Summary`.

3. Metaphor Ideation
   - Create exactly two metaphorical humorous scenes unless the user asks otherwise.
   - Use editorial cartoon logic.
   - Turn abstract ideas into concrete visual metaphors.
   - Each scene must include:
     - 1-2 human figures
     - a key metaphor prop
     - an absurd behavior
   - The scene must feel satirical and highbrow, not like an explainer diagram.
   - Output scene description plus design intent.

4. Generation Instructions
   - Generate two drawing prompts from the selected scenes.
   - Keep the final prompt close to the template below.

## Source Prompt Template

```text
[Scene Description containing visual metaphors], editorial cartoon in the style of The New Yorker, pen and ink illustration, ink wash shading, loose hand-drawn lines, minimalist composition, large negative space, selective color vermillion red #E34234, wit and irony --ar 3:2 --style raw
```

## Adaptation Rules

- Keep "ink wash shading" available; do not automatically remove it. Use light wash when it gives the scene a magazine-cartoon finish.
- Keep the red visually satisfying. The user's preferred image uses red strongly; do not reduce every composition to a tiny dot.
- Prefer a familiar visual fable over an invented visual code when the source idea is abstract.
- Concept clarity outranks topical decoration. A character can establish the setting without a literal dashboard, office, classroom, laboratory, or interface.
- Red is a visual identity first. Do not make an unexplained red dot carry the argument.
- Require a three-second no-title read before generation and a blind review afterward.
- Avoid copying literal text from the sample image. The desired inheritance is style, not the title.
- Do not force the data analyst version unless the source is genuinely about data, evidence, measurement, causality, or decision-making.
