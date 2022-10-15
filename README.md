# XIAOスクエア液晶モジュール（準備中）

![](gaiken.jpg)

SeeedStudioのXIAOを使用して1.69インチ240ｘ280ドットの角丸四角形液晶を駆動する基板モジュールです。

液晶の裏にXIAOを配置してしまいました。

余り領域にサウンダもつけてみました。

さらに、FET(AO3400A)を搭載してDCモータかソレノイドを１個駆動出来るようにしました。(駆動出来る電流は5V入力電源側に依存しますが、1A以下とお考え下さい)

液晶にはst7789v2というコントローラーが使用されていますが、対応したグラフィックライブラリが数種類公開されています。

本モジュールは「グラフィックライブラリの使い方を理解して液晶モジュールを駆動出来る人」をターゲットにしております。


# <span style="color: red;">注意！！（必ずお読み下さい）</span>

本品は基本的な電子回路の仕組みを理解した方を対象とした、電子部品がむき出しの半完成キットです。
電子部品は電源電圧や極性を間違えたり、部品を破損させたり部品端子をショートさせた場合、発熱・発煙・発火に至る場合もあります。
間違った使い方をすると危険である事を理解された方のみご使用ください。
趣味の電子工作向けに製作しておりますので、製品への組込みや日常生活へ組込んでのご使用はお止め下さい。



# 形状および回路図

以下に外形イメージを示します

![](pcb_image.png)



以下に回路図を示します

![](schematic.png)





# ピンアサイン

XIAO とLCDの制御信号とのピン接続は以下となります。

- SCLK:D8

- MOSI:D10

- DC:D0

- CS:D7

- RST:D1

- バックライト:D2

オマケ回路

- ブザー:D3
- FETドライブ:D9


XIAOの各端子はSMTタイプのピンヘッダが実装できるパットを準備しましたので外部との接続が可能です。



# 使用するツールやライブラリ

XIAOのArduino IDEへのインストールは、以下サイトを参考下さい。

https://wiki.seeedstudio.com/Seeeduino-XIAO/


グラフィックライブラリについては主にlovyan様のLovyanGFXにて動作確認をしています。

https://github.com/lovyan03/LovyanGFX

他、st7789に対応したライブラリが使用可能と考えています。





# LCD表示動画

仮データ

https://youtu.be/RPaXjcNmUY8





# 使用例

準備中





# 製作者

ウルカテクノロジー
Hiroyuki Sunagawa

https://www.facebook.com/URUKA-Technologies-105478404379918
