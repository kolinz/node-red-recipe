# Watson Disovery AI検索
## 概要
IBM Watson Discoveryを使うことで、アップロードした文書やWebクロールによるAI検索が実施できるため、Node-REDを使ってUIを作成する。

## 動作確認方法
- json形式のフローファイルを、Node-REDに「読み込む」ことで、Node-RED上で動かすことができる。
- Node-RED環境を用意。無料で使いたい場合は、IBM Cloud ライト・アカウントが最も楽。Node-RED自体は、オープンソースソフトウェア。
  - Node-RED 導入手順書 [Getting Started:Node-RED日本ユーザー会](https://nodered.jp/docs/getting-started/)
- 読み込み方法
  1. Node-REDを起動し、画面右上の「三」→「読み込む」→「読み込むファイルを選択」をクリック。
  1. 「読み込み先」に「新規タブ」を選択。
  1. 「読み込み」をクリック。
  1. 「Watson Discovery AI検索」タブが表示される。
  

# 参考資料
- Watson Discoveryの使用には、IBM Cloudの登録が必要。
  - クレジットカード不要かつ無料 [IBM Cloud ライト・アカウント](https://www.ibm.com/jp-ja/cloud/lite-account)
  - [IBM Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery)
  - 資料 >> [IBM Dojo: Watson Discovery を使ったAI検索体験](https://speakerdeck.com/osonoi/watson-discoverywoshi-tutaaijian-suo-ti-yan)

