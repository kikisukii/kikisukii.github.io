# Wota Grid Maker · 发布配置 / 公開設定

**项目代码与双语说明：[kikisukii/wota-grid-maker](https://github.com/kikisukii/wota-grid-maker)**

本仓库仅保存GitHub Pages发布配置。请在上面的主仓库修改代码。

このリポジトリはGitHub Pagesへの公開設定専用です。コードの変更は上記のメインリポジトリで行ってください。

- [中文版](https://kikisukii.github.io/wota-grid-maker/)
- [日本語版](https://kikisukii.github.io/wota-grid-maker-jp/)

GitHub Actions从主仓库的main分支读取代码并发布，无需额外密钥。约每30分钟检查更新，内容未变时跳过部署；需要立即发布时，在[发布流程](https://github.com/kikisukii/kikisukii.github.io/actions/workflows/publish.yml)点击 **Run workflow**。

GitHub Actionsがメインリポジトリのmainブランチからコードを取得して公開します。追加のシークレットは不要です。約30分ごとに更新を確認し、変更がない場合は公開処理をスキップします。すぐに公開する場合は、上記ワークフローで **Run workflow** を選んでください。

GitHub的定时任务可能延迟，公开仓库长期无活动时也可能自动停用。停用后需在Actions中重新启用。

GitHubのスケジュール実行には遅延が生じる場合があります。また、公開リポジトリが長期間更新されないと自動停止することがあります。その場合はActionsで再開してください。
