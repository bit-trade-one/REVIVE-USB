# ファイルリスト

 - Revive_USB_CT_V130.exe(通常版)
 - REVIVE_USB_MATRIX_CT.exe(マトリックス版)

## ushui殿作成FW・設定ツールのご紹介  
こちらよりDLください。  
https://github.com/ushui/REVIVE_USB_RENC_Debounce  
 - REVIVE_USB_RENC_Debounce_latest.zip(エンコーダ対応版)  
追加機能  
---入力のチャタリング設定機能の追加  
---サンプリング周期：入力周期の設定  
---一致検出回数：何回一致したら入力とするかの設定  
---ロータリーエンコーダー設定機能の追加  
---ペア設定：どのピンでロータリーエンコーダーを接続して使用するかの設定  
---一致検出回数：何回一致したら入力とするかの設定  
 
# REVIVE USB Configuration Toolの使い方

## 1. 概要

ここでは、REVIVE USBのピン設定ツール、REVIVE USB, Configuration Toolの使い方を紹介します。  
REVIVE USB, Configuration Toolを用いると、各ピンに「マウス」「キーボード」「ジョイパッド」のキーを様々な組み合わせで登録する事が出来ます。  
Configuration Toolを用いて行った設定はREVIVE USBのチップの中に記憶されます。  
以後はConfiguration Toolを立ち上げる事無く動作します。（常駐ソフトも必要無し）  

## 2. 設定方法

### 2.1 REVIVE USBの立ち上げ

REVIVE USB, Configuration Toolを立ち上げ、REVIVE USBを接続すると、自動的にデバイスが認識され、以下の様な画面となります。  
![](https://lh6.googleusercontent.com/li3BnWSCqTS_B3_ZmOh8z4FZYgbxWEKOpqTLYWl6ZiJWaeauTL0bK-nqGzD93qpdKG0f6m63DbKpYXGnxLui7rz6RzC687HpFbVVSIRakunJj5vyqHEge4w8)  
デバイスが認識されていないと、以下の画面となります。  
![](https://lh6.googleusercontent.com/11NaX34EBSxdQvyBctX4zwhNCsgsrADqhvUkWAUyOawUZ6Y2DWAzq89EYOvZGYn4S4h4sfC62w08P97P5bI9WD1Vfh_4xtpD_DIbkVX4LVkvWOtEttpnUE-T)  
各画面の情報は以下のとおりです。  
![](https://lh4.googleusercontent.com/vJYv8hhFh82GTmLzcqYKbJQRblYZrfmyJhofOyT59u6ycKakYlfeU0fUWvhwtinUvzlibs6PYky0SGMgIMqVusTZXYDfO6G5axmo0I79Wrh88npcUvlzJkMF)  
### 2.2 設定順序

設定は以下の順番で行ないます。  

    1. 設定するピンを選ぶ  
    2. デバイスタイプを選ぶ  
    3. 割当てを選ぶ  
    4. 「設定」ボタンを押す  

これを全てのピンに対して行っていきます。  

### 2.3 設定するピン番号の選択

まず、設定するピンを選びます。  
ピンは以下の選び方が出来ます。  
![](https://lh6.googleusercontent.com/g35vWL1eARPBdL8Rx3-Zp3u6KWDvDTFQYMzsU5mcJv4B_e6Oo0XX0Nut5H2xkxdDukuUaL5XuXpEljRkomdSD-9WrawvUegKaoXpC064rirkFuOgV8Pt28nN)  
### 2.4 デバイスタイプ／割当てを選択  

設定するピンを選んだ後、デバイスタイプ／割当てを選択します。  
デバイスタイプの選択はコンボボックスから行ないます。  

#### 2.4.1 マウス

マウスは以下の割当てから選ぶ事が出来ます。

 - 左クリック
 - 右クリック
 - ホイールクリック
 - 上移動
 - 下移動
 - 左移動
 - 右移動
 - ホイール上
 - ホイール下
 - カーソル速度変更

##### 2.4.1.1 左クリック

左クリックに割当てられたピンがONになると、マウスの左クリックが押されます。  

##### 2.4.1.2 右クリック

右クリックに割当てられたピンがONになると、マウスの右クリックが押されます。  

##### 2.4.1.3 ホイールクリック

ホイールクリックに割当てられたピンがONになると、マウスのホイール（真ん中ボタン）が押されます。  

##### 2.4.1.4 上移動／下移動／左移動／右移動

各移動に割当てられたピンがONになると、マウスカーソルが設定した方向に移動します。  
マウスカーソルのスピードは「移動速度」で設定出来ます。デフォルトは50で、1～255の範囲で設定し、値が小さい程カーソル速度は遅く、値が大きいほどカーソル速度は早くなります。  
![](https://lh6.googleusercontent.com/P7Hq5VtS8CqRuenw9ByTR8tfJozjr2tkxBOzaxDmz2vGtxPfr7J70xF7jlEBku4qAVE3IX155t3ziDHX88JKNwHl3zkEB3_dkNJMHNwgLTXHPJcO3I0--nBS)  

##### 2.4.1.5 ホイール上／ホイール下

各ホイールに割当てられたピンがONになると、マウスのホイールを上または下に回したのと同じ動作をします。  
ホイールの速度は「移動速度」で設定出来ます。デフォルトは50で、1～255の範囲で設定し、値が小さいほど、ホイール速度は遅く、値が大きいほどホイール速度は早くなります。  

##### 2.4.1.6 カーソル速度変更

カーソル速度変更に割当てられたピンがONになると、上移動／下移動／左移動／右移動のカーソル速度がこのピンに設定された値に変更されます。  
この変更は、このボタンが押されている間のみ、有効になります。  
01ピンにカーソル左移動を移動速度50で、02ピンにカーソル速度変更を移動速度100で設定すると、01ピンだけを押した場合には左に速度50で、02ピンを押しながら01ピンを押した場合には速度が100になります。  

#### 2.4.2 キーボード

割当てのCtrl／Shift／Alt／Winのチェックボックスにチェックを入れ、「ここに入力」の所でキーを入力し、設定すると、ピンにその動作が割当てられます。  
![](https://lh3.googleusercontent.com/AMDqYjLxhnA7K00yqyEIrQ663Q1lLc_5SfTl-sWraf_RRTZe_5jxAWBy6w5E_-IK2tzkEAK7-jQ44CufprtgvVdZsl4TCW4sfEwIML7PdU0LDioaf6KkTeHf)  
例えば、「CTRL + ALT + DEL」を設定したい場合には、[Ctrl]と[Alt]にチェックを入れ、「ここに入力」の所で「Delキー」を押し、「設定」を押します。  
そのピンがONになると、CTRL + ALT + DELが押されます。  

#### 2.4.3 ジョイパッド

レバー上下左右／ボタン1～12の中からそのピンに対応させたい物を選んでチェックを入れます。  
チェックを入れたもの全てが反応する様になります。  
例えば、「ボタン１」と「ボタン３」にチェックを入れた場合、そのピンをONにすると、「ボタン１／３」が同時におされます。  
![](https://lh4.googleusercontent.com/MySjBWVSyV3m4A7lQW4NOV5bz-Cn9Jsq66AgiclFI44m9CeVGcrf5BLO4NCr-pjm2VMuyUrKYuFYVhnNWg21SvRX037K3GxGAwf7s5AO6TSOMapCmlFgfQUw)  
