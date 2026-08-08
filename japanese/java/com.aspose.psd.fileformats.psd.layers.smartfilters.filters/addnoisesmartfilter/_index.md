---
title: "AddNoiseSmartFilter"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "AddNoise スマートフィルターです。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

AddNoise スマートフィルターです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | 新しい [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [FilterType](#FilterType) | 現在のスマートフィルターの識別子です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | 現在のフィルタを入力の RasterImage 画像に適用します。 |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | 現在のフィルタを入力の [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) マスクデータに適用します。 |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | 現在のインスタンスのメンバ単位のクローンを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | ノイズ値の量を取得または設定します。 |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | ノイズフィルターの分布を取得または設定します。 |
| [getFilterId()](#getFilterId--) | スマートフィルタのタイプ識別子を取得します。 |
| [getName()](#getName--) | スマートフィルタの名前を取得します。 |
| [getOpacity()](#getOpacity--) | スマートフィルタの不透明度の値を取得または設定します。 |
| [getSourceDescriptor()](#getSourceDescriptor--) | スマートフィルタデータを含むソース記述子構造です。 |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | スマートフィルタの有効状態を取得または設定します。 |
| [isMonochromatic()](#isMonochromatic--) | 単色の値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | ノイズ値の量を取得または設定します。 |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setDistribution(int value)](#setDistribution-int-) | ノイズフィルターの分布を取得または設定します。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | スマートフィルタの有効状態を取得または設定します。 |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | 単色の値を取得または設定します。 |
| [setOpacity(double value)](#setOpacity-double-) | スマートフィルタの不透明度の値を取得または設定します。 |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | スマートフィルタ情報を [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) データに保存し、返します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


新しい [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) クラスのインスタンスを初期化します。

### FilterType {#FilterType}
```
public static final int FilterType
```


現在のスマートフィルターの識別子です。

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

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


ノイズ値の量を取得または設定します。

**Returns:**
double
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
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


ノイズフィルターの分布を取得または設定します。

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


スマートフィルタのタイプ識別子を取得します。

**Returns:**
int
### getName() {#getName--}
```
public String getName()
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
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


単色の値を取得または設定します。

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




### setAmountNoise(double value) {#setAmountNoise-double-}
```
public final void setAmountNoise(double value)
```


ノイズ値の量を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


ブレンドモードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


ノイズフィルターの分布を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


スマートフィルタの有効状態を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


単色の値を取得または設定します。

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

