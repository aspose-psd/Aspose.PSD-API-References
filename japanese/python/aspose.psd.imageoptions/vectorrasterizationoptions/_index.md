---
title: "VectorRasterizationOptions クラス"
type: docs
weight: 150
url: /ja/python-net/aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.VectorRasterizationOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 背景色を取得または設定します。 |
| border_x | float | r/w | X 境界を取得または設定します。 |
| border_y | float | r/w | Y 境界を取得または設定します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| center_drawing | bool | r/w | 中心描画かどうかを示す値を取得または設定します。 |
| default_replacement_font | string | r/w | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートする際にテキスト描画に使用されるフォント）。<br/>            正しいデフォルトフォント名を取得するには、次のコードスニペットを使用できます：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 前景色を取得または設定します。 |
| full_frame | bool | r/w | [full frame] かどうかを示す値を取得または設定します。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | マルチページオプション |
| page_height | float | r/w | ページの高さを取得または設定します。 |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | ページサイズを取得または設定します。 |
| page_width | float | r/w | ページの幅を取得または設定します。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 解像度設定を取得または設定します。 |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | スムージングモードを取得または設定します。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 画像を作成するためのソースを取得または設定します。 |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | テキストのレンダリングヒントを取得または設定します。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | ベクトルラスター化オプションを取得または設定します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータ コンテナを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | コピー先。 |


### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | このインスタンスの浅いコピーを返します。 |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

コピー先。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | ベクトルラスタライズオプションです。 |

