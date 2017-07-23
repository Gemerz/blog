title: 前端開發時,字體下多端多环境顯示選擇
date: 2016-03-10
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

在windows中，特別是繁體網頁中，建議還是做一個關於平臺 css flag，繁體下windows 最優選擇是微軟正黑體 `Microsoft JhengHei`，但假如用繁體環境去看解析簡體，又要出現各中字符不一。所以做好每個語言加flag是最好的選擇。

在處理日文方面，也不是用通用的字體，因在windows那字體真不好。建議用：因為：`ヒラギノ角ゴ Pro W3`,算是日文能行處理比較好。
``` bash
 font-family: "ヒラギノ角ゴ Pro W3", "Hiragino Kaku Gothic Pro", "メイリオ", Meiryo, Osaka, "ＭＳ Ｐゴシック", "MS PGothic", sans-serif;

```
在處理葡萄牙语歐美系，用 `Helvetica Neue` 會比較好。在處理韓國等選擇方些的字體會比較優勢，建議用 `pt sans` google fonts有。

至於其他語系字體最優化選擇還是更多了解。

<br>
<br>
<br>




