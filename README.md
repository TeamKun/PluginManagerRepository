# PluginManagerRepository
## 概要
[TeamKunPluginManager](https://github.com/TeamKun/TeamKunPluginManager)のデータ管理リポジトリです。
Github Actionsで自動化されています。
## 注意
1.15.2向けプラグインですので、1.15.2の依存関係を追加してください。
## 追加方法
+ Issue templateから`\{REQUEST\} Additional url into database.json` を選びます。
+ タイトルは何も変更せずに、本文に、コンマ区切りのエントリを貼ります。
### エントリの記述方法
```
ProtocolLib,https://hogehoge.com/downloads/ProtocolLib.jar
↑ベーシックな方法です。jarをそのまま指定します。
ProtocolLib,https://github.com/exampleuer/
↑つよい方法です。GitHubのURLを貼ります。
```
