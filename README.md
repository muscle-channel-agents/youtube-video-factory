# Codex note factory

Codexで売れるnoteを量産するための作業テンプレートです。

## 最初の使い方

1. `templates/note-brief.md` をコピーして、作りたいnoteの企画を埋める。
2. `prompts/30-codex-note-skills.md` のスキル1から順番にCodexへ依頼する。
3. 生成物を `notes/YYYY-MM-topic-slug/` に保存していく。
4. 本文完成後、販売ページ・告知・運用まで同じフォルダにまとめる。

## おすすめの依頼文

```text
AGENTS.mdとprompts/30-codex-note-skills.mdを読んでください。
templates/note-brief.mdをもとに、売れるnote企画を1本設計してください。
まずスキル1から6まで実行し、brief.mdとresearch.mdにまとめてください。
```

本文まで進めるときは以下です。

```text
このnote企画について、スキル7から10を実行してください。
outline.mdとdraft.mdを作成し、最後にタイトル案を10個出してください。
```

販売まで進めるときは以下です。

```text
このnoteについて、スキル11から20を実行してください。
sales-page.mdとlaunch-plan.mdを作成してください。
誇大表現を避けつつ、購入率が上がる導線にしてください。
```

運用まで進めるときは以下です。

```text
このnoteについて、スキル21から30を実行してください。
operations.mdとimprovements.mdを作成し、3ヶ月の改善ロードマップを出してください。
```

## フォルダ構成

```text
AGENTS.md
README.md
prompts/
  30-codex-note-skills.md
templates/
  note-brief.md
  note-production-board.md
  sales-page.md
  launch-plan.md
  operations.md
  final-quality-check.md
notes/
  .gitkeep
```

