# 音色野郎
Version 1.02 -リリース版-

## 必要なソフトウェア
本ソフトウェアには、別途「IOCS.X」または「HIOCS.X Ver 1.10+16.19以降」、および「Z-MUSIC ver 2.xx」が必要です。<br>
また、データフォーマットも試食版と異なっておりますので試食版のデータファイルは使用できません。

## 履歴
- 2025/03/29 Version 0.50 試食版リリース
- 2025/04/02 Version 0.51 試食版リリース
- 2025/06/08 Version 0.60 試食版リリース
- 2025/07/11 Version 1.00 リリース版
- 2025/07/12 Version 1.01 バグ修正版
- 2025/07/12 Version 1.02 バグ修正版

## 概要
- SHARP X680x0シリーズ用のFM音源音色編集ソフトウェアです。<br>
- XDF形式のフロッピーイメージと単純な圧縮ファイルの２つを用意していますので、お手元の環境に合わせてご利用ください。<br>
  XDF形式のイメージは、XM6g等のエミュレータに「フロッピーディスク」として設定する事で使用できます。<br>
  ※起動イメージとしては作成されておりませんので、起動フロッピーとして使用する事はできません。<br>
- 画面上で、FM音源の音色作成と簡易な演奏による音色の確認を実施できます。

## インストール（フロッピーからではなく、ハードディスクから使用する場合）
 - フロッピーイメージの場合、ディスク内の「SndEd102」 ディレクトリを丸ごとエミュレータ上のハードディスクにコピーし、続いて「AUTOEXEC.BAT」を編集して環境変数「PATH」に、先ほどコピーしたディレクトリを追加する事で使用可能になります。

## 使用方法
- 事前にIOCS.XまたはHIOCS.X、およびZ-MUSIC Ver2を常駐させます。
- コマンドラインより「SoundEdt.X」を実行すると本ソフトウェアが起動します。

## 機能
本ソフトウェアは以下の機能を備えています。
- 音色データ・演奏データの保存／読み込み
- キーボードでの演奏内容を記録し、MMLとしてファイル出力
- 音色の新規作成／複製／編集／削除
- キーボードでの簡易演奏（オクターブ／音色／テンポ変更可能）
- キーボードでの演奏内容の記録、再生

## 操作
- 現状では、原則としてマウスでの操作が主体となります。<br>
- 本ドキュメントではボタン類の大まかな説明にとどめていますので、詳細は別資料[「操作説明」](Manual/Manual.md)をご参照ください。
  ### [ボタン]
  ![CmdBtn](https://github.com/user-attachments/assets/436fdc78-9735-4b1b-bf02-f43f0617b3b9)<br>
  画面上部に並んだボタンで、クリックする事で個々の機能が働きます。<br><br>
  ### [スピンボタン]
  ![SpinBtn](https://github.com/user-attachments/assets/2ae0bcc2-81bd-4aaa-a78a-71c8f8b20326)<br>
  数値欄と、その隣の上下矢印ボタンで構成されています。<br>
  数値欄への直接手入力と、矢印ボタンをクリックする事で値の増減が可能です。また、直接入力中にカーソル（矢印）キーの上下を押下しても値の増減が可能です。<br><br>
  ### [トグルボタン]
  ![TglBtn](https://github.com/user-attachments/assets/87007209-0284-48e0-9a02-f7b97160059b)<br>
  クリックする事でON/OFFを切り替える事が可能です。
  「ON」の場合には「●」が表示され、「OFF」の際には空欄となります。
- 簡単なヘルプ機能が実装されており、ボタン等の上でマウス右クリックする事で簡単な説明が表示されます。

## 参考文献
- SHARP X68000 X-BASIC ver 2.0 ユーザーズリファレンス<br>
  本ソフトウェアの説明文章は、その多くを「SHARP X68000 X-BASIC ver 2.0 ユーザーズリファレンス」に寄っております。作者のFM音源知識不足のため具体的な説明が乏しい文章になってしまっておりますが、今後少しでも改善できるよう精進したいと思います。
- Inside X68000
- Z-MUSIC ver2.08/ver3.01 添付ドキュメント

## 謝辞
本ソフトウェアは、以下の方々の素晴らしいソフトウェア群によって支えられております。<br>
この場をお借りして、作者の皆様に感謝致します。
- [PI.](https://twitter.com/xm6_original)様・[GIMONS](https://x.com/GimonsW)様
  <br>X68000エミュレータ「XM6 TypeG」
- [吉野智興](http://retropc.net/x68000/software/develop/c/gcc_mariko/)様
  <br>GNU Cコンパイラ「GCC真里子版 ver 1.42」
- [西川善司](https://x.com/zenjinishikawa)様
  <br>FM音源ドライバ「Z-MUSIC Ver2」
- [GORRY](https://x.com/gorry5)様
  <br>PIC/APIC形式画像ローダ　ライブラリ「APICGLIB」
- [yunk](https://x.com/yunkya2)様・[TcbnErik](https://x.com/kg68k)様
  <br>IOCS.X改良版「HIOCS PLUS」
  <br><br>
  **また、制作中にＸ（旧Twitter）上にて、多くの方々より貴重なアドバイスをいただきました。<br>
  皆様のお力添え無しには本作品はここまで到達できなかったであろうと思われます。<br>
  この場にて簡素ではありますが、改めてお礼申し上げます。**

# お願い
***
- 本ソフトウェアは正しく動作する事を期待して制作されておりますが、完全な動作を保証するものではありません。
- 本ソフトウェアはフリーウェアとして制作されていますので、個人的な使用に関する限り自由にコピー及び再配布が可能です。
- 本ソフトウェアに対して自由な個人的利用、フリーウェアとしての配布を妨げる事はご遠慮ください。<br>
	※本項は、フリーウェアとしての流通を妨げないようにするためのものです。
