---
title: "JpegOptions クラス"
type: docs
weight: 60
url: /ja/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | 新しい [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) クラスのインスタンスを初期化します。 |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | 新しい [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | ロスレス JPEG 画像のチャンネルあたりビット数を取得または設定します。現在、2 ビットから 8 ビットまでのチャンネルあたりビット数をサポートしています。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg 画像用の宛先 CMYK カラープロファイルです。画像の保存に使用します。正しい色変換のために RGBColorProfile とペアで使用する必要があります。 |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | jpeg 画像のカラ―タイプを取得または設定します。 |
| コメント | string | r/w | jpeg ファイルのコメントを取得または設定します。 |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | 圧縮タイプを取得または設定します。 |
| default_memory_allocation_limit | int | r/w | デフォルトのメモリ割り当て上限を取得または設定します。 |
| default_replacement_font | string | r/w | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートする際にテキスト描画に使用されるフォント）。<br/>            正しいデフォルトフォント名を取得するには、次のコードスニペットを使用できます：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | exif データコンテナを取得または設定します |
| full_frame | bool | r/w | [full frame] かどうかを示す値を取得または設定します。 |
| horizontal_sampling | byte | r/w | 各コンポーネントの水平サブサンプリングを取得または設定します。 |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | jfif を取得または設定します。 |
| jpeg_ls_allowed_lossy_error | int | r/w | JPEG-LS の非可逆コーディング用差分境界（JPEG-LS 仕様の NEAR パラメータ）を取得または設定します。 |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | JPEG-LS のインタリーブモードを取得または設定します。 |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | JPEG-LS のプリセットパラメータを取得または設定します。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | マルチページオプション |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。 |
| preblend_alpha_if_present | bool | r/w | アルファチャンネルが存在する場合、赤・緑・青のコンポーネントを背景色と混合すべきかどうかを示す値を取得または設定します。 |
| quality | int | r/w | 画像品質を取得または設定します。 |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | RD オプティマイザ設定を取得または設定します。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 解像度設定を取得または設定します。 |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | 解像度単位を取得または設定します。 |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg 画像用の宛先 RGB カラープロファイルです。画像の保存に使用します。正しい色変換のために CMYKColorProfile とペアで使用する必要があります。 |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | 8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。 <see cref="P:JpegOptions.BitsPerChannel" /> |
| scaled_quality | int | r | スケールされた品質です。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 画像を作成するためのソースを取得または設定します。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | ベクトルラスター化オプションを取得または設定します。 |
| vertical_sampling | byte | r/w | 各コンポーネントの垂直サブサンプリングを取得または設定します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータ コンテナを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

新しい [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) クラスのインスタンスを初期化します。

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

新しい [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | JPEG オプションです。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | このインスタンスの浅いコピーを返します。 |


