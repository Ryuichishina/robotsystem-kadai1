# robotsystem-kadai1

このプログラムは、LEDを発光させるものです。

# 使用するもの

・Raspberry Pi 4 Computer Model B 4GB　

・抵抗(150Ω)　　　　1本    

・LED　　　　　　　1本   

・電子基盤　　　　　1個 

・ジャンパー線　　　2本

・USBコード（Type-C）　　1本

# 繋げ方

![1](https://user-images.githubusercontent.com/95426761/148651410-f9a84966-409b-4f73-befb-12a357b52c5c.jpg)基盤写真(GPIO 25ピン→抵抗→LED→GND)
![1](https://user-images.githubusercontent.com/95426761/148651555-baf01649-c5a6-4bfa-8387-1535d9bde0d3.jpg)Raspberryの写真(グレーがGPIO25ピン、紫がGNDに接続しています)



# 使用方法
①コードを入力

②＄sudo insmod myled.ko

③$ sudo chmod 666 /dev/myled0

④$ echo 1 > /dev/myled0
　//これによりLEDが着きます
 
⑤$ echo 0 > /dev/myled0
　//これによりLEDが消えます

# 実行動画　
https://youtu.be/Pbw2TQ349b0



