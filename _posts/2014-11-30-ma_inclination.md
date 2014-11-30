---
layout: post
title: 移動平均の傾き
tag: metatrader
date: 2014-11-30 11:59:00
---

100日移動平均の傾きが正負逆転したところで売買するという  
シンプルなプログラムを作ってみた。  
手仕舞も正負逆転したとき。  

USDJPY 5年分(2009/10-2014/10)  
利食い 1000, 損切り 1000, スプレッド 10で固定  

売買頻度は悪くないが、対して利益もないし
そのうえスーパー不安定だな...

#### 日足
![日足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_D1.gif)  
  
#### 4時間足
![4時間足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_H4.gif)  

#### 1時間足
PF 1.06, Drawdown 5.76%  
![1時間足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_H1.gif)  

#### 30分足
![30分足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_M30.gif)  

#### 15分足
PF 1.08, Drawdown 14.36%  
![15分足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_M15.gif)  

#### 5分足
![5分足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_M5.gif)  

#### 1分足
![1分足]({{ site.url }}/assets/ma_inclination/MA_inclination_ma_inclination_USDJPY_M1.gif)  
