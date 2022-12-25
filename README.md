# Plateau three.js FBX example

[Plateau](https://www.mlit.go.jp/plateau/ "Plateau")のモデルをthree.jsで表示するサンプルです。

##　動作環境

ローカルで動作させる場合[node.js](https://nodejs.org/ "node.js")が必要です

## 使い方

1　ダウンロードし、任意のディレクトリに配置してください

2　配置したディレクトリ
に移動し[G空間情報センターの「3D都市モデル（Project PLATEAU）東京都23区」]( https://www.geospatial.jp/ckan/dataset/plateau-tokyo23ku "G空間情報センターの「3D都市モデル（Project PLATEAU）東京都23区」")にあるFBXからモデルをダウンロードし、以下の2つのファイルをmodels下に配置してください。(13100_tokyo23-ku_2020_fbx_3_opはzip直下のディレクトリです。適宜読み替えてください)

・13100_tokyo23-ku_2020_fbx_3_op/bldg/lod1/53392546_bldg_6677.fbx
・13100_tokyo23-ku_2020_fbx_3_op/bldg/lod2/53392633_bldg_6677.fbx

3 以下のコマンドを入力し、依存ライブラリをインストールします

```
npm install
```

4 以下のコマンドでサーバーを起動し、http://localhost:3000にブラウザでアクセスしてください

```
npm run serv
```

