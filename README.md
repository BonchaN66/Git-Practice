# Git操作練習リポジトリ（ローカル用）

このリポジトリは、Git操作の基本を実践的に学ぶための練習用です。  
Mac環境 + SourceTree を想定しています。

---

## 📌 目的

- Gitの基礎操作を習得する（add / commit / branch / merge / ignoreなど）
- `.gitignore`やブランチ運用など、実務的に必要な要素を体験する
- ファイル操作とGitの反映の関連を理解する

---

## ✅ 練習チェックリスト

### 基本操作
- [x] リポジトリの作成（SourceTreeから）
- [x] ファイル追加と初回コミット
- [x] `.gitignore` の設定と効果確認

### 編集・削除とコミット
- [ ] ファイル編集 → 差分確認 → コミット（`editable_note.txt`）
- [ ] ファイル削除 → Git検出 → コミット（`removable_note.txt`）

### ブランチとマージ
- [ ] 新しいブランチ `feature/git-practice` を作成
- [ ] 作業ブランチで編集・コミット
- [ ] `main` にマージ（fast-forward or merge commit）

### 応用操作
- [ ] コミットの取り消し（amend / reset）
- [ ] ファイル名変更の扱い
- [ ] `.gitignore` ルールの追加・確認

### GitHub連携（任意）
- [ ] GitHubにリモートPush
- [ ] プルリクエスト作成
- [ ] マージ後のブランチ削除

---

## 💬 備考

このREADME自体もGitでバージョン管理されており、練習内容の進捗を可視化できます。
