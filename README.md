# single-moduleなmaven webappのサンプル

## 概要
- cargo-maven3-pluginでローカルに別途用意されたtomcat9を使用
- mvn 
- デバッグ実行ボタンで リモートデバッグのattach
- mvn war:war cargo:redeployで再デプロイ

## 環境設定

- example用ファイルをコピーして個人用ファイルの作成
    - `cp .vscode/launch.json.example .vscode/launch.json`
    - `cp .vscode/tasks.json.example .vscode/tasks.json`
    - 複製したファイルはgit管理対象外
