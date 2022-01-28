# CH559Pico

<img src="https://github.com/akita11/CH559Pico/blob/main/CH559Pico.png" width="240px">

[WCH(南京沁恒微电子股份有限公司)](http://wch-ic.com/)の8ビットマイコン[CH559](http://wch-ic.com/products/CH559.html)を使った、RaspberryPi Pico型のマイコンボードです。
主な特徴は以下のとおりです。

- RaspberryPi Pico型
- [ArduinoIDEなどでプログラム開発が可能](https://qiita.com/akita11/items/d7baed4ca3c06e292637)
- USBペリフェラル（キーボードやUSBメモリなど）、USBホストとして動作可能

またRaspberryPi Picoとは、以下のような違いがあります。
- 一部ピンの機能が異なる
- +3.3V出力の電流供給能力は100mA程度（CH552内蔵レギュレータの性能）
- リセット(RST)は正論理で、"1"でリセット
- +5V端子に、外部電源から+5Vを供給可能（内部にレギュレータはないので、+5Vを超える電圧は不可）


## ピン配置

<img src="https://github.com/akita11/CH559Pico/blob/main/CH559Pico_pin.png" width="480px">

<img src="https://github.com/akita11/CH559Pico/blob/main/CH559Pico_Back.png" width="240px">

基板上の"LED"（オレンジ）はP1.5で駆動できます。

# 訂正

基板上の2個のシルク表示が逆になっているロットがあります。正しくは、RSTスイッチ側のD2が"LED"（オレンジ）、反対側のD1が"POW"（緑、電源インジケータ）です。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
