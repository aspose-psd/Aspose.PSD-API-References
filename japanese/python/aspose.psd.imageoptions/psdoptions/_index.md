---
title: "PsdOptions クラス"
type: docs
weight: 100
url: /ja/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | 新しい [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) クラスのインスタンスを初期化します。 |
| [PsdOptions(image)](#PsdOptions_image_2) | 新しい [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) クラスのインスタンスを初期化します。 |
| [PsdOptions(options)](#PsdOptions_options_3) | 新しい [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | 背景色を取得または設定します。<br/>            透明オブジェクトの下で表示されます。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| channel_bits_count | short | r/w | カラー チャネルごとのビット数を取得または設定します。 |
| channels_count | short | r/w | カラー チャネル数を取得または設定します。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | PSD カラーモードを取得または設定します。 |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | PSD 圧縮方式を取得または設定します。 |
| default_replacement_font | string | r/w | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートする際にテキスト描画に使用されるフォント）。<br/>            正しいデフォルトフォント名を取得するには、次のコードスニペットを使用できます：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| full_frame | bool | r/w | [full frame] かどうかを示す値を取得または設定します。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | マルチページオプション |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。 |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | ファイル形式のバージョンを取得または設定します。PSD または PSB のいずれかです。 |
| refresh_image_preview_data | bool | r/w | [refresh image preview data] の有無を示す値を取得または設定します。- 他の PSD 画像ビューアとの互換性を最大化するために使用されるオプションです。<br/>            注意: Compact Framework プラットフォームでは、テキストレイヤーの最終レイアウトへの描画はサポートされていません。 |
| remove_global_text_engine_resource | bool | r/w | グローバル テキスト エンジン リソースを削除するかどうかを示す値を取得または設定します。- 一部のテキストレイヤー付き PSD ファイルで使用され、処理後に Adobe Photoshop で開けない場合にのみ（主にフォントが欠如したテキストレイヤーが原因）。<br/>            このオプションを使用した後、ユーザーは Photoshop で開いたファイルで次の操作を行う必要があります: メニュー \"Text\" -> \"Process absent fonts\"。その操作後、すべてのテキストが再び表示されます。<br/>            注意: この操作により最終レイアウトが一部変更される可能性があります。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 解像度設定を取得または設定します。 |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | PSD リソースを取得または設定します。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 画像を作成するためのソースを取得または設定します。 |
| update_metadata | bool | r/w | [update metadata] の有無を示す値を取得または設定します。<br/>            値が true の場合、画像を保存する際にメタデータが更新されます。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | ベクトルラスター化オプションを取得または設定します。 |
| version | int | r/w | PSD ファイル バージョンを取得または設定します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP データ コンテナを取得または設定します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

新しい [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) クラスのインスタンスを初期化します。

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

新しい [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | 画像。 |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

新しい [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | オプション。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | このインスタンスの浅いコピーを返します。 |


