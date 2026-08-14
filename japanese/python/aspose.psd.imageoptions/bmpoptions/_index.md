---
title: "BmpOptions クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) クラスの新しいインスタンスを初期化します。 |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | 画像のビット/ピクセル数を取得または設定します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | 圧縮を取得または設定します。 |
| default_replacement_font | string | r/w | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートする際にテキスト描画に使用されるフォント）。<br/>            正しいデフォルトフォント名を取得するには、次のコードスニペットを使用できます：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| full_frame | bool | r/w | [full frame] かどうかを示す値を取得または設定します。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | マルチページオプション |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 解像度設定を取得または設定します。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 画像を作成するためのソースを取得または設定します。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | ベクトルラスター化オプションを取得または設定します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータ コンテナを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

[BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) クラスの新しいインスタンスを初期化します。

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

[BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | BMP オプションです。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | このインスタンスの浅いコピーを返します。 |


