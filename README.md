IchigoDotS
==========
yhironaka@gmail.com 廣中靖久

LPC1114を利用して作成できるワンキーゲーム機、IchigoDotのファームウェアをforkして、機能追加しています。
主に、シリアルI/F (uart)経由で表示を制御できるようにする、といった機能追加がメインです。
空中配線で制作すると、たいへん安上がりです。

### 主な用途

* おみくじ、連打ゲーム、10秒当てゲーム、といったアプリケーションで遊ぶ
* シリアルから流し込んだデータを字幕状に表示する  
　その際、IchigoDotを数珠つなぎにすることで、長い流れる文字表示ができます。
* 8x8で64個のLED表示状態をメモリし、アニメーション表示できます。

その他、徐々に機能を拡張したいと思います。

### 以下、taisukefさんが開発したIchigoDotのREADME.mdです。

IchigoDot
=========

a One Key Game Machine for LPC1114

see http://fukuno.jig.jp/881
