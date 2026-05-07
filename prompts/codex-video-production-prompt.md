# Codex Video Production Prompt

Use this prompt when starting a new cinematic motivation video.

```text
AGENTS.mdを読んだうえで、YouTube向けの英語モチベーション動画を制作してください。

目的:
英語音声、日本語焼き込み字幕、英語キーフレーズ、映画的インサートを使った3-5分のオリジナル動画を作る準備をする。

まず本文や素材を作り始める前に、以下を設計してください。

1. templates/video-brief.md をもとに企画を定義する
2. templates/video-script.md をもとに英語スピーチと日本語字幕を作る
3. templates/video-scene-board.md をもとにシーン割り振りを作る
4. templates/video-generation-prompts.md をもとに画像生成プロンプトと動画生成プロンプトを作る
5. templates/video-edit-spec.md をもとにRemotion/HyperFrames用のタイムライン設計を作る
6. templates/video-publish-pack.md をもとにタイトル、サムネ、概要欄、固定コメントを作る
7. templates/video-quality-check.md で品質確認する

必ず守ること:
- 有名人の肖像、声、映像、名言を使わない
- セリフはオリジナルにする
- ただの名言集にしない
- 各シーンには映像上の役割を持たせる
- 森、道、雨、部屋、朝日などの映画的インサートはセリフの比喩として使う
- 日本語字幕は直訳ではなく、自然な意訳にする
- 動画の最後に今日のミッションを1つ入れる

今回のテーマ:
[ここにテーマを入れる]

出力先:
videos/YYYY-MM-topic-slug/
```
