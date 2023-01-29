# PokeControllerForESP32

[Poke Controller Modified](https://github.com/Moi-poke/Poke-Controller-Modified)とSwitch間を中継するソフトウェア

# このソフトウェアについて

ろっこく氏のPoke-ControllerForLeonardoを参考にして作っています

# 導入方法

必要なもの

    ESP32-S3-DevkitC-1 1台(https://akizukidenshi.com/catalog/g/gM-17073/)
    USB マイクロケーブル 2本

動作環境

    Arduino IDE(1.8.19推奨)
    Arduino core for ESP32 (2.0.6)
    SwitchControllerESP32

# 使い方

## ソフトウェアのダウンロード

このリポジトリをダウンロードし適当なフォルダへ展開

## 書き込み

1. ESP32 S3 DevkitC-1のUSB端子のUARTシルク側をPCに接続、USBシルク側をSwitchへ接続
2. Arduino IDEを立ち上げる
3. ツール→ボード→ESP32 Arduino→ESP32S3 Dev Moduleを選択
4. シリアルポートも接続してるポートに変更
5. ファイル→開くでスケッチ(PokeControllerForESP32.ino)を開く
6. スケッチ→マイコンボードへ書き込む

Poke Controller側のCOM Port番号をESP32 S3 DevkitC-1のものに合わせてSwitch Controller Simulatorなどでボタンを押して動作確認してください

# 注意

まだキーボード入力には対応してません

# Lisence

このプロジェクトのライセンスはMITライセンスです。詳細はLICENSEをご覧ください
