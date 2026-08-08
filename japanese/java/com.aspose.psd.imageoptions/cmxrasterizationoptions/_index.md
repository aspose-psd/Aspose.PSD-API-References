---
title: "CmxRasterizationOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "CMX エクスポーターオプション。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase), [com.aspose.psd.imageoptions.VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
```
public class CmxRasterizationOptions extends VectorRasterizationOptions
```

CMX エクスポーターオプション。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions--) | 新しい [CmxRasterizationOptions](../../com.aspose.psd.imageoptions/cmxrasterizationoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | コピー先。 |
| [deepClone()](#deepClone--) | このインスタンスをクローンします。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 背景色を取得します。 |
| [getBorderX()](#getBorderX--) | 境界 X を取得または設定します。 |
| [getBorderY()](#getBorderY--) | 境界 Y を取得または設定します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [getCenterDrawing()](#getCenterDrawing--) | 中心描画かどうかを示す値を取得します。 |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getDrawColor()](#getDrawColor--) | 前景色を取得します。 |
| [getFullFrame()](#getFullFrame--) | [full frame] かどうかを示す値を取得します。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | マルチページオプション |
| [getPageHeight()](#getPageHeight--) | ページの高さを取得します。 |
| [getPageSize()](#getPageSize--) | ページサイズを取得します。 |
| [getPageWidth()](#getPageWidth--) | ページの幅を取得します。 |
| [getPalette()](#getPalette--) | カラーパレットを取得または設定します。 |
| [getPositioning()](#getPositioning--) | 配置を取得します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得または設定します。 |
| [getResolutionSettings()](#getResolutionSettings--) | 解像度設定を取得または設定します。 |
| [getSmoothingMode()](#getSmoothingMode--) | スムージングモードを取得します。 |
| [getSource()](#getSource--) | 画像を作成するソースを取得または設定します。 |
| [getTextRenderingHint()](#getTextRenderingHint--) | テキストレンダリングヒントを取得します。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | ベクトルラスタライズオプションを取得または設定します。 |
| [getXmpData()](#getXmpData--) | XMP メタデータコンテナを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | 背景色を設定します。 |
| [setBorderX(float value)](#setBorderX-float-) | 境界 X を取得または設定します。 |
| [setBorderY(float value)](#setBorderY-float-) | 境界 Y を取得または設定します。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | 中心描画かどうかを示す値を設定します。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | 前景色を設定します。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | [full frame] かどうかを示す値を設定します。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | マルチページオプション |
| [setPageHeight(float value)](#setPageHeight-float-) | ページの高さを設定します。 |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | ページサイズを設定します。 |
| [setPageWidth(float value)](#setPageWidth-float-) | ページの幅を設定します。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを取得または設定します。 |
| [setPositioning(int value)](#setPositioning-int-) | 配置を設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを取得または設定します。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 解像度設定を取得または設定します。 |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | スムージングモードを設定します。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 画像を作成するソースを取得または設定します。 |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | テキストレンダリングヒントを設定します。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | ベクトルラスタライズオプションを取得または設定します。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP メタデータコンテナを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmxRasterizationOptions() {#CmxRasterizationOptions--}
```
public CmxRasterizationOptions()
```


新しい [CmxRasterizationOptions](../../com.aspose.psd.imageoptions/cmxrasterizationoptions) クラスのインスタンスを初期化します。

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


コピー先。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | ベクトルラスター化オプションです。 |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


このインスタンスをクローンします。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


背景色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


境界 X を取得または設定します。

**Returns:**
float - 境界 X。
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


境界 Y を取得または設定します。

**Returns:**
float - 境界 Y。
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


中心描画かどうかを示す値を取得します。

**Returns:**
boolean - 中心描画かどうかを示す値。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。デフォルトフォントの正しい名前を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

値: デフォルトの置換フォント。

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


前景色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


[full frame] かどうかを示す値を取得します。

値:  true  （[full frame] の場合）；それ以外の場合は  false 。

**Returns:**
boolean - [full frame] かどうかを示す値。
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


作成イベント後に無視するかどうかを示す値を取得または設定します。

値:  true  （作成イベント後に無視する場合）；それ以外の場合は  false 。

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


マルチページオプション

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


ページの高さを取得します。

**Returns:**
float - ページの高さ。
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


ページサイズを取得します。

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


ページの幅を取得します。

**Returns:**
float - ページの幅。
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


カラーパレットを取得または設定します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


配置を取得します。

値: 配置。

**Returns:**
int - 配置。
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


プログレスイベントハンドラを取得または設定します。

値: プログレスイベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


解像度設定を取得または設定します。

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


スムージングモードを取得します。

**Returns:**
int - スムージングモード。
### getSource() {#getSource--}
```
public final Source getSource()
```


画像を作成するソースを取得または設定します。

値: 画像を作成するソース。

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


テキストレンダリングヒントを取得します。

値: テキストレンダリングヒント。

**Returns:**
int - テキストレンダリングヒント。
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


ベクトルラスタライズオプションを取得または設定します。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP メタデータコンテナを取得または設定します。

値: XMP データコンテナ。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


背景色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 背景色。 |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


境界 X を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 境界 X。 |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


境界 Y を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 境界 Y。 |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


中心描画かどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 中心描画かどうかを示す値。 |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。デフォルトフォントの正しい名前を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

値: デフォルトの置換フォント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


前景色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 前景色。 |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


[full frame] かどうかを示す値を設定します。

値:  true  （[full frame] の場合）；それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | [full frame] かどうかを示す値。 |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


作成イベント後に無視するかどうかを示す値を取得または設定します。

値:  true  （作成イベント後に無視する場合）；それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


マルチページオプション

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


ページの高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | ページの高さ。 |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


ページサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | ページサイズ。 |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


ページの幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | ページ幅。 |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


カラーパレットを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


配置を設定します。

値: 配置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 配置。 |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


プログレスイベントハンドラを取得または設定します。

値: プログレスイベントハンドラ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


解像度設定を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


スムージングモードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | スムージングモード。 |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


画像を作成するソースを取得または設定します。

値: 画像を作成するソース。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


テキストレンダリングヒントを設定します。

値: テキストレンダリングヒント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | テキストレンダリングヒント。 |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


ベクトルラスタライズオプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP メタデータコンテナを取得または設定します。

値: XMP データコンテナ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

