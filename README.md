![main](images/thumbnail.jpg?raw=true)

# はじめに

この度は、「わんわんわんきーぼーど」をお買い上げいただきまして誠にありがとうございます。  
この製品は *100%キーボード* と言われるフルサイズの自作キーボードです。    
`わんわんわん` → `111` ということで *111キー* までキー数の拡張が可能な特徴となっています。

ファームウェアについては [QMK Firmware](https://github.com/qmk/qmk_firmware) を採用しており、ご購入者自身で各キー割り当てを変更することが出来ます。

本製品は組み立てが必要なキットです。  
組立工程の中には、ハンダ付けや細いねじを締める工程があります。  
あらかじめ必要な工具（後述）を用意した上で、組立を始めてください。

また、本製品には含まれていないもので必要なものがございます、必要なパーツを確認の上ご自身でお好みのものを別途揃えてください。

# 目次

- [必要な工具](README.md#%E5%BF%85%E8%A6%81%E3%81%AA%E5%B7%A5%E5%85%B7)
- [本製品に含まれるパーツ一覧](README.md#%E6%9C%AC%E8%A3%BD%E5%93%81%E3%81%AB%E5%90%AB%E3%81%BE%E3%82%8C%E3%82%8B%E3%83%91%E3%83%BC%E3%83%84%E4%B8%80%E8%A6%A7)
- [本製品に含まれていない必要なパーツ一覧と主な購入先](README.md#%E6%9C%AC%E8%A3%BD%E5%93%81%E3%81%AB%E5%90%AB%E3%81%BE%E3%82%8C%E3%81%A6%E3%81%84%E3%81%AA%E3%81%84%E5%BF%85%E8%A6%81%E3%81%AA%E3%83%91%E3%83%BC%E3%83%84%E4%B8%80%E8%A6%A7%E3%81%A8%E4%B8%BB%E3%81%AA%E8%B3%BC%E5%85%A5%E5%85%88)
- [本体の組み立て](README.md#%E6%9C%AC%E4%BD%93%E3%81%AE%E7%B5%84%E3%81%BF%E7%AB%8B%E3%81%A6)
- [基本ファームウェアの書き込み](README.md#%E5%9F%BA%E6%9C%AC%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E6%9B%B8%E3%81%8D%E8%BE%BC%E3%81%BF)
- [QMK Configuratorでファームウェアを作る](README.md#qmk-configurator%E3%81%A7%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2%E3%82%92%E4%BD%9C%E3%82%8B)

# 必要な工具
- ハンダゴテ https://www.amazon.co.jp/dp/B006MQD7M4
- コテ台 https://www.amazon.co.jp/dp/B000TGNWCS
- ハンダ https://www.amazon.co.jp/dp/B0029LGAJI
- ピンセット https://www.amazon.co.jp/dp/B002A5VG2E
- ニッパー https://www.amazon.co.jp/dp/B001D7TE2E
- 精密ドライバー https://www.amazon.co.jp/dp/B000CED236
- ワイヤーストリッパー https://www.amazon.co.jp/dp/B004OR7BQ6

## あると便利なもの
- テスタ https://www.amazon.co.jp/dp/B06XPFRCGQ
- ヘッドルーペ https://www.amazon.co.jp/dp/B002T8EXVS
- ハンダ吸い取り線 https://www.amazon.co.jp/dp/B001PR1KPQ

# 本製品に含まれるパーツ一覧

|名前|個数| |
|:-----:|:----:|:----:|
|PCB|1枚|![main](images/0/main1.jpg?raw=true)  ![main](images/0/main2.jpg?raw=true)|
|トッププレート|1枚|![top](images/0/top1.jpg?raw=true)  ![top](images/0/top2.jpg?raw=true)|
|ボトムプレート|1枚|![bottom](images/0/bottom1.jpg?raw=true)  ![bottom](images/0/bottom2.jpg?raw=true)|
|ダイオード|111個|![diode](images/diode.jpg?raw=true)|
|M2 3mm貫通スペーサー|16個|![m-3sp](images/m-3sp.jpg?raw=true)|
|M2 8mmネジ|16本|![m2-8mm](images/m2-8mm.jpg?raw=true)|
|M2 3mmネジ|16本|![image](images/m2-3mm.jpg?raw=true)|
|M2 6mmスペーサー|16個|![image](images/m2-6sp.jpg?raw=true)|
|ゴム足|1セット|![rubber](images/rubber.jpg?raw=true)|
|リセットスイッチ|1個|![reset](images/reset.jpg?raw=true)|

# 本製品に含まれていない必要なパーツ一覧と主な購入先

|名前|個数|入手先| |
|:-----:|:----:|:----:|:----:|
|ProMicro+コンスルー|1セット|遊舎工房( https://yushakobo.jp/shop/promicro-spring-pinheader/ )|![promico](images/promico.jpg?raw=true)|
|MXキースイッチ|104～111個|遊舎工房( https://yushakobo.jp/product-category/switches/ )||
|MXキーキャップ|104～111個|遊舎工房( https://yushakobo.jp/product-category/keycaps/ )||
|（任意）ws2812b|111個|遊舎工房( 実店舗で取り扱い中 )|![ws2812b](images/ws2812b.jpg?raw=true)|
|（任意）ワイヤー5cmぐらい|3本|秋月電子通商( http://akizukidenshi.com/catalog/g/gP-11640/ )| |

# 本体の組み立て

## 0.PCBの見かた（表裏、上下左右）

PCBメイン表

![top](images/0/main1.jpg?raw=true)

PCBメイン裏

![top](images/0/main2.jpg?raw=true)

PCBボトム表

![top](images/0/bottom1.jpg?raw=true)

PCBボトム裏

![top](images/0/bottom2.jpg?raw=true)

このあとの解説はすべて左手用での説明となっています。

## 1. ダイオードを取り付け
ひっくり返す作業が必要となりますのでテープを用意してください。

まず、ダイオードを取り付けていきます。

ダイオードとは、電気の流れの向きを一定にする仕組みのものです。  
水で表現すると水流の向きを制御し、逆向きに水が流れることを防ぎます。

この特徴からダイオードには細い線の印刷がされています。

**逆向きに取り付けてしまうと、そのキーは反応しなくなってしまいます。**

ハンダ付けはダイオードの端に細い線が通っている方と、 
PCB側の `コ` の字型の線がある方を同じ向きに揃えてハンダ付けしていきます。


ダイオードを9mm幅で折り曲げます。  
定規なので図りながらやってもいいですが、 *リードベンダー* という道具を使ったりすると良いでしょう。

![image](images/1/3.jpg?raw=true)

向きを間違えないように基板に刺していきます。  
刺し終わったらひっくり返したときに落ちないよう、テープなどで仮止めします。

![image](images/1/4.jpg?raw=true)

そのままひっくり返し、ニッパーで余分な足を切り取ります。

![image](images/1/5.jpg?raw=true)
![image](images/1/6.jpg?raw=true)

ハンダ付けをして仮止めのテープを外します。

![image](images/1/7.jpg?raw=true)

これを111個繰り返していきます。  
(104キーの場合、D105～D111の箇所のハンダ付けは不要です。付けてもつけてなくても動作には影響しません。)



<strong style="font-size: 200%">TIPS：スルーホールな基板なので表裏の好きな方にハンダ付けできますが、スタビライザーを取り付ける場合は干渉してしまいますので裏側にダイオードが来るようにハンダ付けをすることをおすすめします。</strong>


![image](images/1/1.jpg?raw=true)

![image](images/1/2.jpg?raw=true)




## 2. リセットスイッチの取り付け
次に、リセットスイッチを取り付けます。  
PCBでは表裏どっちでも付けられるようになっていますが、表面につけてしまうとトップが取り付けられなくなってしまいます。  
写真を見ながら、裏面にはんだ付けを行ってください。

![image](images/2/1.jpg?raw=true)

リセットスイッチも同じく先に片足だけ予備ハンダします。
その後、ピンセットを使いながらスイッチの片足をはんだ付けします。  
はんだ付けできたら、もう片足と横の方もしっかりはんだ付けしていきます。

![image](images/2/2.jpg?raw=true)
![image](images/2/3.jpg?raw=true)
![image](images/2/4.jpg?raw=true)

## 3. RGBLEDをつける（オプション）

この作業の必要のない方は [(5. スタビライザーをつける)](README.md#5-%E3%82%B9%E3%82%BF%E3%83%93%E3%83%A9%E3%82%A4%E3%82%B6%E3%83%BC%E3%82%92%E3%81%A4%E3%81%91%E3%82%8B%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3) までの作業を省略してください。

作業を行う前に半田ゴテの温度を230度まで下げます。  
半田ゴテの温度が高い状態で作業するとLEDを熱で破壊してしまう場合があります。  
これを防ぐために、コテ先の温度を下げるのを忘れないように注意してください。

![image](images/3/1.jpg?raw=true)

RGBLEDの切込みと、PCBの枠で囲った位置が合うよう向きを合わせてはんだ付けしていきます。
このとき、ダイオードでやったのと同じで一箇所だけ予備ハンダし、ピンセットを使ってハンダ付けしてください。

***このとき、なるべく慌てず素早く作業しましょう。温度が低くても長時間温め続けてしまうとLEDを破損させる原因となります。***

![image](images/3/2.jpg?raw=true)

![image](images/3/3.jpg?raw=true)

1個RGBLEDをつけるとこのようになります。

![image](images/3/4.jpg?raw=true)

## 4. ボトムプレートとPCBをワイヤーでつなぐ（オプション）

RGBLEDを光らせる電力をボトム基板に送るため  
PCB基板とボトムの基板をワイヤーでつなぎます。

ワイヤーを5cm～7cmぐらいの長さに揃えて切り、両端から３ミリを目安にワイヤーストリッパーなどを使って被覆を剥ぎます。

その後、上から同じ位置に合うようにワイヤーを刺し、はんだ付けします。

□から `VCC,LED,GND` の順になっています。

![image](images/4/1.jpg?raw=true)

## 5. スタビライザーをつける（オプション）

この作業の必要のない方は [(6. トップにキースイッチをはめる)](README.md#6-%E3%83%88%E3%83%83%E3%83%97%E3%81%AB%E3%82%AD%E3%83%BC%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%82%92%E3%81%AF%E3%82%81%E3%82%8B) までの作業を省略してください。

スタビライザーをはめていきます。  
円が大きい方から先にはめて、パチンと音がするまでしっかり小さい方を押し込みます。

この時横から確認してスタビライザーとPCBの隙間がないことを確認してください。

![image](images/5/1.jpg?raw=true)

分割スペースバーにする場合はスペースバーの位置にスタビライザーは不要です。  
1uテンキーにする場合もその箇所にスタビライザーは不要です。

## 6. トップにキースイッチをはめる

向きを確認しながらキースイッチをトップにすべてはめていきます。  
この時通常のスペースバーを使う場合は、5個中真ん中の穴（写真の赤い円）にキースイッチを入れてください。

![image](images/6/1.jpg?raw=true)
![image](images/6/2.jpg?raw=true)

## 7. ネジを付ける
ひっくり返す作業が必要となりますのでテープを用意してください。

トッププレートに `M2 8mmネジ` を16箇所全てのネジ穴に指します。

![image](images/7/1.jpg?raw=true)

その後テープを利用してネジ穴から落ちないようひっくり返します。

![image](images/7/2.jpg?raw=true)

ひっくり返したら、 `M2 3mm 貫通スペーサー` を16箇所と通します。

![image](images/7/3.jpg?raw=true)

その後、PCBを付けて、 `M2 6mm スペーサー` で固定します。
16箇所すべて固定しネジが落ちない状況になったら、仮止めのテープを外ししっかり固定します。

![image](images/7/4.jpg?raw=true)

## 8. キースイッチをはんだ付けする

キースイッチの足と基板をはんだ付けします。  
この時差し込みが甘かったり他のキーをはんだ付けしてるときに傾いてしまったりしたままハンダ付けをしてしまわないよう  
はんだ付けするときにはもう一度ちゃんと奥まで入っているか確認しましょう。

## 9. ProMicroにコンスルーをつける

ProMicroとコンスルーを準備します。
遊舎工房様で購入した場合は、ピンヘッダとコンスルーの両方がついてきます。
そのうち、写真の下側のほうがコンスルーでこちらの方を使っていきます。 (上の方は不要なので破棄するかよしなにしてください)

![image](https://user-images.githubusercontent.com/5952961/59026138-aec00a00-8890-11e9-8fba-5ff7336ee15c.jpg)

ProMicroの部品が実装されている面にコンスルーを差し込みます。
コンスルーの小さな小窓がProMicroに近い側であること、手前奥ともに小窓が見えていることを確認したらひっくり返します。

![image](https://user-images.githubusercontent.com/5952961/59015614-5b42c180-887a-11e9-92bd-fa32baa3fef1.JPG)
![image](https://user-images.githubusercontent.com/5952961/59015616-5da51b80-887a-11e9-8408-a7d9d0e1b51e.JPG)

## 10. PCBにProMicroを取り付ける

この状態でPCBにProMicroを取り付けます。  
12ピンのProMicroに対し13個穴が空いてますが、これはBLEMicroPro用に準備されています。

取り付けるときは白い枠線にピッタリ合うよう、下の線に合わせて取り付けます。

その後もう一度しっかり刺さってるか確認し、 ***ProMicroをはんだ付けします。***

![image](images/10/1.jpg?raw=true)

## 11. ボトムを取り付ける

ボトムプレートをとりつけ `M2 3mm ネジ` で16箇所固定します。

## 12. ゴム足をつける
キーボードと机を保護するためにゴム足を取り付けます。

![image](images/12/1.jpg?raw=true)

## 13. キーキャップを指す

キーキャップを付けていきます。  
つけるキースイッチの種類によって向きがありますので、確認しながら付けましょう。  
キーキャップには十字の切れ込み、キースイッチには十字の軸がついています。  
そちらの向きを確認しながらまっすぐ差し込んでいってください。

![image](images/14/3.jpg?raw=true)
![image](images/14/4.jpg?raw=true)

これで本体は完成です。

# 基本ファームウェアの書き込み

まずは動作確認のため基本ファームウェアを書き込みます。

書き込みには [qmk_toolbox](https://qmk.fm/toolbox/) を使用します。
[こちら](https://github.com/qmk/qmk_toolbox/releases) から最新版をダウンロードし任意の場所に保存します。

次に、[こちら](https://github.com/kakunpc/thedogkeyboard/releases)からファームウェアをダウンロードし任意の場所に保存します。 (thedogkeyboard_default.hex)

その後qmk_toolboxを起動します。

起動したら次のように設定します。

- `Local File` を先程保存したファームウェアを指定します
- `Microcontroller` を `atmega32u4` を指定します。
- `Auto-Flash` にチェックを入れます。

![image](images/qmk_toolbox/1.jpg?raw=true)

準備ができたら、USBでPCと接続します。
その後、リセットスイッチを押してしばらくまちます。

`Thank you.` と画面に出たら完了です。

![image](images/qmk_toolbox/2.jpg?raw=true)

実際にボタンをして正しく動作するか確認しましょう。

# QMK Configuratorでファームウェアを作る

次のリンクからキー配置の割り当てをGUIで設定し、hexファイルを作成することが出来ます。  
https://config.qmk.fm/#/thedogkeyboard/LAYOUT

hexファイルをProMicroに書き込むときは ***[基本ファームウェアの書き込み](README.md#%E5%9F%BA%E6%9C%AC%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E6%9B%B8%E3%81%8D%E8%BE%BC%E3%81%BF)*** を参考にしてください。

QMK Configurator自体の使い方に関してはこちらの動画を参考にしてください。  
基礎からわかる！自キ入門講座 第12回「ファームウェアのカスタマイズ」 - https://www.youtube.com/watch?v=J3Z1LN2ZMu8

