# GPT Image 2 Prompt Skill

![Prompt Skill](https://img.shields.io/badge/Prompt%20Skill-GPT%20Image%202-0f172a?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)

A compact agent skill for turning rough image ideas into clean, structured GPT Image 2 prompts.

![GPT Image 2 Skill comparison](assets/comparison.png)

## What It Does

- Preserves the original idea.
- Improves prompt clarity without overengineering.
- Adds practical visual fields only when useful.
- Selects a fitting aspect ratio from `3:1` to `1:3`.
- Outputs only the final prompt, ready for image generation.

## ChatGPT Web

Enable Memory, then save this instruction before generating images:

```text
Before generating photos, use this skill to create the prompt:
https://github.com/UzenUPozitiv4ik/gpt-image-2-skill/blob/main/gpt_image_2_prompt_skill.md
```

## Recommendation

For best results, use Codex or the API with high quality image generation.

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

## License

MIT
