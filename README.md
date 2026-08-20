# .github — mjone-shinn 組織共通デフォルト

mjone-shinn 組織の**全リポジトリに自動適用される**共通ファイルを管理するリポジトリ。

| ファイル | 効果 |
|---------|------|
| `.github/ISSUE_TEMPLATE/` | 全リポジトリの「New issue」にテンプレート3種（タスク / バグ報告 / 相談・決定）を表示。空白Issueは無効化 |
| `.github/PULL_REQUEST_TEMPLATE.md` | 全リポジトリのPR作成画面に本文テンプレートを表示 |

- 各リポジトリが自前のテンプレートを持つ場合は、そちらが優先される。
- **このリポジトリは public であること必須**（GitHubの仕様。組織共通デフォルトは public の `.github` リポジトリからのみ配信される）。機密情報は置かない。
- 運用ルール本体は [github-rules](https://github.com/mjone-shinn/github-rules) を参照。

出典: [Creating a default community health file - GitHub Docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
