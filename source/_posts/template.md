---
title: 模板語言的疑惑
date: 2016-09-11 23:17:47
tags:
---
React 好像持續成為前端視圖框架的主流（至少是最受關注的），據說也是現在找工作常被問到的一種加分技能，使用 Meteor 範例教學摸了半小時，非常疑惑。

<!-- more -->

將前端以「元件（component）」的層級架構拆分，感覺還不錯；單向資料更新的簡單化也似乎減少了一些麻煩。但所有東西通通使用 JS 撰寫，甚至把 HTML 模板都用 JSX 寫進去，實在是非常不習慣。

幾乎現在既存的模板語言，包含 Meteor 自己的 Blaze UI，都是標準的三層架構：用 HTML 寫框，CSS 設計視覺呈現，JS 處理邏輯。框模板裡會有一些方便的語法，例如簡單取資料的遞迴，在 React 裡就連這最簡單的邏輯也得自己撰寫。

當然這不是從「程式設計」的角度出發，而是在想，對「進階的內容生產者」來說，哪一種模式比較合適？

參考：

- [Storybook 2](https://voice.kadira.io/releasing-storybook-2-63bf4837f34f)
- [從零開始學 ReactJS（ReactJS 101）](https://www.gitbook.com/book/kdchang/react101/details)