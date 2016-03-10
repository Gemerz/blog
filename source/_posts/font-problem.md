title: 前端開發時,字體下多端多环境顯示選擇
date: 2016-03-10 22:34:21
author: Gemer
categories:
- css
tags: [css,fonts]

--------

在國內前端中,我比較欣賞的字體選擇,我是比較欣賞,sofish的[type.css](https://github.com/sofish/typo.css "type.css")和lepture的[yue.css](https://github.com/lepture/yue.css/blob/master/yue.css "yue.css") 两者都在跨平台做得不错.先看下他们的关于字体的处理.  

### type.css的font处理:

``` bash
  font: 300 1em/1.8 PingFang SC, Lantinghei SC, Microsoft Yahei, Hiragino Sans GB,
        Microsoft Sans Serif, WenQuanYi Micro Hei, sans;
```


### yue.css的font处理:

``` bash
  font: 400 18px/1.62 "Georgia", "Xin Gothic", "Hiragino Sans GB", "Droid Sans Fallback",
   "Microsoft YaHei", sans-serif;

```

type.css在標準網頁端和移動端都相對標準,1em的字體(相當於16px),1.8行距,而yue.css在文字上向在繁體與字體顯得更大.更好看.所以簡書也用這個設置.  
但可以說兩者在簡體上和osx平臺都相當不錯的選擇,但在繁體下.yue相對type的選擇好相對好些.但我發現,並不那些完美.特別是IE11下.出現許多問題.