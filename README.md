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

https://mail.google.com/mail/u/1/#drafts?projector=1

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



