# ロボットシステム学課題１
２つのLEDが点灯、消灯します。

## 使用するもの　　
・Raspberry Pi 3 Model B  
・LED  
・抵抗(220Ω)  
・ジャンパー線  
・ブレッドボード  

## 動作手順
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
