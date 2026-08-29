---
title: "IPathShape"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ベジェ曲線のノットからなるシェイプです。"
type: docs
weight: 31
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

ベジェ曲線のノットからなるシェイプです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getItems()](#getItems--) | Bezierノットの配列を取得します。 |
| [getPathOperations()](#getPathOperations--) | パス形状の結合（ブール演算）に関する操作です。 |
| [isClosed()](#isClosed--) | シェイプが閉じているかどうかを決定するプロパティを取得または設定します。 |
| [setClosed(boolean value)](#setClosed-boolean-) | シェイプが閉じているかどうかを決定するプロパティを取得または設定します。 |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bexierノットの配列を割り当てます。 |
| [setPathOperations(int value)](#setPathOperations-int-) | パス形状の結合（ブール演算）に関する操作です。 |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Bezierノットの配列を取得します。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord の配列。
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


パス形状の結合（ブール演算）に関する操作です。

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


シェイプが閉じているかどうかを決定するプロパティを取得または設定します。

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


シェイプが閉じているかどうかを決定するプロパティを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Bexierノットの配列を割り当てます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezierノットの配列 |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


パス形状の結合（ブール演算）に関する操作です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

