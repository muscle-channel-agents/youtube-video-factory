# Mobile PC Setup

This guide explains how to work on this YouTube video factory from another PC.

## Goal

Make the workflow portable across:

- Main desktop PC
- Mobile laptop
- Future replacement PC

The project files should move with Git or OneDrive. Heavy generated assets can be synced separately.

## What Must Be Shared

### Repository Files

These should be synced through Git or OneDrive:

```text
AGENTS.md
README.md
prompts/
templates/
videos/
notes/
```

### Channel Strategy

Keep these files updated because every video depends on them:

```text
videos/channel-strategy/channel-concept.md
videos/channel-strategy/audience-persona.md
videos/channel-strategy/brand-rules.md
```

### Per-Video Production Files

Each video should live in:

```text
videos/YYYY-MM-topic-slug/
```

Minimum files:

```text
brief.md
script.md
scene-board.md
generation-prompts.md
edit-spec.md
publish-pack.md
quality-check.md
metrics.md
assets/
```

## Recommended Sync Options

## Option A: GitHub

Best for text files, templates, scripts, prompts, and version history.

Use GitHub for:

- Templates
- Prompts
- Strategy files
- Scripts
- Timeline JSON
- Small metadata files

Avoid committing:

- Large raw videos
- Huge AI exports
- Temporary renders
- Downloaded reference videos

## Option B: Google Drive

Best for moving assets between PCs without thinking too much.

Use Google Drive for:

- AI-generated images
- AI-generated video clips
- Narration audio
- BGM candidates
- Exported review videos

Use only this dedicated Google Drive folder as the asset root:

```text
BUILT IN SILENCE/
```

Folder URL:

```text
https://drive.google.com/drive/folders/1OpDIl2gCR_LmanNK1Z_pJvG-Jhtnnr1l
```

Main PC local sync path:

```text
C:\Users\mat09\Google Drive\My Drive\BUILT IN SILENCE\
```

Then reference project folders under that root in each video's production files.

## Recommended Folder Layout

```text
New project/
  templates/
  prompts/
  videos/
    channel-strategy/
    2026-05-disappear-for-6-months/
      brief.md
      script.md
      scene-board.md
      generation-prompts.md
      edit-spec.md
      publish-pack.md
      quality-check.md
      metrics.md
      assets/
        images/
        video/
        audio/
        exports/
```

## Tools To Install Or Log Into

### Required

- Codex app
- ChatGPT account with image generation
- ElevenLabs
- Kling, Lovart, Runway, or another image-to-video tool
- CapCut, DaVinci Resolve, Premiere Pro, Remotion, or HyperFrames

### Optional

- Git
- GitHub Desktop
- Node.js
- Topaz Video AI
- Epidemic Sound or Artlist

## Tool Account Checklist

- [ ] ChatGPT can generate images.
- [ ] ElevenLabs account is logged in.
- [ ] Main narrator voice is saved or documented.
- [ ] Image-to-video tool is logged in.
- [ ] Editing tool is installed.
- [ ] BGM source is available.
- [ ] YouTube channel access is available.

## What To Document For Each Tool

Do not store passwords or API keys in this repository.

Document only:

- Tool name
- Account email hint
- Plan name
- Main settings
- Export settings
- Voice name or ID if safe to store
- License notes

Create a private local file if needed:

```text
local-tool-settings.private.md
```

Do not commit that file if it contains sensitive details.

## Moving Work Between PCs

### Before leaving the main PC

1. Save all production files.
2. Sync OneDrive.
3. Commit or push text changes if using GitHub.
4. Export any needed reference files.
5. Confirm assets are in the synced folder.

### On the mobile PC

1. Pull or sync the project.
2. Open the relevant `videos/YYYY-MM-topic-slug/` folder.
3. Continue from `video-production-board.md` or the per-video checklist.
4. Generate missing assets.
5. Update `metrics.md` or production notes before switching back.

## Recommended Git Ignore Rules

If using GitHub, add these to `.gitignore`:

```text
*.mp4
*.mov
*.wav
*.mp3
*.psd
*.prproj
*.drp
local-tool-settings.private.md
videos/**/assets/
```

Keep prompts, scripts, and scene boards in Git. Keep heavy assets in OneDrive or another cloud folder.

## Best Practice

Use the repository as the brain.
Use the dedicated Google Drive folder as the asset warehouse.
Use Codex on either PC to continue from the same production files.
