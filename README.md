#### Design

0. 請不要用左右兩側 scrollTop offset 用 javascript 同步，Zoom 會有左右不對齊的 Bug。請改用 "右側 scrollTop" 去 Update "左側 top: -x - $(header_height) px"。
1. 產生一個 4 * 4(左 1w*2h 右 1w*2h) 的樣板，上方兩格放 Header 下方兩格放 Table Data View。讓 下方兩格右側產生 overflow: scroll 產生捲軸，左側用 top Offset 連動！
2. 作為包裹的下方 Table 向上 Offset Top Header 的 Height 並設定為 Absolute Position。

![Alt text](https://raw.githubusercontent.com/scott1028/HTML5-Table-Pinned-Column-Sample/master/sample01.jpg "sample01")
![Alt text](https://raw.githubusercontent.com/scott1028/HTML5-Table-Pinned-Column-Sample/master/sample01.gif "sample01")
