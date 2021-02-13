# Watson Discovery AI検索 UI
## 概要
IBM Watson Discoveryを使うことで、アップロードした文書やWebクロールによるAI検索が実施できるため、Node-REDを使ってUIを作成。

## 動作確認方法
- json形式のフローファイルを、Node-REDに「読み込む」ことで、Node-RED上で動かすことができる。
- Node-RED環境を用意。無料で使いたい場合は、IBM Cloud ライト・アカウントが最も楽。Node-RED自体は、オープンソースソフトウェア。
  - Node-RED 導入手順書 [Getting Started:Node-RED日本ユーザー会](https://nodered.jp/docs/getting-started/)
  - IBM Cloud以外でNode-REDを導入した場合は、Node-REDの画面右上の「三」→「パレットの管理」→「ノードを追加」の順にクリックし、「node-red-node-watson」ノードを追加しておくこと。
- 読み込み方法
  1. [flows-discoverysearch-ui.json](https://github.com/kolinz/node-red-recipe/blob/master/discoverysearchui/flows-discoverysearch-ui.json)に新規タブでアクセスし、「Raw」ボタンをクリック。
  1. 全選択(Windowsを利用の場合は、Ctrl+Aキー)を行い、その後コピーを実行。
  1. Node-REDを起動し、画面右上の「三」→「読み込む」をクリック。
  1. 「フローをクリップボードから読み込み」に、コピーしておいた、「flows-discoverysearch-ui.json」を貼り付け。
  1. 「読み込み先」に「新規タブ」を選択。
  1. 「読み込み」をクリック。
  1. 「Watson Discovery AI検索」タブが表示される。
  1. 読み込み後のNode-RED上のフロー
  ![読み込みフローイメージ](https://github.com/kolinz/node-red-recipe/blob/master/discoverysearchui/images/flowimage.png)
  

# 参考資料
- Watson Discoveryの使用には、IBM Cloudの登録が必要。
  - クレジットカード不要かつ無料 [IBM Cloud ライト・アカウント](https://www.ibm.com/jp-ja/cloud/lite-account)
  - [IBM Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery)
  - 資料 >> [IBM Dojo: Watson Discovery を使ったAI検索体験](https://speakerdeck.com/osonoi/watson-discoverywoshi-tutaaijian-suo-ti-yan)

