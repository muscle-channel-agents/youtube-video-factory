# Video Edit Spec

## Output Settings

- Main format: 1920x1080, 16:9
- Shorts format: 1080x1920, 9:16
- Frame rate:
- Target loudness:
- Export format: MP4

## Brand Style

- Main font:
- English key phrase font:
- Japanese subtitle font:
- English text color:
- Japanese subtitle color:
- Accent color:
- Subtitle position:
- Text safe area:
- Film grain:
- Vignette:

## Audio Mix

- Narration volume:
- BGM volume under narration:
- BGM volume during text cuts:
- SFX:
- Silence moments:

## Timeline Data Model

Use this shape for Remotion or HyperFrames automation.

```json
{
  "video": {
    "title": "",
    "durationSeconds": 240,
    "fps": 30,
    "format": "16:9"
  },
  "assets": {
    "narration": "assets/audio/narration.mp3",
    "bgm": "assets/audio/bgm.mp3"
  },
  "scenes": [
    {
      "id": "S01",
      "start": 0,
      "duration": 5,
      "type": "ai-video",
      "asset": "assets/video/S01.mp4",
      "chapter": "Hook",
      "englishText": "DISAPPEAR",
      "japaneseSubtitle": "しばらく、静かに消えろ。",
      "effects": ["film-grain", "vignette", "slow-zoom"]
    }
  ]
}
```

## Edit Checklist

- [ ] Hook starts within the first 2 seconds.
- [ ] No scene feels like random filler.
- [ ] Symbolic inserts match the narration line.
- [ ] Japanese captions are readable on mobile.
- [ ] English key phrases are short and easy to understand.
- [ ] BGM supports the speech, not the other way around.
- [ ] At least 40% of the video has real motion or AI video clips.
- [ ] The final line has room to breathe.
