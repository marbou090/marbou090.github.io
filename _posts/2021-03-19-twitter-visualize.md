---
layout: post
title:  "ツイートワードクラウド"
date:   2021-03-19
excerpt: "タイムラインツイートをamCharts.jsを用いて可視化"
project: true
tag:
- product
- Python
- JavaScript
comments: false
---
ツイッターAPIを用いてタイムラインのツイートを取得し、可視化してみました。

## やったこと
+ PythonでTwitterAPIを叩いてタイムラインのツイートを取得
+ mecabを用いて形態素解析を行い名詞のみを抽出し、名詞ごとに出現回数をカウント
+ amCharts(JavaScriptのライブラリ)を用いてワードクラウド表示

## 実際の挙動
文字が良い感じに表示され、定期的に単語が移動しています。単語をクリックするとTwitter上で該当単語をフォロワー内検索して表示されます。

実際に動いている様子は[こちら](https://marbou090.github.io/TwitterTrendsVisualizer/)で見れます。


![image](https://cdn.discordapp.com/attachments/712655088119709716/833357802806181909/2021-04-19_0.06.13.png)
        
