---
title: "SmartFilter"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "スマートフィルターの基本ロジックを処理するクラスです。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class SmartFilter implements System.ICloneable, Cloneable
```

スマートフィルターの基本ロジックを処理するクラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [SmartFilter()](#SmartFilter--) | 新しい [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | 現在のフィルタを入力の RasterImage 画像に適用します。 |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | 現在のフィルタを入力の [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) マスクデータに適用します。 |
| [deepClone()](#deepClone--) | 現在のインスタンスのメンバ単位のクローンを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | スマートフィルタのタイプ識別子を取得します。 |
| [getName()](#getName--) | スマートフィルタの名前を取得します。 |
| [getOpacity()](#getOpacity--) | スマートフィルタの不透明度の値を取得または設定します。 |
| [getSourceDescriptor()](#getSourceDescriptor--) | スマートフィルタデータを含むソース記述子構造です。 |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | スマートフィルタの有効状態を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | スマートフィルタの有効状態を取得または設定します。 |
| [setOpacity(double value)](#setOpacity-double-) | スマートフィルタの不透明度の値を取得または設定します。 |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | スマートフィルタ情報を [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) データに保存し、返します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartFilter() {#SmartFilter--}
```
public SmartFilter()
```


新しい [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) クラスのインスタンスを初期化します。

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


現在のフィルタを入力の RasterImage 画像に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | ラスタ画像です。 |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


現在のフィルタを入力の [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) マスクデータに適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | マスクデータを持つレイヤーです。 |

### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


現在のインスタンスのメンバ単位のクローンを作成します。

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


ブレンドモードを取得または設定します。

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public abstract int getFilterId()
```


スマートフィルタのタイプ識別子を取得します。

**Returns:**
int
### getName() {#getName--}
```
public abstract String getName()
```


スマートフィルタの名前を取得します。

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


スマートフィルタの不透明度の値を取得または設定します。

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


スマートフィルタデータを含むソース記述子構造です。

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


スマートフィルタの有効状態を取得または設定します。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


ブレンドモードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


スマートフィルタの有効状態を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


スマートフィルタの不透明度の値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


スマートフィルタ情報を [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) データに保存し、返します。

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

