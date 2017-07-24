title: 写个readhub.me的electron版本。
date: 2017-07-23
author: Gemer
categories:
- javascript
tags: [electron]

--------

之前在做一個項目用的就是electron,發現electron前端交互真是方便，不過之前內置go版tts在node，用child press run就可以，結果內存真是顯高，畢竟不是原生的mac os。之前看大輝老師的[readhub.me](http://readhub.me)上線，我算是小道消息的老用戶（只是接收端，低社交人士），發現這個產品真不錯，以前也有個想法用spide去抓。當时腦一熱就用electron＋React+redux+persist寫一個readhub.me的版本叫readhubtron。后来也有人用swift写出来，逻辑差不多。

![alt text](https://download.gemer.xyz/soucre/images/tfc/animation-600.gif "readhubtron")

>  [macOS 版本 v0.1.2](https://download.gemer.xyz/soucre/readhubtron/release/readhubtron-0.1.2.dmg)

>  [windows 版本 v0.1.2](https://download.gemer.xyz/soucre/readhubtron/release/win-unpacked.zip)

## feature

1. *增加 Notifacation.*
2. *增加 推薦閱讀api*
3. *flowType加强检测*
4. *code Sgin for autoupdater*
5. *unit test and pinline test*

## update noted

touchbar在development下可以，可惜production上没支持。

![alt text](https://download.gemer.xyz/soucre/images/blog/readhub_touchbar.jpg "readhubtron")

<br>
<br>

And carry on.







