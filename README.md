# ガントチャート

個人用のガントチャート兼プロジェクト管理表です。

## Renderで公開する手順

1. このフォルダを新しいGitHubリポジトリにpushします。
2. Renderで `New` -> `Static Site` を選びます。
3. GitHubリポジトリを接続します。
4. 設定は以下にします。

| 項目 | 値 |
| --- | --- |
| Build Command | `echo "No build step"` |
| Publish Directory | `.` |

`render.yaml` を使う場合は、RenderのBlueprintとしてこのリポジトリを選ぶだけでも同じ設定で作れます。

## メモ

タスクやチェックの入力内容はブラウザのlocalStorageに保存されます。GitHubやRenderに公開しても、あなたがブラウザで入力した内容が自動で他の人に共有されるわけではありません。
