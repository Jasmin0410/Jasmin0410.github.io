---
title: 【JS】ScrollBy & ScrollTo
description: 最近做了一個滾動列表功能，來記錄一下使用的 JS 語法
date: '2023-06-06T11:09:43.836Z'
categories: 
  - 前端筆記
  - JavaScript
tag: 
  - 前端筆記
  - JavaScript
  - scrollby
  - scrollto
slug: /@wow92716/js-note/js-scrollby-scrollto
---

![](img/2023/06-06/cover.jpeg)

最近做了一個滾動列表功能
來記錄一下語法～

<br/>

## ScrollBy
>滾動多少位置

``` JS
scrollBy(x-coord, y-coord)  
scrollBy(options)
```

<br/>

![](img/2023/06-06/scroll-by.gif)

<br/>

## ScrollTo
>滾動到指定的位置

``` JS
scrollTo(x-coord, y-coord)  
scrollTo(options)
```

<br/>

![](img/2023/06-06/scroll-to.gif)

<br/>

## Options 的寫法
> 如果 top 值為負數代表內容向下滾動；而 left 為負數則是內容向右滾動


``` JS
scrollBy / scrollTo  
({  
  top: 0,  
  left: 100,  
  behavior: "smooth" (平滑) / "instant" (瞬間) / "auto" (看瀏覽器)  
})
```

<br/>
<br/>
          
最後，附上 codepan 範例供參考

{% iframe https://codepen.io/jasmin0410/embed/jOQNjvX?default-tab=html%2Cresult?height=265&theme-id=dark&default-tab=html,result %}


