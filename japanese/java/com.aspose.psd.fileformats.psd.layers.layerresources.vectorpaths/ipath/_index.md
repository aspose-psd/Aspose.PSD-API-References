---
title: "IPath"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "インターフェイスは、シェイプレイヤーに存在するパスの集合を記述します。"
type: docs
weight: 30
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipath/
---
```
public interface IPath
```

インターフェイスは、シェイプレイヤーに存在するパスの集合を記述します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getItems()](#getItems--) | Path 内の Shapes の配列を取得します。 |
| [isDisabled()](#isDisabled--) | パスが無効です。 |
| [isInverted()](#isInverted--) | パスが反転しています。 |
| [isNotLinked()](#isNotLinked--) | パスがリンクされていません。 |
| [setDisabled(boolean value)](#setDisabled-boolean-) | パスが無効です。 |
| [setInverted(boolean value)](#setInverted-boolean-) | パスが反転しています。 |
| [setItems(IPathShape[] shapes)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---) | Path 内の Shapes の配列を設定します。 |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | パスがリンクされていません。 |
### getItems() {#getItems--}
```
public abstract IPathShape[] getItems()
```


Path 内の Shapes の配列を取得します。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape[] - IPathShape の配列。
### isDisabled() {#isDisabled--}
```
public abstract boolean isDisabled()
```


パスが無効です。

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public abstract boolean isInverted()
```


パスが反転しています。

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public abstract boolean isNotLinked()
```


パスがリンクされていません。

**Returns:**
boolean
### setDisabled(boolean value) {#setDisabled-boolean-}
```
public abstract void setDisabled(boolean value)
```


パスが無効です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public abstract void setInverted(boolean value)
```


パスが反転しています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setItems(IPathShape[] shapes) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---}
```
public abstract void setItems(IPathShape[] shapes)
```


Path 内の Shapes の配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [IPathShape\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape) | IPathShape の配列。 |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public abstract void setNotLinked(boolean value)
```


パスがリンクされていません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

