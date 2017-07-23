title: 前端，是reactjs還是 vuejs ?
date: 2016-12-30
author: Gemer
categories:
- javascript
tags: [javascript,react,vue]

--------

 <br>
  *只要有人的地方就有恩怨，有恩怨就會有江湖，人就是江湖。--- 金庸*
  <br>
  這段時間前端最熱鬧的事莫過於[阿当老師事件](https://www.zhihu.com/question/53625757) ，關於一片關於前端2016的考察，文中主要觀點是，建議新人關於前端入門更多的是注重的是基礎，寫發jquery和css等，不要去追什麼reactjs和vuejs等新潮的技術，結果引來vuejs作者和同行中許多的各種爭議。

在知乎上，觀點幾乎是一邊倒的，這也無可厚非，這個開倒車的行為有點過失，邏輯存在 `Major Conflict`。

在這個爭議中，引起我的思考的，不是技術的對比，或者雙方論點論據的優越，而是對於前端的認知，一個心理的行為認知。

對於非科班出身的，當初進入編程行，莫過於前端與php的入門，這也是至今說php是最好語言的一個表述，因為當時入門的最容易的就是php+mysql+jquery這一套東西。對於當時只有pc的年代，另一套是java系列。

隨著手機ios和 andirod 以及多端的出現，必然出現更多複雜情況，慢慢出現前後端分離以應對，但是分離後，前端該怎樣了？以往權力是後端控制前端，只是當前端view層面，因為習慣MVC了，但是前端分離出來，在前端不斷完成自我人格的時候，必然同現要權的行為，從angular1開始，就體驗到在views拿到了control和data flow的權力，而且directive的創新概念影響後代的reactjs和vuejs以及ember等主流框架，可以說angular1有著開時代的影響，就如當年的yahoo的Mootools和Prototype。

至於現在前端主流reactjs和vuejs以及jquery之間的區別是什麼，我簡單解析下：

jquery可以說影響前端比較深遠的一個框架，是框架嗎？其實不是，準確是javascript的工具集，在這之前還有Mootools和Prototype等優勢工具集。 為什麼說jquery影響深遠，因為他將native javascript簡單歸納成易用易維護的dom操作，插件plugin易extend和開發，event以及交互上，以及樣式控制。對於當時來說，也存在很大爭議，對於寫習慣原生js的人來，就如今天之爭。

而對於現在初學者來說，怎麼學好reactjs和vuejs？一般入門者都喜歡站隊，其實不必然。因為reactjs和vuejs相似又各不同。

對於reactjs來說，可以說和jquery一樣相當影響，簡單來說，reactjs就如上文所說，現在前端框架是真是框架並不是工作集，例如：

1. 獨立的人格。就如lifecircle生命周期的概念，生命周期就如人一樣，出生，成年，死亡和回收大自然，所以有`componentWillMount`, `componentDidMount`,`componentWillUnmount` 等生命周期階段.

2. 生物信息流。對於state props來說,可以簡單講信息流，就是人一樣的身高，體重，以及dna,fingerprint一樣，就如人的生物信息流，那麼這些信息流會改變或不變嗎？其實不能說去量化這麼信息，reactjs只是記錄這個過程，就如你出生體重到死亡成灰都有一記錄值，就如性別一樣，你一樣可以改，但在更換性別前時就有一個記錄是什麼條件下改變的。

3. 社交記錄。至於`redux`，又是一個什麼概念了？其實簡單來說，各個component之間社交行為紀錄，在沒有 `redux`,reactjs 會將props和state的變化各自記下，就如A借錢到B,B又把錢C，C要還錢還B,B再還給A，但有 `redux`時就可以，C還錢給B， B可設置action在收到C錢時dispatch直接還給A。而且 `redux`的數據是怎麼記錄的？，你可以想像就如圖書館，你每看一本書，就要去借入記一次，歸來記一次，就如會計帳記錄，衝正也是記錄，所有行為可以trace。

4. 自我反復思考糾錯。至於`virtrual dom`又是什麼概念呢？因為javascript 的actural dom是一次渲染出來，以前開發時修過只是通過人工fresh才可看到，而`virtrual dom`只是在真正渲染前用diff算提交一个path的去更新view ，就如一个自我糾錯的行为一样。

以上也是vuejs2改版之後也具有的特性。

兩者有什麼不同？可以講都是人，可以講男女之別。

> reactjs 就像男生一樣，想法多，得想到方方面面，但風氣就如農村的重男輕女，習慣繼承皇位。

> vuejs 就像女生一樣，嬌小，思維直觀，`template` `javascript` `style`， 每個 `componet` 像 derivative 可自義聲明，有點女孩子富養的感覺。對於習慣MVC?思維有一個好的幫助。

那 angular 4呢 angular 2開始 `typescript` 寫，入門門檻更新，也採用新時代特性，習慣 `flowtype`和強類型的前端有了一個更好的選擇。

江湖門派之爭，總有好勝之爭，這是好事。但想成為真正強者，還是知各家所長所短，不然到真正華山論劍之時，不學無術者自然是給淘汰。我的建議，潛力去研究，學其所長。

<br>
<br>
<br>







