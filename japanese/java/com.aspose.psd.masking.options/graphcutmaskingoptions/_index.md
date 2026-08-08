---
title: "GraphCutMaskingOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "GraphCut 自動マスキングオプションです。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

GraphCut 自動マスキングオプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | 背景オブジェクト番号 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | セグメンテーションアルゴリズムの引数を取得します。 |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | 背景置換色を取得します。 |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | マスクから各Shapeを個別のオブジェクトとして分離するか、マスク全体を背景から分離した統合オブジェクトとして扱うかを示す値を取得します。 |
| [getExportOptions()](#getExportOptions--) | 画像エクスポートオプションを取得します。 |
| [getFeatheringRadius()](#getFeatheringRadius--) | フェザリング半径を取得します。 |
| [getMaskingArea()](#getMaskingArea--) | マスク領域を取得します。 |
| [getMethod()](#getMethod--) | セグメンテーション方法を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | セグメンテーションアルゴリズムの引数を設定します。 |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | 背景置換色を設定します。 |
| [setDecompose(boolean value)](#setDecompose-boolean-) | マスクから各シェイプを個別オブジェクトとして分離するか、背景から分離されたマスクの統合オブジェクトとして分離するかを示す値を設定します。 |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | 画像エクスポートオプションを設定します。 |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | フェザリング半径を設定します。 |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | マスク領域を設定します。 |
| [setMethod(int value)](#setMethod-int-) | セグメンテーション方法を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


背景オブジェクト番号

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


セグメンテーションアルゴリズムの引数を取得します。

値: セグメンテーションアルゴリズムの引数。

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


背景置換色を取得します。

値: 背景置換色。この色は生成された画像の背景色として使用されます。

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


マスクから各Shapeを個別のオブジェクトとして分離するか、マスク全体を背景から分離した統合オブジェクトとして扱うかを示す値を取得します。

値: 分解する場合は true、そうでない場合は false。

**Returns:**
boolean - マスクから各シェイプを個別オブジェクトとして分離するか、背景から分離されたマスクの統合オブジェクトとして分離するかを示す値。
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


画像エクスポートオプションを取得します。

値: 生成された画像を作成するために使用される画像エクスポートオプション。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


フェザリング半径を取得します。

**Returns:**
int - フェザー半径です。
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


マスク領域を取得します。

値: ソース画像の一部領域であるマスク領域。Rectangle.Empty の値はソース画像全体領域を意味します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


セグメンテーション方法を取得します。

値: セグメンテーション方法。

**Returns:**
int - セグメンテーション方法。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


セグメンテーションアルゴリズムの引数を設定します。

値: セグメンテーションアルゴリズムの引数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | セグメンテーションアルゴリズムの引数。 |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


背景置換色を設定します。

値: 背景置換色。この色は生成された画像の背景色として使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 背景置換色。 |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


マスクから各シェイプを個別オブジェクトとして分離するか、背景から分離されたマスクの統合オブジェクトとして分離するかを示す値を設定します。

値: 分解する場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | マスクから各シェイプを個別オブジェクトとして分離するか、背景から分離されたマスクの統合オブジェクトとして分離するかを示す値。 |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


画像エクスポートオプションを設定します。

値: 生成された画像を作成するために使用される画像エクスポートオプション。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像エクスポートオプション。 |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


フェザリング半径を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | フェザー半径です。 |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


マスク領域を設定します。

値: ソース画像の一部領域であるマスク領域。Rectangle.Empty の値はソース画像全体領域を意味します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | マスク領域。 |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


セグメンテーション方法を設定します。

値: セグメンテーション方法。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | セグメンテーション方法。 |

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

