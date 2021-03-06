# Simple缠论量化工具集

## 简介

​	缠论只是一个工具，请不要将它神化，发现一些客观的规律远比追求虚无缥缈的神论更有意义。

​	本模型按照简单可控的方式实现，与原著的描述不尽相同，为了模型可推导做了一些调整，模型整体按照零参数设计，不必关注策略应该设置定什么参数，是否过度拟合等问题。

​	缠论是一种结构化分析方法，但每个人对于缠论的理解不同，如果有计算机基础，每个人量化的缠论模型也不会完全一致，所以没必要过多纠结是否与自己的实现方式一样，学缠的人一旦纠于细节，理论化、精度化、完美化，基本也就缠进去了。从另一个角度说，缠论是一种视觉体现，是对市场阶段性顶底和交易密集区的量化展示，本模型重在交易，在保证无任何未来函数上实现了实时模型，如果仔细观察最后一个笔和线段是动态的，随着行情的变化而变化，但是确认了的构件是不会改变的，这就保证了回测的稳定性，在本模型基础上按照规则开发出的策略没有任何漂移。

​	开源本模型，提供一种无参的量化实现，爱好者可以继续摸索，形成自己一套技术分析体系。在市场上仅仅懂得技术分析是远远不够的，但是作为散户，没有精力读研报做调研，技术分析仍是一种有效的市场解读方法。技术分析体系的建立意味着面对杂乱无章的市场，你有了自己的解读语言，可以与之对话、交流、提升，进一步可以形成一套交易策略，知道自己在自己的体系下什么情况亏什么时候赚，在概率基础上可以形成持久的可调整的交易框架。希望可以帮助各位找到自己的方法论。


![上证指数](https://user-images.githubusercontent.com/104715342/166645675-89aff9e2-826d-47a8-aef6-2e3200098f2a.png)

演示地址：http://simple-trade.cn:18188/  账户：guest/1


## 概览图

本项目基本实现了缠论模型计算、可视化、选股、策略模板等功能，部分功能仍在开发中。

![量化架构-逻辑架构](https://user-images.githubusercontent.com/104715342/166646137-5af0371d-3e2a-4776-86db-10450d251879.png)

## 安装
pip install simple-czsc==0.1.0

## 策略及选股参考Demo
https://github.com/simple-trade/simple-czsc-demo

## 交流
![WechatIMG9](https://user-images.githubusercontent.com/104715342/166646837-8c63702f-518a-463e-99af-c5c2c832cd5c.jpeg)





