+++
date = '2025-12-07T18:43:26+09:00'
draft = false
title = 'Matplotlib'
categories = ["Python"]
tags = []
+++


# Matplotlib備忘録


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



適宜更新します。
