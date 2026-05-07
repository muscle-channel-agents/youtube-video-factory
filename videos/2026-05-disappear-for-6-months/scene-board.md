# Video Scene Board

## Scene Types

- Speaker Cut: original AI character close-ups and body language.
- Symbolic Cut: forest, road, fog, rain, dark room, sunrise as metaphor.
- Action Cut: turning phone over, writing, training, marking calendar.
- Text Cut: key English phrase on cinematic background.

## Scene Table

| ID | Time | Chapter | Narration Line | JP Subtitle | Scene Type | Visual Purpose | Asset Type | Duration |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S01 | 0:00-0:06 | Hook | Disappear for a while. | しばらく、静かに消えろ。 | Symbolic Cut | Enter the ghost-mode world immediately | AI video | 6s |
| S02 | 0:06-0:12 | Hook | Not because you are weak. Not because you lost. | 弱いからじゃない。負けたからでもない。 | Speaker Cut | Humanize the pressure | AI video | 6s |
| S03 | 0:12-0:18 | Hook | But because the next version of you needs silence. | 次の自分には、静けさが必要だからだ。 | Text Cut | State the thesis | Remotion/HyperFrames | 6s |
| S04 | 0:18-0:28 | Problem | Stop telling people what you are about to do. | これからやることを、人に話すのをやめろ。 | Action Cut | Show the habit of announcing | AI video | 10s |
| S05 | 0:28-0:40 | Problem | Stop explaining the plan. | 計画を説明するのをやめろ。 | Speaker Cut | Direct confrontation | AI video | 12s |
| S06 | 0:40-0:55 | Problem | Your goal is still young. Do not hand it to people who only know how to doubt. | お前の目標は、まだ育ち始めたばかりだ。疑うことしか知らない人に、渡さなくていい。 | Symbolic Cut | Protect the dream as a fragile seed | AI video | 15s |
| S07 | 0:55-1:05 | Decision | For the next six months, become harder to reach. | これから6か月、少し連絡がつきにくい人間になれ。 | Text Cut | Give the command | Remotion/HyperFrames | 10s |
| S08 | 1:05-1:18 | Decision | Not rude. Not bitter. Just focused. | 冷たくなるんじゃない。ひねくれるんじゃない。ただ、集中するんだ。 | Speaker Cut | Clarify the tone | AI video | 13s |
| S09 | 1:18-1:30 | Decision | Turn the phone over. Leave the group chat quiet. | スマホを伏せろ。グループチャットを静かにしろ。 | Action Cut | Make silence physical | AI video | 12s |
| S10 | 1:30-1:42 | Decision | You do not need an audience for the beginning. | 始まりに観客はいらない。 | Symbolic Cut | Empty room, private start | AI video | 12s |
| S11 | 1:42-1:55 | Work | You need a room. A notebook. A calendar. | 必要なのは、部屋。ノート。カレンダー。 | Action Cut | Show the tools of rebuilding | AI video | 13s |
| S12 | 1:55-2:08 | Work | There will be days when nothing changes. | 何も変わらない日が来る。 | Symbolic Cut | Fog and uncertainty | AI video | 13s |
| S13 | 2:08-2:20 | Work | That is the middle. | そこが、真ん中だ。 | Text Cut | Name the emotional battlefield | Remotion/HyperFrames | 12s |
| S14 | 2:20-2:32 | Work | You will not. | でも、お前は戻らない。 | Speaker Cut | Turning point | AI video | 12s |
| S15 | 2:32-2:48 | Work | You will walk through the fog. You will take the hard road. | 霧の中を歩け。険しい道を選べ。 | Symbolic Cut | Forest and road metaphor | AI video | 16s |
| S16 | 2:48-3:04 | Work | You will train when nobody is recording. | 誰も撮っていない場所で鍛えろ。 | Action Cut | Real work without audience | AI video | 16s |
| S17 | 3:04-3:18 | Work | You will study when nobody is clapping. | 誰も褒めない夜に勉強しろ。 | Action Cut | Quiet study at night | AI video | 14s |
| S18 | 3:18-3:32 | Return | And slowly, quietly, something will happen. | すると少しずつ、静かに変わり始める。 | Symbolic Cut | First morning light | AI video | 14s |
| S19 | 3:32-3:48 | Return | Your work will become evidence. | 積み上げたものが、証拠になる。 | Action Cut | Calendar, notebook, shoes, body language | AI video | 16s |
| S20 | 3:48-4:02 | Return | I did not abandon myself this time. | 今回は、自分を見捨てなかった。 | Speaker Cut | Emotional payoff in mirror | AI video | 14s |
| S21 | 4:02-4:15 | Final Mission | So today, do one thing in silence. | だから今日、1つだけ黙ってやれ。 | Text Cut | Mission appears | Remotion/HyperFrames | 13s |
| S22 | 4:15-4:25 | Final Mission | Build quiet. Return different. | 静かに積み上げろ。別人になって戻ってこい。 | Symbolic Cut | Final road into morning | AI video | 10s |

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

## Symbolic Insert Library Used

| Emotion | Visual Motif | Use |
| --- | --- | --- |
| Isolation | lone figure entering dark forest | S01, S15 |
| Protection | small plant under glass in dark room | S06 |
| Decision | phone turned face down | S09 |
| Uncertainty | foggy forest path | S12, S15 |
| Middle | black screen with minimal text and pulse | S13 |
| Hidden work | desk, notebook, gym, calendar | S11, S16, S17, S19 |
| Return | road at sunrise | S18, S22 |
