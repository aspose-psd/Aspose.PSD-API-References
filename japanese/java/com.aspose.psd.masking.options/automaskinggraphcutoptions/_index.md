---
title: "AutoMaskingGraphCutOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "GraphCut 自動マスキングオプションです。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

GraphCut 自動マスキングオプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | 新しい [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | 背景オブジェクト番号 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | 自動マスキングの引数を追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | デフォルトのストロークを埋めます。 |
| [getArgs()](#getArgs--) | セグメンテーションアルゴリズムの引数を取得します。 |
| [getAssumedObjects()](#getAssumedObjects--) | 想定オブジェクトを取得します。 |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | 背景置換色を取得します。 |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | デフォルトのストロークを計算すべきかどうかを示す値を取得します。 |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | 結合されたオブジェクトの矩形を取得します。 |
| [getDecompose()](#getDecompose--) | マスクから各Shapeを個別のオブジェクトとして分離するか、マスク全体を背景から分離した統合オブジェクトとして扱うかを示す値を取得します。 |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | デフォルトの背景ストロークを取得します。 |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | 事前計算されたデフォルトの前景ストロークを取得します。 |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | デフォルトのオブジェクト矩形を取得します。 |
| [getExportOptions()](#getExportOptions--) | 画像エクスポートオプションを取得します。 |
| [getFeatheringRadius()](#getFeatheringRadius--) | フェザリング半径を取得します。 |
| [getMaskingArea()](#getMaskingArea--) | マスク領域を取得します。 |
| [getMethod()](#getMethod--) | セグメンテーション方法を取得します。 |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | デフォルトポイントの事前計算プロセスの進行状況イベントハンドラを取得します。 |
| [hasHumans_internalized()](#hasHumans-internalized--) | 想定オブジェクトコレクションに人間オブジェクトが含まれているかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | セグメンテーションアルゴリズムの引数を設定します。 |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | 想定オブジェクトを設定します。 |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | 背景置換色を設定します。 |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | デフォルトのストロークを計算すべきかどうかを示す値を設定します。 |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | 結合されたオブジェクトの矩形。 |
| [setDecompose(boolean value)](#setDecompose-boolean-) | マスクから各シェイプを個別オブジェクトとして分離するか、背景から分離されたマスクの統合オブジェクトとして分離するかを示す値を設定します。 |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | デフォルトの背景ストローク。 |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | 事前計算されたデフォルトの前景ストローク。 |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | デフォルトのオブジェクト矩形。 |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | 画像エクスポートオプションを設定します。 |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | フェザリング半径を設定します。 |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | 想定オブジェクトコレクションに人間オブジェクトが含まれているかどうかを示す値。 |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | マスク領域を設定します。 |
| [setMethod(int value)](#setMethod-int-) | セグメンテーション方法を設定します。 |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | デフォルトポイントの事前計算プロセスの進行状況イベントハンドラを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


新しい [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) クラスのインスタンスを初期化します。

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


背景オブジェクト番号

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


自動マスキングの引数を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 画像です。 |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


デフォルトのストロークを埋めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 画像です。 |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


セグメンテーションアルゴリズムの引数を取得します。

値: セグメンテーションアルゴリズムの引数。

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


想定オブジェクトを取得します。

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - 想定オブジェクト。
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


背景置換色を取得します。

値: 背景置換色。この色は生成された画像の背景色として使用されます。

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


デフォルトのストロークを計算すべきかどうかを示す値を取得します。

**Returns:**
boolean - デフォルトのストロークを計算すべきかどうかを示す値。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


結合されたオブジェクトの矩形を取得します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


マスクから各Shapeを個別のオブジェクトとして分離するか、マスク全体を背景から分離した統合オブジェクトとして扱うかを示す値を取得します。

値: 分解する場合は true、そうでない場合は false。

**Returns:**
boolean - マスクから各シェイプを個別オブジェクトとして分離するか、背景から分離されたマスクの統合オブジェクトとして分離するかを示す値。
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


デフォルトの背景ストロークを取得します。

**Returns:**
com.aspose.psd.Point[] - デフォルトの背景ストローク。
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


事前計算されたデフォルトの前景ストロークを取得します。

**Returns:**
com.aspose.psd.Point[] - 事前計算されたデフォルトの前景ストロークです。
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


デフォルトのオブジェクト矩形を取得します。

**Returns:**
com.aspose.psd.Rectangle[] - デフォルトのオブジェクト矩形です。
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


デフォルトポイントの事前計算プロセスの進行状況イベントハンドラを取得します。

値: プログレスイベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


想定オブジェクトコレクションに人間オブジェクトが含まれているかどうかを示す値を取得します。

**Returns:**
boolean - 想定オブジェクトコレクションに人間オブジェクトが含まれているかを示す値です。
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


想定オブジェクトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | 想定オブジェクトです。 |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


デフォルトのストロークを計算すべきかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | デフォルトのストロークを計算すべきかどうかを示す値です。 |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


結合されたオブジェクトの矩形。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | 結合されたオブジェクトの矩形です。 |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


デフォルトの背景ストローク。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | デフォルトの背景ストロークです。 |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


事前計算されたデフォルトの前景ストローク。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 事前計算されたデフォルトの前景ストロークです。 |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


デフォルトのオブジェクト矩形。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | デフォルトのオブジェクト矩形です。 |

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

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


想定オブジェクトコレクションに人間オブジェクトが含まれているかどうかを示す値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 想定オブジェクトコレクションに人間オブジェクトが含まれているかを示す値です。 |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


デフォルトポイントの事前計算プロセスの進行状況イベントハンドラを設定します。

値: プログレスイベントハンドラ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | デフォルトポイントの事前計算プロセス進行イベントハンドラです。 |

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

