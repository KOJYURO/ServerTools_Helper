# ServerTools Helper

Dedicated Discord bot for ServerTools Config and Phrases operations.

## Bot Brief (BB)

ServerTools Helper provides a safe, working-copy-first workflow for ServerTools XML operations in Discord.

### Key Features
- Version-aware config loading
- Working-copy-only XML editing
- Safe XML import with automatic backups
- XML export from working or base source
- Language-specific Phrases.xml export
- Translation coverage overview
- Stability checks and sync visibility
- Rotating rich presence with current server count

### How It Works
- /load: Load selected version and open editor UI
- /xml_import: Replace working copy from uploaded XML
- /xml_export: Export XML from working or base
- /phrases_export: Build language-specific Phrases.xml
- /languages: Show translation coverage
- /validate: Run integrity checks
- /sync_status: Show slash sync/runtime status

### Good to Know
- Source XML under SharedFiles is never edited directly
- Risky operations are executed only on per-version working copies
- Validate outputs before applying to production

## Supported Versions
- `g2.5.1.7`
- `g2.5.1.9`

---

## 日本語

ServerTools Config と Phrases 操作に特化した Discord Bot です。

## Bot Brief (BB)

ServerTools Helper は、Discord 上で ServerTools XML を安全に扱うための working copy 優先ワークフローを提供します。

### 主な機能
- バージョン別 Config 読み込み
- working copy のみを対象にした XML 編集
- 自動バックアップ付きの安全な XML import
- working/base を選べる XML export
- 言語別 Phrases.xml export
- 翻訳率の確認
- 安定性チェックと同期状態可視化
- サーバー数ベースの Rich Presence ローテーション

### 動作フロー
- /load: 対象バージョンを読み込み編集 UI を起動
- /xml_import: 添付 XML で working copy を置換
- /xml_export: working または base から XML を出力
- /phrases_export: 言語別 Phrases.xml を生成
- /languages: 翻訳率を表示
- /validate: 整合性チェックを実行
- /sync_status: slash command の同期状態を表示

### 補足
- SharedFiles 配下の原本 XML は直接編集しません
- 変更リスクのある処理は version 別 working copy に限定されます
- 本番反映前に出力内容を必ず確認してください

## 対応バージョン
- `g2.5.1.7`
- `g2.5.1.9`
