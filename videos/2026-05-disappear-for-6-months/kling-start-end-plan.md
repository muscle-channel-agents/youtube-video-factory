# Kling Start/End Frame Plan

Use Start/End frames for shots where the motion needs a clear transformation. Single-image animation is still useful for atmospheric shots, but it can feel too static for key story beats.

## When To Use Two Frames

- The subject needs to move from one place to another.
- The scene needs a visible before/after.
- The shot represents a decision, crossing a threshold, or returning changed.
- The single-image animation feels atmospheric but too still.

## Priority Scenes For Two Frames

| Scene | Start Frame | End Frame | Motion Goal | Status |
| --- | --- | --- | --- | --- |
| S01 | `images/S01-forest-entrance.png` | `images/S01-end-deeper-forest.png` | The figure moves from the forest edge into the path. | End frame needed |
| S09 | `images/S09-start-phone-glow.png` | `images/S09-phone-face-down.png` | The phone turns face down and the blue light disappears. | Start frame optional |
| S15 | `images/S15-walking-through-fog.png` | `images/S15-end-deeper-forest.png` | The figure walks deeper into the foggy forest. | End frame needed |
| S20 | `images/S20-start-mirror-down.png` | `images/S20-mirror-payoff.png` | The man raises his eyes toward the mirror. | Start frame optional |
| S22 | `images/S22-start-dark-road.png` | `images/S22-return-different.png` | The figure moves from darkness toward sunrise. | Start frame optional |

## S01 End Frame Prompt

```text
Create a cinematic 16:9 still image for an original motivational video.
Do not use or imitate any celebrity, athlete, actor, movie scene, brand logo, or copyrighted character.
No text, no captions, no watermark, no logos.

Scene: The same mood as S01. A lone young Japanese or mixed-Asian man in a plain black hoodie is now several steps deeper inside a dark forest path at night, seen from behind. He is smaller in the frame, moving away from the viewer. The forest is denser than the entrance, cold fog is thicker between the trees, and the wet muddy path reflects faint blue-green light. A subtle distant blue glow appears deeper in the forest. The image should feel like someone disappearing from the world on purpose.

Style: realistic, cinematic, high contrast, subtle film grain, deep teal and black color grade, moody atmosphere, wet ground reflections, restrained lighting, 16:9 composition.
```

## S01 Kling Prompt With Start/End Frames

```text
Use the first image as the starting frame and the second image as the ending frame.
Create a slow cinematic forward tracking shot as the lone figure moves from the forest entrance deeper into the dark forest path.
Keep the figure seen from behind with no face reveal.
Cold fog drifts between the trees, wet ground reflects faint blue-green light, and branches move gently.
The movement should feel quiet, deliberate, and serious, like disappearing from the world to rebuild.
No fast camera movement, no extra people, no text, no logos, no distortion.
```

## General Kling Settings

- Duration: 5 seconds
- Motion: medium-low for atmosphere, medium for walking/action shots
- Camera: slow push-in, slow tracking, or subtle handheld
- Avoid: fast motion, face reveal, extra people, readable text, logos, hand distortion
