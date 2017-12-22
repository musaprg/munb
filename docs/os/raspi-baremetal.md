# Raspi3でのベアメタル関連情報メモ

## RaspberryPi仕様

### Raspberry Pi 2 Model B v1.2（UD-RP2）

http://www.iodata.jp/product/pc/raspberrypi/ud-rp2/spec.htm

|項目||
|---|---|
|CPU|Broadcom BCM2837<br>900MHz 64-bit quad-core ARMv8 Cortex-A53|
|メモリ|1GB|

### Raspberry Pi 3 Model B (UD-RP3)

http://www.iodata.jp/product/pc/raspberrypi/ud-rp3/spec.htm

|項目||
|---|---|
|CPU|Broadcom BCM2837<br>1.2GHz 64-bit quad-core ARMv8 Cortex-A53|
|メモリ|1GB|

## RasPiのブートプロセス等について

## ブートプロセス

https://www.raspberrypi.org/forums/viewtopic.php?f=63&t=6685

### config.txt

RasPiはBIOSを持たないため、ブート時の挙動については`config.txt`の記述によって決定する。

config.txtについての詳しいことについては、以下のサイトが非常に見やすい。

[RPiconfig](https://elinux.org/RPiconfig)

また、公式ドキュメントも存在する。

## 開発環境

### クロスコンパイラ

[GNU ARM Embedded Toolchain](https://launchpad.net/gcc-arm-embedded)

[Ubuntuにおける環境構築方法](http://dev.toppers.jp/trac_user/ev3pf/wiki/DevEnvLinux)

## リンク集

### 公式ドキュメント

### ブログ等

[ラズパイ3でベアメタル - その1:何もしない無限ループプログラム](http://d.hatena.ne.jp/cupnes/20160514/1463238354)

[RaspberryPiのVideoCore IV(GPU)を使ってOS無し(ベアメタル)からポリゴン出して遊ぶ](https://qiita.com/gyabo/items/f3a411a63d608d00b384)

[RaspberryPi3 64bitモード ベアメタルをJTAGデバッグする](https://qiita.com/toshinaga/items/146bcb00db235258162f)

[EclipseとOpenOCDでSTM32(ARM)マイコン開発](https://qiita.com/Ted-HM/items/760759b6b152230b48a8)
