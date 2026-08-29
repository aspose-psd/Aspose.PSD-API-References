---
title: "IOrderedShape"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "順序付けられた形状を表します。"
type: docs
weight: 129
url: /ja/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

順序付けられたシェイプを表します。順序付けられたシェイプは、開始点と終了点を持つ連続した点の集合です。特定の規則を使用して接続された連続点の集合です。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | 終了シェイプ点を取得します。 |
| [getStartPoint()](#getStartPoint--) | 開始シェイプ点を取得します。 |
| [isClosed()](#isClosed--) | 順序付けられたシェイプが閉じているかどうかを示す値を取得します。 |
| [reverse()](#reverse--) | このシェイプの点の順序を逆にします。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 順序付けられたシェイプが閉じているかどうかを示す値を設定します。 |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


終了シェイプ点を取得します。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


開始シェイプ点を取得します。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


順序付けられたシェイプが閉じているかどうかを示す値を取得します。閉じた順序付けシェイプを処理する場合、開始点と終了点は意味を持ちません。

**Returns:**
boolean - この順序付けシェイプが閉じている場合は true、そうでない場合は false。
### reverse() {#reverse--}
```
public abstract void reverse()
```


このシェイプの点の順序を逆にします。

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


順序付けられたシェイプが閉じているかどうかを示す値を設定します。閉じた順序付けシェイプを処理する場合、開始点と終了点は意味を持ちません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | この順序付けシェイプが閉じている場合は true、そうでない場合は false。 |

