# ロボットシステム学課題１
２つのLEDが点灯、消灯します。

## 使用するもの　　
・Raspberry Pi 3 Model B  
・LED×2  
・抵抗(220Ω)×2  
・ジャンパー線×4  
・ブレッドボード  

## 動画  
[https://youtu.be/4kyXL1OSse8](https://youtu.be/4kyXL1OSse8)  

## 回路
![回路図写真](https://photos.app.goo.gl/wmzRT4B32wVWvh1JA)  
GPIO24.25とLEDを接続しています。  

## 動作手順  
初めに以下のコマンドを実行します。  
```$ git clone https://github.com/kokikubo/homework1.git```  
```$ cd myled```  
```$ make```  
```$ sudo insmod myled.ko```  
```$ sudo chmod 666 /dev/myled0```  

LED1の点灯  
```$ echo 1 > /dev/myled0```  
LED1の消灯  
```$ echo 0 > /dev/myled0```  
LED2の点灯  
```$ echo 3 > /dev/myled0```  
LED2の消灯  
```$ echo 2 > /dev/myled0```  

## ライセンス  
GNU General Public License v3.0
