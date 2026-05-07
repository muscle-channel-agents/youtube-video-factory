# Video Edit Spec

## Output Settings

- Main format: 1920x1080, 16:9
- Shorts format: 1080x1920, 9:16 derivative after main edit
- Frame rate: 30fps
- Target loudness: around -14 LUFS integrated for YouTube
- Export format: MP4 H.264
- Target duration: 4:25

## Brand Style

- Main font: Noto Sans JP or Inter fallback
- English key phrase font: Anton, Bebas Neue, or bold condensed sans
- Japanese subtitle font: Noto Sans JP Bold
- English text color: #f5f5f0
- Japanese subtitle color: #ffffff with soft dark shadow
- Accent color: muted red #b83a32 or warm gold #d9a441 only for tiny emphasis
- Subtitle position: lower third, inside safe area
- Text safe area: 8% horizontal, 10% vertical
- Film grain: subtle, 8-12%
- Vignette: subtle, darker on symbolic inserts

## Audio Mix

- Narration tool: ElevenLabs
- Voice ID: ZthjuvLPty3kTMaNKVKb
- Narration volume: primary, clear and intimate
- BGM volume under narration: low, never competing
- BGM volume during text cuts: slight rise
- SFX: phone click, rain, soft room tone, low impact hits for key text only
- Silence moments: before "That is the middle.", before "I did not abandon myself this time.", before final line

## Timeline Data Model

```json
{
  "video": {
    "title": "Disappear for 6 Months",
    "durationSeconds": 265,
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
      "duration": 6,
      "type": "ai-video",
      "asset": "assets/video/S01.mp4",
      "chapter": "Hook",
      "englishText": "DISAPPEAR FOR A WHILE",
      "japaneseSubtitle": "しばらく、静かに消えろ。",
      "effects": ["film-grain", "vignette", "slow-zoom"]
    },
    {
      "id": "S03",
      "start": 12,
      "duration": 6,
      "type": "text-cut",
      "asset": null,
      "chapter": "Hook",
      "englishText": "NEXT VERSION NEEDS SILENCE",
      "japaneseSubtitle": "次の自分には、静けさが必要だからだ。",
      "effects": ["grain", "word-fade"]
    },
    {
      "id": "S22",
      "start": 255,
      "duration": 10,
      "type": "ai-video",
      "asset": "assets/video/S22.mp4",
      "chapter": "Final Mission",
      "englishText": "BUILD QUIET. RETURN DIFFERENT.",
      "japaneseSubtitle": "静かに積み上げろ。別人になって戻ってこい。",
      "effects": ["warm-grade", "slow-fade-out"]
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
