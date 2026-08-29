---
title: "Jpeg2000Options"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "JPEG2000 ファイル形式のオプション。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.imageoptions/jpeg2000options/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

JPEG2000 ファイル形式のオプション。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Jpeg2000Options クラスの新しいインスタンスを初期化します。 |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-) | Jpeg2000Options クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | このインスタンスをクローンします。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [getClass()](#getClass--) |  |
| [getCodec()](#getCodec--) | JPEG2000 コーデックを取得または設定します |
| [getComments()](#getComments--) | Jpeg コメントマーカーを取得または設定します。 |
| [getCompressionRatios()](#getCompressionRatios--) | 圧縮率の配列を取得または設定します。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getFullFrame()](#getFullFrame--) | [full frame] かどうかを示す値を取得します。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [getIrreversible()](#getIrreversible--) | 不可逆 DWT 9-7 (true) を使用するか、可逆 DWT 5-3 圧縮 (既定) を使用するかを示す値を取得します。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | マルチページオプション |
| [getPalette()](#getPalette--) | カラーパレットを取得または設定します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得または設定します。 |
| [getResolutionSettings()](#getResolutionSettings--) | 解像度設定を取得または設定します。 |
| [getSource()](#getSource--) | 画像を作成するソースを取得または設定します。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | ベクトルラスタライズオプションを取得または設定します。 |
| [getXmpData()](#getXmpData--) | XMP メタデータコンテナを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [setCodec(int value)](#setCodec-int-) | JPEG2000 コーデックを取得または設定します |
| [setComments(String[] value)](#setComments-java.lang.String---) | Jpeg コメントマーカーを取得または設定します。 |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | 圧縮率の配列を取得または設定します。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | [full frame] かどうかを示す値を設定します。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | 不可逆 DWT 9-7 (true) を使用するか、可逆 DWT 5-3 圧縮 (既定) を使用するかを示す値を設定します。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | マルチページオプション |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを取得または設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを取得または設定します。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 解像度設定を取得または設定します。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 画像を作成するソースを取得または設定します。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | ベクトルラスタライズオプションを取得または設定します。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP メタデータコンテナを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Jpeg2000Options クラスの新しいインスタンスを初期化します。

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Jpeg2000Options クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.psd.imageoptions/jpeg2000options) | 設定をコピーする Jpeg2000 ファイル形式オプション。 |

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodec() {#getCodec--}
```
public int getCodec()
```


JPEG2000 コーデックを取得または設定します

**Returns:**
int - JPEG2000 コーデック
### getComments() {#getComments--}
```
public String[] getComments()
```


Jpeg コメントマーカーを取得または設定します。

**Returns:**
java.lang.String[] - Jpeg コメントマーカー。
### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


圧縮率の配列を取得または設定します。連続するレイヤーごとに異なる圧縮率があります。各品質レベルで指定されたレートは目的の圧縮係数です。圧縮率を減少させる必要があります。

**Returns:**
int[] - 圧縮率。
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
### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


不可逆 DWT 9-7 (true) を使用するか、可逆 DWT 5-3 圧縮 (既定) を使用するかを示す値を取得します。

**Returns:**
boolean - 不可逆 DWT 9-7 (true) を使用するか、可逆 DWT 5-3 圧縮を使用するかを示す値
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


マルチページオプション

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


カラーパレットを取得または設定します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
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
### getSource() {#getSource--}
```
public final Source getSource()
```


画像を作成するソースを取得または設定します。

値: 画像を作成するソース。

**Returns:**
[Source](../../com.aspose.psd/source)
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
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

### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


JPEG2000 コーデックを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | JPEG2000 コーデック |

### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Jpeg コメントマーカーを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String[] | Jpeg コメントマーカー。 |

### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


圧縮率の配列を取得または設定します。連続するレイヤーごとに異なる圧縮率があります。各品質レベルで指定されたレートは目的の圧縮係数です。圧縮率を減少させる必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | 圧縮率。 |

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

### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


不可逆 DWT 9-7 (true) を使用するか、可逆 DWT 5-3 圧縮 (既定) を使用するかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 不可逆 DWT 9-7 (true) を使用するか、可逆 DWT 5-3 圧縮を使用するかを示す値 |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


マルチページオプション

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


カラーパレットを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

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

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP データコンテナ。 |

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

