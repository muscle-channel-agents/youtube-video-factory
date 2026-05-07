# Video Scene Board

Use this file to turn the speech into shots. Each scene should have a job. Avoid random cinematic filler.

## Scene Types

- Speaker Cut: human presence, direct emotion, face, body, breath.
- Symbolic Cut: forest, road, rain, stairs, empty station, dark room, sunrise.
- Action Cut: running, writing, training, turning off phone, marking calendar.
- Text Cut: key English phrase on a simple cinematic background.

## Scene Table

| ID | Time | Chapter | Narration Line | JP Subtitle | Scene Type | Visual Purpose | Asset Type | Duration |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S01 | 0:00-0:05 | Hook |  |  | Speaker Cut |  | AI video | 5s |
| S02 | 0:05-0:10 | Hook |  |  | Text Cut |  | Remotion/HyperFrames | 5s |
| S03 | 0:10-0:16 | Problem |  |  | Symbolic Cut |  | AI video | 6s |

## Image Prompt Template

```text
Cinematic [shot type] of [subject], [emotion], [location], [lighting], [color grade],
[composition], realistic skin texture if human, shallow depth of field, film still,
high contrast, moody atmosphere, no text, no logos, no watermark.
```

## Video Prompt Template

```text
[Camera movement]. [Subject motion]. [Environmental motion]. [Lighting motion].
Subtle realistic movement, cinematic pacing, no fast cuts, no major facial distortion,
no extra people, no text, no logos, no watermark.
```

## Negative Prompt

```text
cartoon, anime, plastic skin, over-smoothed face, distorted hands, extra fingers,
warped eyes, unreadable text, logo, watermark, celebrity likeness, famous athlete,
overly dramatic action, fast camera movement, low resolution, stock photo look.
```

## Symbolic Insert Library

| Emotion | Visual Motif | Use When |
| --- | --- | --- |
| Isolation | lone figure in dark forest | The script says disappear, go silent, or be hard to reach |
| Uncertainty | foggy road with no clear end | The script says you do not know when results will come |
| Discipline | same road at sunrise | The script says keep showing up |
| Temptation | phone glowing in dark room | The script says cut distractions |
| Pressure | rain on face or window | The script says the work hurts |
| Return | person walking into morning light | The script says results will speak |
