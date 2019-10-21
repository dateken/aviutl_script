# 鏡面反射スクリプト
AviUtlの拡張編集用の鏡面反射スクリプトです

## ダウンロード
"Clone or download" ボタンをクリックし，"Download ZIP" を選択してダウンロードしてください．

## インストール
ダウンロードされたzipファイルを解凍し，script内のファイルをAviUtlのscript内へコピーしてください．

## 使い方
___
### @Cube_Mapping
カメラ座標を中心にキューブマップを描画するカスタムオブジェクト用スクリプトです．

カメラ制御ON，拡張描画でのみ正しく動作します．

"参照"ボタンからキューブマップ用のテクスチャ画像を読み込んでご利用ください．

- オフセット
  - キューブマップの面の隙間を埋めるためのオフセット量をピクセル単位で指定します．
- 空間サイズ
  - 描画するキューブマップのサイズをピクセル単位で指定します．0が指定された場合，カメラの焦点距離の10倍のサイズになります．

___
### @Reflection_Mapping
オブジェクト表面に鏡面反射のようにキューブマップ画像を投影するアニメーション効果用スクリプトです．

カメラ制御ON，拡張描画でのみ正しく動作します．

"参照"ボタンからキューブマップ用のテクスチャ画像を読み込んでご利用ください．

- オフセット
  - キューブマップの面の隙間を埋めるためのオフセット量をピクセル単位で指定します．
- 空間サイズ
  - 描画するキューブマップのサイズをピクセル単位で指定します．0が指定された場合，カメラの焦点距離の10倍のサイズになります．
- 裏面を計算する
  - チェックを外すと裏面の投影計算を省略します．
___

## 動作環境
AviUtl 1.00, 拡張編集Plugin version 0.92 で動作確認しています．

## バグ報告等
https://github.com/dateken/AUL_reflection_mapping へお願いいたします．
