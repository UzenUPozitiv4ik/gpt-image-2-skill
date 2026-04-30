# GPT Image 2 Prompt Skill

![Prompt Skill](https://img.shields.io/badge/Prompt%20Skill-GPT%20Image%202-0f172a?style=for-the-badge)
![Agent Ready](https://img.shields.io/badge/Agent-Ready-2563eb?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)

A compact agent skill for turning short prompts into beautiful, realistic GPT Image 2 images.

![GPT Image 2 Skill comparison](assets/comparison.png)

## What It Does

- Preserves the original idea.
- Turns brief ideas into polished realistic image prompts.
- Improves prompt clarity without overengineering.
- Adds practical visual fields only when useful.
- Selects a fitting aspect ratio from `3:1` to `1:3`.
- Outputs only the final prompt, ready for image generation.

## Current Modes

- Everyday photo: natural, realistic, phone-like images.
- Cinematic still: film-frame composition, lighting, and mood.
- Small improvements for UI, infographics, and memes.

## ChatGPT Web (currently works very poorly on chatgpt web)

Enable Memory, then save this instruction before generating images:

```text
Before generating photos, use this skill to create the prompt:
https://github.com/UzenUPozitiv4ik/gpt-image-2-skill/blob/main/gpt_image_2_prompt_skill.md
```

## Recommendation

For best results, use Codex or the API with high quality.

## Output Style

```text
Generate an image with the following prompt, dont change it -

object:
setting:
style:
lighting:
composition:
aspect ratio:
```

## Use It For

Photos, cinematic shots, ads, infographics, memes, product visuals, and quick visual concepts.

## Examples

![Example 1](assets/example1.png)

```text
Jenna Ortega and Sabrina Carpenter walking through a park.
```

![Example 2](assets/example2.png)

```text
Dario Amodei and Sam Altman performing at a Tiny Desk concert, wearing their everyday clothes, cinematic film still.
```

![Example 3](assets/example3.png)

```text
Jenna Ortega and Sabrina Carpenter walking through a park, cinematic film still.
```

![Example 4](assets/example4.png)

```text
Create one 16:9 image made from four vertical 9:16 Snapchat-style meme selfies. Jenna Ortega and Sabrina Carpenter appear in different iconic video game worlds, with their outfits matching each world. Each selfie has a distinct interesting vibe, realistic lighting, and a playful candid phone-photo feel.
```

## License

MIT
