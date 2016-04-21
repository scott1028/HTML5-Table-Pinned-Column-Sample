#### Design

```
請不要用左右兩側 scrollTop offset 用 javascript 同步，Zoom 會有左右不對齊的 Bug。請改用 "右側 scrollTop" 去 Update "左側 top: -x - $(header_height) px"。
```

![Alt text](https://raw.githubusercontent.com/scott1028/HTML5-Table-Pinned-Column-Sample/master/sample01.jpg "sample01")

