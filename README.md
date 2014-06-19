==========================
LabVIEW BuildAction VI
==========================

# 概要
  Exeをビルドする際の前処理、後処理を実行するためのVI集


## 対応する環境
  LabVIEW 2009 で作成します。

## 使用方法
  必要な Build Action VI をプロジェクトのソースに追加（コピー）し、それを LabVIEW プロジェクトにも
追加してください。
  Exe のビルド設定 >> ビルド前/後の動作の設定で、登録した Build Action VI を選択してください。

# BuildAction VI の一覧

## 前処理 (Pre-Build Action)


## 後処理 (Pre-Build Action)

* Post-Build Action_AddToIni_allowmultipleinstances.vi: アプリケーションINIファイルに多重起動を許可する設定を追加する。

