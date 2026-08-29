---
title: "TiffOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "TIFF ファイル形式のオプションです。"
type: docs
weight: 25
url: /ja/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

tiff ファイル形式オプションです。幅と高さのタグは画像作成時に幅と高さのパラメータによって上書きされるため、直接指定する必要はありません。多くのオプションはデフォルト値を返しますが、これはそのオプションがタグ値として明示的に設定されていることを意味しません。タグが存在するか確認するには Tags プロパティまたは対応する IsTagPresent メソッドを使用してください。

警告！保存中に tiff オプションを変更しないでください。副作用や見つけにくいバグの原因になる可能性があります。以下の行はデータ開始位置の判定が正しくなくなるため、特別にコメントアウトされています。渡されたオプションに spp が含まれていません（この場合オプション自体が正しくないとはいえ、依然としてエラーが発生します）。次の行で +spp タグと +bpp タグが追加され、データが完全に書き込まれた後にオプションが書き込まれると、非圧縮コーデックのデータ開始位置が上書きされてしまいます！！！詳細は TiffUncompressedCodec.Encode を参照してください。 this.Options.SamplesPerPixel = 3;
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | TiffOptions クラスの新しいインスタンスを初期化します。 |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | TiffOptions クラスの新しいインスタンスを初期化します。 |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | TiffOptions クラスの新しいインスタンスを初期化します。 |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | TiffOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | 新しいタグを追加します。 |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | タグを追加します。 |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | このインスタンスをクローンします。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | アルファストレージオプションを取得または設定します。 |
| [getArtist()](#getArtist--) | アーティストを取得または設定します。 |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | 背景色を取得または設定します。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | ピクセルあたりのビット数を取得します。 |
| [getBitsPerSample()](#getBitsPerSample--) | サンプルあたりのビット数を取得します。 |
| [getBufferSizeHint()](#getBufferSizeHint--) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [getByteOrder()](#getByteOrder--) | tiff バイトオーダーを示す値を取得または設定します。 |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | キャッシュを取得します。 |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | カラーマップを取得または設定します。 |
| [getCompressedQuality()](#getCompressedQuality--) | 圧縮画像の品質を取得します。 |
| [getCompression()](#getCompression--) | 圧縮方式を取得します。 |
| [getCopyright()](#getCopyright--) | 著作権情報を取得します。 |
| [getDateTime()](#getDateTime--) | 日付と時刻を取得または設定します。 |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | デフォルトのメモリ割り当て上限を取得または設定します。 |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getDocumentName()](#getDocumentName--) | ドキュメント名を取得または設定します。 |
| [getExifIfd()](#getExifIfd--) | EXIF IFD へのポインタを取得または設定します。 |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | 余分なサンプル数を取得します。 |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | 余分なサンプルの値を取得します。 |
| [getFaxT4Options()](#getFaxT4Options--) | FAX T4 オプションを取得または設定します。 |
| [getFileStandard()](#getFileStandard--) | TIFF ファイル標準を取得または設定します。 |
| [getFillOrder()](#getFillOrder--) | バイトビットのフィル順序を取得または設定します。 |
| [getFullFrame()](#getFullFrame--) | [full frame] かどうかを示す値を取得します。 |
| [getHalfToneHints()](#getHalfToneHints--) | ハーフトーンヒントを取得または設定します。 |
| [getIccProfile()](#getIccProfile--) | ICC プロファイルストリームを取得します。 |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [getImageDescription()](#getImageDescription--) | 画像の説明を取得または設定します。 |
| [getImageLength()](#getImageLength--) | 画像の長さを取得または設定します。 |
| [getImageWidth()](#getImageWidth--) | 画像の幅を取得または設定します。 |
| [getInkNames()](#getInkNames--) | インク名を取得または設定します。 |
| [getMaxSampleValue()](#getMaxSampleValue--) | 最大サンプル値を取得または設定します。 |
| [getMinSampleValue()](#getMinSampleValue--) | 最小サンプル値を取得または設定します。 |
| [getMultiPageOptions()](#getMultiPageOptions--) | マルチページオプション |
| [getOrientation()](#getOrientation--) | 向きを取得または設定します。 |
| [getPageName()](#getPageName--) | ページ名を取得または設定します。 |
| [getPageNumber()](#getPageNumber--) | ページ番号タグを取得または設定します。 |
| [getPalette()](#getPalette--) | カラーパレットを取得または設定します。 |
| [getPhotometric()](#getPhotometric--) | フォトメトリックを取得または設定します。 |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 平面構成を取得または設定します。 |
| [getPredictor()](#getPredictor--) | LZW 圧縮用の予測子を取得または設定します。 |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| [getProgressEventHandler()](#getProgressEventHandler--) | プログレスイベントハンドラを取得または設定します。 |
| [getResolutionSettings()](#getResolutionSettings--) | 解像度設定を取得または設定します。 |
| [getResolutionUnit()](#getResolutionUnit--) | 解像度単位を取得または設定します。 |
| [getRowsPerStrip()](#getRowsPerStrip--) | ストリップあたりの行数を取得または設定します。 |
| [getSampleFormat()](#getSampleFormat--) | サンプル形式を取得または設定します。 |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | ピクセルあたりのサンプル数を取得します。 |
| [getScannerManufacturer()](#getScannerManufacturer--) | スキャナメーカーを取得または設定します。 |
| [getScannerModel()](#getScannerModel--) | スキャナモデルを取得または設定します。 |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | 最大サンプル値を取得または設定します。 |
| [getSminSampleValue()](#getSminSampleValue--) | 最小サンプル値を取得または設定します。 |
| [getSoftwareType()](#getSoftwareType--) | ソフトウェアタイプを取得または設定します。 |
| [getSource()](#getSource--) | 画像を作成するソースを取得または設定します。 |
| [getStripByteCounts()](#getStripByteCounts--) | ストリップバイト数を取得または設定します。 |
| [getStripOffsets()](#getStripOffsets--) | ストリップオフセットを取得または設定します。 |
| [getSubFileType()](#getSubFileType--) | このサブファイルに含まれるデータの種類を示す一般的な指標を取得または設定します。 |
| [getTagByType(int tagKey)](#getTagByType-int-) | タイプでタグのインスタンスを取得します。 |
| [getTags()](#getTags--) | タグを取得または設定します。 |
| [getTargetPrinter()](#getTargetPrinter--) | ターゲットプリンターを取得または設定します。 |
| [getThreshholding()](#getThreshholding--) | しきい値の取得または設定。 |
| [getTileByteCounts()](#getTileByteCounts--) | タイルのバイト数の取得または設定。 |
| [getTileLength()](#getTileLength--) | タイルの長さの取得または設定。 |
| [getTileOffsets()](#getTileOffsets--) | タイルのオフセットの取得または設定。 |
| [getTileWidth()](#getTileWidth--) | タイルの幅の取得または設定。 |
| [getTotalPages()](#getTotalPages--) | 総ページ数の取得。 |
| [getValidTagCount()](#getValidTagCount--) | 有効なタグ数の取得。 |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | 有効なタグ数を取得します。 |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | ベクトルラスタライズオプションを取得または設定します。 |
| [getXPAuthor()](#getXPAuthor--) | Windows Explorerで使用される画像の作者の取得。 |
| [getXPComment()](#getXPComment--) | Windows Explorerで使用される画像のコメントの取得。 |
| [getXPKeywords()](#getXPKeywords--) | Windows Explorerで使用される画像の主題の取得。 |
| [getXPSubject()](#getXPSubject--) | Windows Explorerで使用される画像に関する情報の取得。 |
| [getXPTitle()](#getXPTitle--) | Windows Explorerで使用される画像に関する情報の取得。 |
| [getXmpData()](#getXmpData--) | XMP メタデータコンテナを取得または設定します。 |
| [getXposition()](#getXposition--) | x 位置の取得または設定。 |
| [getXresolution()](#getXresolution--) | X 解像度を取得または設定します。 |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | YCbCr係数の取得または設定。 |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | YCbCr 写真測光のサブサンプリング係数の取得または設定。 |
| [getYposition()](#getYposition--) | y 位置の取得または設定。 |
| [getYresolution()](#getYresolution--) | Y 解像度を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | 余分なサンプルが存在するかどうかを示す値の取得。 |
| [isTagPresent(int tag)](#isTagPresent-int-) | オプションにタグが存在するかどうかを判定。 |
| [isTiled()](#isTiled--) | 画像がタイル化されているかどうかを示す値の取得。 |
| [isValid()](#isValid--) | TiffOptions が適切に構成されているかどうかを示す値の取得。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | タグの削除。 |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | アルファストレージオプションを取得または設定します。 |
| [setArtist(String value)](#setArtist-java.lang.String-) | アーティストを取得または設定します。 |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | 背景色を取得または設定します。 |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | サンプルあたりのビット数を設定。 |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。 |
| [setByteOrder(int value)](#setByteOrder-int-) | tiff バイトオーダーを示す値を取得または設定します。 |
| [setColorMap(int[] value)](#setColorMap-int---) | カラーマップを取得または設定します。 |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | 圧縮画像の品質を設定。 |
| [setCompression(int value)](#setCompression-int-) | 圧縮方式を設定。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 著作権情報を設定。 |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 日付と時刻を取得または設定します。 |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | デフォルトのメモリ割り当て上限を取得または設定します。 |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | デフォルトの置換フォントを取得または設定します（ラスタにエクスポートする際にテキストを描画するために使用されるフォントで、PSD ファイル内の既存レイヤーフォントがシステムに存在しない場合）。 |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | ドキュメント名を取得または設定します。 |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | 余分なサンプルの値を設定。 |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | FAX T4 オプションを取得または設定します。 |
| [setFileStandard(int value)](#setFileStandard-int-) | TIFF ファイル標準を取得または設定します。 |
| [setFillOrder(int value)](#setFillOrder-int-) | バイトビットのフィル順序を取得または設定します。 |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | [full frame] かどうかを示す値を設定します。 |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | ハーフトーンヒントを取得または設定します。 |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | icc プロファイル ストリームを設定します。 |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 作成イベント後に無視するかどうかを示す値を取得または設定します。 |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 画像の説明を取得または設定します。 |
| [setImageLength(long value)](#setImageLength-long-) | 画像の長さを取得または設定します。 |
| [setImageWidth(long value)](#setImageWidth-long-) | 画像の幅を取得または設定します。 |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | インク名を取得または設定します。 |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | 最大サンプル値を取得または設定します。 |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | 最小サンプル値を取得または設定します。 |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | マルチページオプション |
| [setOrientation(int value)](#setOrientation-int-) | 向きを取得または設定します。 |
| [setPageName(String value)](#setPageName-java.lang.String-) | ページ名を取得または設定します。 |
| [setPageNumber(int[] value)](#setPageNumber-int---) | ページ番号タグを取得または設定します。 |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | カラーパレットを取得または設定します。 |
| [setPhotometric(int value)](#setPhotometric-int-) | フォトメトリックを取得または設定します。 |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 平面構成を取得または設定します。 |
| [setPredictor(int value)](#setPredictor-int-) | LZW 圧縮用の予測子を取得または設定します。 |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | プログレスイベントハンドラを取得または設定します。 |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 解像度設定を取得または設定します。 |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 解像度単位を取得または設定します。 |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | ストリップあたりの行数を取得または設定します。 |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | サンプル形式を取得または設定します。 |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | スキャナメーカーを取得または設定します。 |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | スキャナモデルを取得または設定します。 |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | 最大サンプル値を取得または設定します。 |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | 最小サンプル値を取得または設定します。 |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | ソフトウェアタイプを取得または設定します。 |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 画像を作成するソースを取得または設定します。 |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | ストリップバイト数を取得または設定します。 |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | ストリップオフセットを取得または設定します。 |
| [setSubFileType(long value)](#setSubFileType-long-) | このサブファイルに含まれるデータの種類を示す一般的な指標を取得または設定します。 |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | タグを取得または設定します。 |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | ターゲットプリンターを取得または設定します。 |
| [setThreshholding(int value)](#setThreshholding-int-) | しきい値の取得または設定。 |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | タイルのバイト数の取得または設定。 |
| [setTileLength(long value)](#setTileLength-long-) | タイルの長さの取得または設定。 |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | タイルのオフセットの取得または設定。 |
| [setTileWidth(long value)](#setTileWidth-long-) | タイルの幅の取得または設定。 |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | ベクトルラスタライズオプションを取得または設定します。 |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Windows Explorer で使用される画像の作者を設定します。 |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Windows Explorer で使用される画像のコメントを設定します。 |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Windows Explorer で使用される画像の件名を設定します。 |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Windows Explorer で使用される画像に関する情報を設定します。 |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Windows Explorer で使用される画像に関する情報を設定します。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP メタデータコンテナを取得または設定します。 |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | x 位置の取得または設定。 |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | X 解像度を取得または設定します。 |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | YCbCr係数の取得または設定。 |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | YCbCr 写真測光のサブサンプリング係数の取得または設定。 |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | y 位置の取得または設定。 |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Y 解像度を取得または設定します。 |
| [toString()](#toString--) |  |
| [validate()](#validate--) | オプションが有効なタグの組み合わせを持っているか検証します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


TiffOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| expectedFormat | int | 期待される tiff ファイル形式。 |
| byteOrder | int | 使用する TIFF ファイル形式のバイトオーダーです。 |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


TiffOptions クラスの新しいインスタンスを初期化します。デフォルトではリトルエンディアン方式が使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| expectedFormat | int | 期待される tiff ファイル形式。 |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


TiffOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | コピー元となるオプションです。 |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


TiffOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | オプションを初期化するためのタグです。 |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


新しいタグを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 追加するタグです。 |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


タグを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 追加するタグです。 |

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
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


アルファ ストレージ オプションを取得または設定します。TiffAlphaStorage.Unspecified 以外のオプションは、3 以上の SamplesPerPixel が定義されている場合に使用されます。

**Returns:**
int - アルファ ストレージ オプションです。
### getArtist() {#getArtist--}
```
public String getArtist()
```


アーティストを取得または設定します。

**Returns:**
java.lang.String - アーティストです。
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


背景色を取得または設定します。画像の背景色を内部的に保存する目的で使用されます。

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


ピクセルあたりのビット数を取得します。

**Returns:**
int - ピクセルあたりのビット数です。
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


サンプルあたりのビット数を取得します。

**Returns:**
int[] - サンプルあたりのビット数の値です。

この値を設定する際は、SamplesPerPixel の値も配列の長さに設定されることに留意してください。これら 2 つのプロパティは非常に密接に結びついているため、同時に設定する必要があります。
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


バッファサイズのヒントを取得または設定します。これはすべての内部バッファに対して許容される最大サイズとして定義されています。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


tiff バイトオーダーを示す値を取得または設定します。

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


キャッシュを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タグ | int | タグ（配列型です）。 |

**Returns:**
long[] - タグの値です。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


カラーマップを取得または設定します。

**Returns:**
int[] - カラーマップです。
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


圧縮画像の品質を取得します。Jpeg 圧縮で使用されます。

**Returns:**
int - 圧縮画像品質。
### getCompression() {#getCompression--}
```
public int getCompression()
```


圧縮方式を取得します。

**Returns:**
int - 圧縮。
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


著作権情報を取得します。

**Returns:**
java.lang.String - 著作権。
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


日付と時刻を取得または設定します。

**Returns:**
java.lang.String - 日付と時刻。
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


デフォルトのメモリ割り当て上限を取得または設定します。

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
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


ドキュメント名を取得または設定します。

**Returns:**
java.lang.String - ドキュメント名。
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


EXIF IFD へのポインタを取得または設定します。

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


余分なサンプル数を取得します。

Value: 余分なサンプル数。

**Returns:**
long - 余分なサンプル数。
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


余分なサンプルの値を取得します。

Value: 余分なサンプルの値。

**Returns:**
int[] - 余分なサンプルの値。
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


FAX T4 オプションを取得または設定します。

**Returns:**
long - ファックス T4 オプション。
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


TIFF ファイル標準を取得または設定します。

**Returns:**
int - TIFF ファイル標準。
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


バイトビットのフィル順序を取得または設定します。

**Returns:**
int - バイトビットのフィル順序。
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


[full frame] かどうかを示す値を取得します。

値:  true  （[full frame] の場合）；それ以外の場合は  false 。

**Returns:**
boolean - [full frame] かどうかを示す値。
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


ハーフトーンヒントを取得または設定します。

**Returns:**
int[] - ハーフトーンヒント。
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


ICC プロファイルストリームを取得します。

**Returns:**
byte[] - ICC プロファイル。
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


作成イベント後に無視するかどうかを示す値を取得または設定します。

値:  true  （作成イベント後に無視する場合）；それ以外の場合は  false 。

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


画像の説明を取得または設定します。

**Returns:**
java.lang.String - 画像説明。
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


画像の長さを取得または設定します。

**Returns:**
long - 画像の長さ。
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


画像の幅を取得または設定します。

**Returns:**
long - 画像の幅。
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


インク名を取得または設定します。

**Returns:**
java.lang.String - インク名。
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


最大サンプル値を取得または設定します。

**Returns:**
int[] - 最大サンプル値。
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


最小サンプル値を取得または設定します。

**Returns:**
int[] - 最小サンプル値。
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


マルチページオプション

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


向きを取得または設定します。

**Returns:**
int - 方向。
### getPageName() {#getPageName--}
```
public String getPageName()
```


ページ名を取得または設定します。

**Returns:**
java.lang.String - ページ名。
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


ページ番号タグを取得または設定します。

**Returns:**
int[] - ページ番号タグ。
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


カラーパレットを取得または設定します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


フォトメトリックを取得または設定します。

**Returns:**
int - フォトメトリック。
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


平面構成を取得または設定します。

**Returns:**
int - 平面構成。
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


LZW 圧縮用の予測子を取得または設定します。

**Returns:**
int - 予測子のタイプ。
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。

**Returns:**
boolean -  コンポーネントが事前乗算される場合は true、そうでない場合は false。
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
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


解像度単位を取得または設定します。

**Returns:**
int - 解像度の単位。
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


ストリップあたりの行数を取得または設定します。

**Returns:**
long - ストリップあたりの行数。
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


サンプル形式を取得または設定します。

**Returns:**
int[] - サンプル形式。
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


ピクセルあたりのサンプル数を取得します。このプロパティの値を変更するには BitsPerSample プロパティのセッターを使用します。

**Returns:**
int - ピクセルあたりのサンプル数。
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


スキャナメーカーを取得または設定します。

**Returns:**
java.lang.String - スキャナの製造元。
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


スキャナモデルを取得または設定します。

**Returns:**
java.lang.String - スキャナのモデル。
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


最大サンプル値を取得または設定します。値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。

**Returns:**
long[] - 最大サンプル値。
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


最小サンプル値を取得または設定します。値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。

**Returns:**
long[] - 最小サンプル値。
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


ソフトウェアタイプを取得または設定します。

**Returns:**
java.lang.String - ソフトウェアのタイプ。
### getSource() {#getSource--}
```
public final Source getSource()
```


画像を作成するソースを取得または設定します。

値: 画像を作成するソース。

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


ストリップバイト数を取得または設定します。

**Returns:**
long[] - ストリップのバイト数。
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


ストリップオフセットを取得または設定します。

**Returns:**
long[] - ストリップのオフセット。
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


このサブファイルに含まれるデータの種類を示す一般的な指標を取得または設定します。

**Returns:**
long - このサブファイルに含まれるデータの種類を示す一般的な指標。
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


タイプでタグのインスタンスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tagKey | int | タグキー。 |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


タグを取得または設定します。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - タグ。
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


ターゲットプリンターを取得または設定します。

**Returns:**
java.lang.String - 対象プリンター。
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


しきい値の取得または設定。

**Returns:**
int - 閾値設定。
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


タイルのバイト数の取得または設定。

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


タイルの長さの取得または設定。

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


タイルのオフセットの取得または設定。

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


タイルの幅の取得または設定。

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


総ページ数の取得。

**Returns:**
int - 総ページ数。
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


有効なタグ数を取得します。これは総タグ数ではなく、保持できるタグの数です。

**Returns:**
int - 有効なタグ数。
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


有効なタグ数を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 検証するタグ。 |

**Returns:**
int - 有効なタグ数。
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


ベクトルラスタライズオプションを取得または設定します。

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Windows Explorerで使用される画像の作者の取得。

値: Image Author、Windows Explorerで使用されます。XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) は、Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) タグが存在する場合、Windows Explorerで無視されます。

**Returns:**
java.lang.String - 画像の作者で、Windows Explorerで使用されます。
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Windows Explorerで使用される画像のコメントの取得。

値: 画像のコメント、Windows Explorerで使用されます。

**Returns:**
java.lang.String - 画像のコメントで、Windows Explorerで使用されます。
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Windows Explorerで使用される画像の主題の取得。

値: 画像の件名、Windows Explorerで使用されます。

**Returns:**
java.lang.String - 画像の件名で、Windows Explorerで使用されます。
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Windows Explorerで使用される画像に関する情報の取得。

値: 画像に関する情報、Windows Explorerで使用されます。

**Returns:**
java.lang.String - 画像に関する情報で、Windows Explorerで使用されます。
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Windows Explorerで使用される画像に関する情報の取得。

値: 画像に関する情報、Windows Explorerで使用されます。XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) は、ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) タグが存在する場合、Windows Explorerで無視されます。

**Returns:**
java.lang.String - 画像に関する情報で、Windows Explorerで使用されます。
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP メタデータコンテナを取得または設定します。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


x 位置の取得または設定。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


X 解像度を取得または設定します。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


YCbCr係数の取得または設定。

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - YCbCr係数です。
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


YCbCr 写真測光のサブサンプリング係数の取得または設定。

**Returns:**
int[] - YCbCrフォトメトリックのサブサンプリング係数です。
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


y 位置の取得または設定。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Y 解像度を取得または設定します。

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


余分なサンプルが存在するかどうかを示す値の取得。

**Returns:**
boolean -  true  余分なサンプルが存在する場合; それ以外は  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


オプションにタグが存在するかどうかを判定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タグ | int | 確認するタグ IDです。 |

**Returns:**
boolean -  true  タグが存在する場合; それ以外は  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


画像がタイル化されているかどうかを示す値の取得。

**Returns:**
boolean -  true  画像がタイル状の場合; それ以外は  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


TiffOptions が正しく構成されているかどうかを示す値を取得します。失敗理由を確認するには Validate メソッドを使用してください。

**Returns:**
boolean -  true  TiffOptions が正しく構成されている場合; それ以外は  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


タグの削除。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タグ | int | 削除するタグです。 |

**Returns:**
boolean - true 成功裏に削除された場合
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


アルファ ストレージ オプションを取得または設定します。TiffAlphaStorage.Unspecified 以外のオプションは、3 以上の SamplesPerPixel が定義されている場合に使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | アルファストレージオプションです。 |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


アーティストを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | アーティストです。 |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


背景色を取得または設定します。画像の背景色を内部的に保存する目的で使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 背景色です。 |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


サンプルあたりのビット数を設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int[] | サンプルあたりのビット数の値です。 |

この値を設定する際は、SamplesPerPixel の値も配列の長さに設定されることに留意してください。これら 2 つのプロパティは非常に密接に結合しているため、同時に設定する必要があります。 |

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

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


tiff バイトオーダーを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


カラーマップを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | カラーマップです。 |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


圧縮画像の品質を設定します。Jpeg 圧縮と共に使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 圧縮画像の品質。 |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


圧縮方式を設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 圧縮です。 |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


著作権情報を設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 著作権。 |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


日付と時刻を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 日付と時刻。 |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


デフォルトのメモリ割り当て上限を取得または設定します。

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

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


ドキュメント名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | ドキュメントの名前。 |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


余分なサンプルの値を設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | 余分なサンプルの値。 |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


FAX T4 オプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | FAX T4 オプション。 |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


TIFF ファイル標準を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | TIFF ファイル標準。 |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


バイトビットのフィル順序を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | バイトビットのフィル順序。 |

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

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


ハーフトーンヒントを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | ハーフトーンヒント。 |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


icc プロファイル ストリームを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] | icc プロファイルです。 |

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

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


画像の説明を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 画像の説明。 |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


画像の長さを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | 画像の長さ。 |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


画像の幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | 画像の幅です。 |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


インク名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | インク名。 |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


最大サンプル値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | 最大サンプル値。 |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


最小サンプル値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | 最小サンプル値。 |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


マルチページオプション

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


向きを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 向き。 |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


ページ名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | ページ名。 |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


ページ番号タグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | ページ番号タグ。 |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


カラーパレットを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


フォトメトリックを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | フォトメトリック。 |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


平面構成を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 平面構成。 |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


LZW 圧縮用の予測子を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 予測子タイプ。 |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | コンポーネントが事前乗算される必要がある場合は true、そうでない場合は false。 |

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

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


解像度単位を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 解像度単位。 |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


ストリップあたりの行数を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | ストリップあたりの行数。 |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


サンプル形式を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | サンプル形式。 |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


スキャナメーカーを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | スキャナーの製造元。 |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


スキャナモデルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | スキャナーのモデル。 |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


最大サンプル値を取得または設定します。値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long[] | 最大サンプル値。 |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


最小サンプル値を取得または設定します。値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long[] | 最小サンプル値。 |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


ソフトウェアタイプを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | ソフトウェアの種類。 |

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

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


ストリップバイト数を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long[] | ストリップバイト数。 |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


ストリップオフセットを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long[] | ストリップオフセット。 |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


このサブファイルに含まれるデータの種類を示す一般的な指標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | このサブファイルに含まれるデータの種類の一般的な指示。 |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


タグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | タグ。 |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


ターゲットプリンターを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 対象プリンター。 |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


しきい値の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | しきい値設定。 |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


タイルのバイト数の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


タイルの長さの取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


タイルのオフセットの取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


タイルの幅の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


ベクトルラスタライズオプションを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Windows Explorer で使用される画像の作者を設定します。

値: Image Author、Windows Explorerで使用されます。XPAuthor（[.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String)）は、Artist（[.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-))タグが存在する場合、Windows Explorer によって無視されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 画像の作者、Windows Explorerで使用されます。 |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Windows Explorer で使用される画像のコメントを設定します。

値: 画像のコメント、Windows Explorerで使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 画像のコメント、Windows Explorerで使用されます。 |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Windows Explorer で使用される画像の件名を設定します。

値: 画像の件名、Windows Explorerで使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 画像の件名、Windows Explorerで使用されます。 |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Windows Explorer で使用される画像に関する情報を設定します。

値: 画像に関する情報、Windows Explorerで使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 画像に関する情報、Windows Explorerで使用されます。 |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Windows Explorer で使用される画像に関する情報を設定します。

値: 画像に関する情報、Windows Explorerで使用されます。XPTitle（[.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String)）は、ImageDescription（[.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-))タグが存在する場合、Windows Explorer によって無視されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 画像に関する情報、Windows Explorerで使用されます。 |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP メタデータコンテナを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP データコンテナ。 |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


x 位置の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x 位置。 |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


X 解像度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x 解像度。 |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


YCbCr係数の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | YCbCrCoefficients。 |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


YCbCr 写真測光のサブサンプリング係数の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] | YCbCr フォトメトリックのサブサンプリング係数。 |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


y 位置の取得または設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y 位置。 |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Y 解像度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y 解像度。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


オプションが有効なタグの組み合わせを持っているか検証します

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

