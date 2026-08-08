---
title: "PngOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PNG ファイル形式の作成オプションです。"
type: docs
weight: 19
url: /ja/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

PNG ファイル形式の作成オプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PngOptions()](#PngOptions--) | PngOptions クラスの新しいインスタンスを初期化します。 |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | JpegOptions クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | デフォルトの圧縮レベル。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | このインスタンスをクローンします。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | ビット深度を取得します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 色のタイプを取得または設定します。 |
| [getCompressionLevel()](#getCompressionLevel--) | 0〜9 の範囲の PNG 画像圧縮レベルで、9 が最大圧縮、0 がストアモードです。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getFilterType()](#getFilterType--) | PNG ファイル保存プロセスで使用されるフィルタタイプを取得または設定します。 |
| [getFullFrame()](#getFullFrame--) | [full frame] かどうかを示す値を取得します。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | マルチページオプション |
| [getPalette()](#getPalette--) | カラーパレットを取得または設定します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得または設定します。 |
| [getProgressive()](#getProgressive--) | この PngOptions がプログレッシブかどうかを示す値を取得または設定します。 |
| [getResolutionSettings()](#getResolutionSettings--) | 解像度設定を取得または設定します。 |
| [getSource()](#getSource--) | 画像を作成するソースを取得または設定します。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | ベクトルラスタライズオプションを取得または設定します。 |
| [getXmpData()](#getXmpData--) | XMP メタデータコンテナを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | ビット深度を設定します。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [setColorType(int value)](#setColorType-int-) | 色のタイプを取得または設定します。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 0〜9 の範囲の PNG 画像圧縮レベルで、9 が最大圧縮、0 がストアモードです。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [setFilterType(int value)](#setFilterType-int-) | PNG ファイル保存プロセスで使用されるフィルタタイプを取得または設定します。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | [full frame] かどうかを示す値を設定します。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | マルチページオプション |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを取得または設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを取得または設定します。 |
| [setProgressive(boolean value)](#setProgressive-boolean-) | この PngOptions がプログレッシブかどうかを示す値を取得または設定します。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 解像度設定を取得または設定します。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 画像を作成するソースを取得または設定します。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | ベクトルラスタライズオプションを取得または設定します。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP メタデータコンテナを取得または設定します。 |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | オプションの検証ルーチンです。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


PngOptions クラスの新しいインスタンスを初期化します。

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


JpegOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | PNG オプションです。 |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


デフォルトの圧縮レベル。

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
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


ビット深度を取得します。

**Returns:**
byte - ビット深度。
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
### getColorType() {#getColorType--}
```
public int getColorType()
```


色のタイプを取得または設定します。

**Returns:**
int - カラーのタイプ。
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


0〜9 の範囲の PNG 画像圧縮レベルで、9 が最大圧縮、0 がストアモードです。

**Returns:**
int - 0〜9 の範囲の圧縮レベルで、9 が最大圧縮、0 がストアモードです。
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
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


PNG ファイル保存プロセスで使用されるフィルタタイプを取得または設定します。

**Returns:**
int - PNG ファイル保存プロセスで使用されるフィルタタイプ。
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
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


この PngOptions がプログレッシブかどうかを示す値を取得または設定します。

**Returns:**
boolean - プログレッシブの場合は true、そうでない場合は false。
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




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


ビット深度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte | ビット深度です。 |

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

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


色のタイプを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | カラーのタイプです。 |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


0〜9 の範囲の PNG 画像圧縮レベルで、9 が最大圧縮、0 がストアモードです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 0〜9 の範囲の圧縮レベルで、9 が最大圧縮、0 がストアモードです。 |

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

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


PNG ファイル保存プロセスで使用されるフィルタタイプを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | PNG ファイル保存プロセスで使用されるフィルタタイプです。 |

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

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


この PngOptions がプログレッシブかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | プログレッシブの場合は true、そうでない場合は false。 |

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
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


オプションの検証ルーチンです。

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

