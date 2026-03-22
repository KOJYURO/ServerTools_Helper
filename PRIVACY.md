# Privacy Policy / プライバシーポリシー

## EN

### 1. Scope
This policy applies to ServerTools Helper operations in Discord servers.

### 2. Data Processed
The bot may process and store:
- Guild/channel context needed to answer slash commands
- Working XML files under data/workspaces
- Import backups under data/workspaces/<version>/backups
- Translation JSON files under data/translations
- Runtime logs in systemd journal

### 3. Purpose
Data is used only to:
- Load, validate, edit, import, and export ServerTools XML files
- Generate language-specific Phrases.xml outputs
- Maintain stable operation and troubleshoot failures

### 4. Storage
- Working copies: data/workspaces/<version>/
- Backups: data/workspaces/<version>/backups/
- Translations: data/translations/<version>/
- Logs: systemd journal / optional local logs

### 5. Sharing
No user personal data is intentionally shared with third parties by design.
Output files are sent only to the command invoker context in Discord.

### 6. Retention and Deletion
Operators can remove working files/backups at any time.
Discord-side message retention is controlled by each server policy.

### 7. Security Notes
- Keep token in environment files only
- Restrict host/file access
- Limit command usage to trusted roles/channels

### 8. Contact
Use your server support channel for privacy-related requests.

---

## JP

### 1. 適用範囲
本ポリシーは ServerTools Helper の Discord 運用に適用されます。

### 2. 処理する情報
本ボットは運用上、次の情報を処理・保存する場合があります。
- スラッシュコマンド応答に必要なギルド/チャンネル文脈
- data/workspaces 配下の作業 XML
- data/workspaces/<version>/backups 配下のバックアップ
- data/translations 配下の翻訳 JSON
- systemd journal の実行ログ

### 3. 利用目的
情報は次の目的でのみ利用します。
- ServerTools XML の読込・検証・編集・入出力
- 言語別 Phrases.xml の生成
- 安定運用と障害調査

### 4. 保存先
- 作業コピー: data/workspaces/<version>/
- バックアップ: data/workspaces/<version>/backups/
- 翻訳: data/translations/<version>/
- ログ: systemd journal / 任意ローカルログ

### 5. 共有
設計上、個人情報を第三者へ送信しません。
出力ファイルは実行コンテキストにのみ返却されます。

### 6. 保持期間と削除
運用者は作業ファイルやバックアップを任意で削除できます。
Discord 側の保持期間は各サーバー方針に従います。

### 7. セキュリティ注意
- トークンは環境変数で管理
- ホスト/ファイルアクセス制限
- 信頼できる権限者へ実行権限を限定

### 8. 連絡先
プライバシー関連の問い合わせは運用サポート窓口で対応してください。
