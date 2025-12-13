+++
date = '2025-12-07T18:43:26+09:00'
draft = false
title = 'Matplotlib備忘録'
categories = ["データ解析"]
tags = ["Python"]
+++

## フォントの設定

論文の図では基本的にArialを使用すればOK。

```
plt.rcParams['font.family']= 'sans-serif'
plt.rcParams['font.sans-serif'] = ['Arial']
plt.rcParams['font.size'] = 16
```

## 解像度の設定

```
plt.rcParams["figure.dpi"] = 200
```

## 枠線の除去

```
# implicit interfaceの場合
plt.gca().spines['right'].set_visible(False)
plt.gca().spines['top'].set_visible(False)

# explicit object-oriented (OO) interfaceの場合
fig, ax = ~
ax.spines["left"].set_visible(False)
ax.spines["bottom"].set_visible(False)
```


適宜更新します。
