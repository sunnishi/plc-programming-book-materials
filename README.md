# 『図解で学ぶ PLCプログラミング入門』の教材

西城戸 亮 著『図解で学ぶ PLCプログラミング入門：ラダーの基本から搬送・位置決め・PID・通信・異常復帰まで』（内容増補版）の教育用教材です。

## 教材ZIPをダウンロードする

**[教材ZIPをダウンロード（約180 KB）](https://github.com/sunnishi/plc-programming-book-materials/releases/download/v2.1.0/plc_programming_code.zip)**

- 最新の教材：v2.1.0（2026年10月24日）
- ファイル名：`plc_programming_code.zip`
- [この版の配布ページ](https://github.com/sunnishi/plc-programming-book-materials/releases/tag/v2.1.0)

ダウンロードにGitHubアカウントは不要です。配布ページの「Assets」から取得する場合は、`plc_programming_code.zip`を選んでください。自動表示される「Source code (zip)」「Source code (tar.gz)」には、教材は入っていません。

ZIPを展開すると`code`フォルダーができます。書籍の「はじめに」のクイックスタート、または第8章の手順で始めてください。

## 収録内容

| 学ぶ内容 | 教材内の場所 |
| --- | --- |
| スキャン、TON、自己保持、PI、九状態のセルの教育用モデル | `plc_model.py` |
| 37項目の試験（はじめに・第8章） | `verify.py` |
| 良品・不良品・検査応答なしの仮想シナリオ（第18章） | `demo.py`、`generated` |
| STへの移植用コード（付録D） | `cell_example.st` |
| 時間・PI・位置決め・通信の追加モデルと13項目の試験（第21〜27章、付録F） | `advanced` |
| 工程・試験・変更の記入書式 | `templates` |

## 実行環境と検証範囲

Python 3.10以降の標準ライブラリだけで動きます。制作時の環境はmacOSとPython 3.10です。教材の試験はPythonの教育用モデルと数学の範囲です。STの実機ビルド、PLC・実I/O・通信機器・生産設備での動作、安全性能は確認していません。

## 正誤表

現時点で、報告された誤りはありません。

## 質問・不具合の報告

本文の誤りや、教材が動かない場合は、[Issues](https://github.com/sunnishi/plc-programming-book-materials/issues)から報告してください。OS、Pythonの版、実行したコマンド、表示されたメッセージを添えると状況を確認しやすくなります。設備の図面や社内の情報は書き込まないでください。個別の設備への導入支援は対象外です。

## 利用条件

収録コードは、学習と自分の設計の試作に改変・利用できます（LICENSEを参照）。PLCメーカーの開発ソフトや機器の利用条件は、それぞれの提供元に従います。

## ダウンロードしたファイルを確認する

[SHA256SUMS.txt](SHA256SUMS.txt)の値と照合できます。
