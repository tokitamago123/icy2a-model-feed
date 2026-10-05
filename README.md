# Icy2A model feed

GitHub Pages: main branch, /docs folder. Unity Source Url: https://tokitamago123.github.io/icy2a-model-feed/model.i2am

モデルの書き出し後、Prepare-Model.ps1へファイルを渡すとdocs/model.i2amを置き換え、Revisionを自動で増やします。元の書き出しファイルは変更しません。Publish-Feed.ps1で選択済みの公開リポジトリへpushします。反映にはGitHub Pagesのデプロイとキャッシュ更新が必要です。

UnityワールドへURL付きローダーを一度組み込んだ後は、同じURLのデータ更新によってワールドを再公開せずにモデルを変更する設計です。初回のワールド組み込み・公開は別作業です。

対応: I2AM v1、単一メッシュ、4096頂点、8192三角形、256フレーム、16MiB。外観はシアン表示。Unityプロジェクト、FBX原本、テクスチャ、認証情報はこの配信リポジトリへ含めません。
