---
title: "JpegOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "JPEG ファイル形式の作成オプション。"
type: docs
weight: 15
url: /ja/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

JPEG ファイル形式の作成オプション。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | JpegOptions クラスの新しいインスタンスを初期化します。 |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | JpegOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | このインスタンスをクローンします。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | ロスレス jpeg 画像のチャネルあたりのビット数を取得します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK jpeg 画像用の宛先 CMYK カラープロファイル。 |
| [getColorType()](#getColorType--) | jpeg 画像のカラータイプを取得します。 |
| [getComment()](#getComment--) | jpeg ファイルのコメントを取得します。 |
| [getCompressionType()](#getCompressionType--) | 圧縮タイプを取得します。 |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | デフォルトのメモリ割り当て上限を取得します。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getExifData()](#getExifData--) | exif データコンテナを取得または設定します |
| [getFullFrame()](#getFullFrame--) | [full frame] かどうかを示す値を取得します。 |
| [getHorizontalSampling()](#getHorizontalSampling--) | 各コンポーネントの水平サブサンプリングを取得します。 |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [getJfif()](#getJfif--) | jfif を取得します。 |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | JPEG-LS 仕様の NEAR パラメータに基づく、ニアロスレス符号化用の JPEG-LS 差分境界を取得します。 |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | JPEG-LS のインタリーブモードを取得します。 |
| [getJpegLsPreset()](#getJpegLsPreset--) | JPEG-LS のプリセットパラメータを取得します。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | マルチページオプション |
| [getPalette()](#getPalette--) | カラーパレットを取得または設定します。 |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | アルファチャンネルが存在する場合、赤・緑・青のコンポーネントを背景色と混合すべきかを示す値を取得します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得または設定します。 |
| [getQuality()](#getQuality--) | 画像品質を取得します。 |
| [getRdOptSettings()](#getRdOptSettings--) | RDオプティマイザ設定を取得します。 |
| [getResolutionSettings()](#getResolutionSettings--) | 解像度設定を取得または設定します。 |
| [getResolutionUnit()](#getResolutionUnit--) | 解像度単位を取得します。 |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK jpeg画像用の宛先RGBカラープロファイルです。 |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | 8ビット値をnビット値に合わせるサンプル丸めモードを取得します。 |
| [getScaledQuality()](#getScaledQuality--) | スケーリングされた品質です。 |
| [getSource()](#getSource--) | 画像を作成するソースを取得または設定します。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | ベクトルラスタライズオプションを取得または設定します。 |
| [getVerticalSampling()](#getVerticalSampling--) | 各コンポーネントの垂直サブサンプリングを取得します。 |
| [getXmpData()](#getXmpData--) | XMPメタデータコンテナを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | ロスレスjpeg画像のチャンネルあたりビット数を設定します。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK jpeg 画像用の宛先 CMYK カラープロファイル。 |
| [setColorType(int value)](#setColorType-int-) | jpeg画像のカラータイプを設定します。 |
| [setComment(String value)](#setComment-java.lang.String-) | jpegファイルのコメントを設定します。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 圧縮タイプを設定します。 |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | デフォルトのメモリ割り当て上限を設定します。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | exif データコンテナを取得または設定します |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | [full frame] かどうかを示す値を設定します。 |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | 各コンポーネントの水平サブサンプリングを設定します。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | jfifを設定します。 |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | JPEG-LS仕様のNEARパラメータに基づく、ニアロスレスコーディング用の差分境界を設定します。 |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | JPEG-LSのインタリーブモードを設定します。 |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | JPEG-LSのプリセットパラメータを設定します。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | マルチページオプション |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを取得または設定します。 |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | アルファチャンネルが存在する場合、赤・緑・青のコンポーネントを背景色と混合すべきかを示す値を設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを取得または設定します。 |
| [setQuality(int value)](#setQuality-int-) | 画像品質を設定します。 |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | RDオプティマイザ設定を設定します。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 解像度設定を取得または設定します。 |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | 解像度単位を設定します。 |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK jpeg画像用の宛先RGBカラープロファイルです。 |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8ビット値をnビット値に合わせるサンプル丸めモードを設定します。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 画像を作成するソースを取得または設定します。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | ベクトルラスタライズオプションを取得または設定します。 |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | 各コンポーネントの垂直サブサンプリングを設定します。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP メタデータ コンテナを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


JpegOptions クラスの新しいインスタンスを初期化します。

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


JpegOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | JPEG オプションです。 |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


ロスレス jpeg 画像のチャンネルあたりビット数を取得します。現在、2 ビットから 8 ビットまでサポートしています。

**Returns:**
byte
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
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


CMYK jpeg 画像用の宛先 CMYK カラープロファイルです。画像の保存に使用します。正しい色変換のために RGBColorProfile とペアで使用する必要があります。

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg 画像のカラータイプを取得します。

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


jpeg ファイルのコメントを取得します。

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


圧縮タイプを取得します。

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


デフォルトのメモリ割り当て上限を取得します。

**Returns:**
int - デフォルトのメモリ割り当て上限です。
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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


exif データコンテナを取得または設定します

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


[full frame] かどうかを示す値を取得します。

値:  true  （[full frame] の場合）；それ以外の場合は  false 。

**Returns:**
boolean - [full frame] かどうかを示す値。
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


各コンポーネントの水平サブサンプリングを取得します。

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


作成イベント後に無視するかどうかを示す値を取得または設定します。

値:  true  （作成イベント後に無視する場合）；それ以外の場合は  false 。

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


jfif を取得します。

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


JPEG-LS 仕様の NEAR パラメータに基づく、ニアロスレス符号化用の JPEG-LS 差分境界を取得します。

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


JPEG-LS のインタリーブモードを取得します。

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


JPEG-LS のプリセットパラメータを取得します。

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
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
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


アルファチャンネルが存在する場合、赤・緑・青のコンポーネントを背景色と混合すべきかを示す値を取得します。

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


プログレスイベントハンドラを取得または設定します。

値: プログレスイベントハンドラ。

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


画像品質を取得します。

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


RDオプティマイザ設定を取得します。

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


解像度設定を取得または設定します。

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


解像度単位を取得します。

**Returns:**
byte - 解像度単位です。
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


CMYK jpeg 画像用の宛先 RGB カラープロファイルです。画像の保存に使用します。正しい色変換のために CMYKColorProfile とペアで使用する必要があります。

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8 ビット値を n ビット値に合わせるサンプル丸めモードを取得します。  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


スケーリングされた品質です。

**Returns:**
int
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
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


各コンポーネントの垂直サブサンプリングを取得します。

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMPメタデータコンテナを取得します。

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




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


ロスレス jpeg 画像のチャンネルあたりビット数を設定します。現在、2 ビットから 8 ビットまでサポートしています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK jpeg 画像用の宛先 CMYK カラープロファイルです。画像の保存に使用します。正しい色変換のために RGBColorProfile とペアで使用する必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg画像のカラータイプを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpegファイルのコメントを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


圧縮タイプを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


デフォルトのメモリ割り当て上限を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | デフォルトのメモリ割り当て上限です。 |

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


exif データコンテナを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


各コンポーネントの水平サブサンプリングを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


jfifを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


JPEG-LS仕様のNEARパラメータに基づく、ニアロスレスコーディング用の差分境界を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


JPEG-LSのインタリーブモードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


JPEG-LSのプリセットパラメータを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

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

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


アルファチャンネルが存在する場合、赤・緑・青のコンポーネントを背景色と混合すべきかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


画像品質を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


RDオプティマイザ設定を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | RD オプティマイザ設定です。 |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


解像度設定を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


解像度単位を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte | 解像度単位です。 |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


CMYK jpeg 画像用の宛先 RGB カラープロファイルです。画像の保存に使用します。正しい色変換のために CMYKColorProfile とペアで使用する必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8 ビット値を n ビット値に合わせるサンプル丸めモードを設定します。  P:JpegOptions.BitsPerChannel

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


各コンポーネントの垂直サブサンプリングを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP メタデータ コンテナを設定します。

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

