---
layout: default
title: らぁらちゃんがGASでTwitterのBotを作る本
---

# らぁらちゃんがGASでTwitterのBotを作る本

![]({{site.github.url}}/assets/hyoshi.png)

## コンテンツ

３章でコピペするソースコードを掲載します．

-----

```javascript
//今日のイベント一覧を取得する処理
function getTodayEvents(){
  const today = new Date();
  const calender = CalendarApp.getDefaultCalendar();
  const events = calender.getEventsForDay(today);
  return events.map(function(e){return e.getTitle()});
}
```

-----

## 概要

らぁらちゃんがGASでTwitterのBotを作る本のページです．

## 正誤表

現在，誤表記は特に見つかっていません．

## ダウンロード

ダウンロードは [こちら](https://taimen.jp/f/586) から

## 連絡先

質問等は

- twitter : @takanakahiko
- mail : takanakahiko@gmail.com

までお願いします．

## 発行

著者 なかひこくん 

- 2018 年 3 月 21 日 初版第 1 刷 発行
- 2018 年 4 月 1 日 第 2 版第 1 刷 発行 