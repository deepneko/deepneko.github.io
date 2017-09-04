---
layout: post
title: 移動平均の傾きの移動平均
tag: metatrader
date: 2014-11-30 13:01:34
---

ややこしいタイトルだが、(5日/50日の移動平均の傾き)の移動平均について  
クロス交差法で売買してみた。  
短期の傾きの正負が逆転したら手仕舞。  

USDJPY 5年分(2009/10-2014/10)  
利食い 500, 損切り 1000, スプレッド 10で固定  

インディケーターつくって眺めてみて、この条件が良さそうだなーと思ったんだが  
まぁ、普通に移動平均だけで売買したほうが良いですね。

#### 日足
![日足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_D1.gif)  
  
#### 4時間足
![4時間足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_H4.gif)  

#### 1時間足
PF 1.11, Drawdown 6.77%  
![1時間足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_H1.gif)  

#### 30分足
![30分足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_M30.gif)  

#### 15分足
![15分足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_M15.gif)  

#### 5分足
![5分足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_M5.gif)  

#### 1分足
![1分足]({{ site.url }}/assets/ma_inclination_cross/MA_Inclination_Cross_ma_inclination_cross_USDJPY_M1.gif)  
