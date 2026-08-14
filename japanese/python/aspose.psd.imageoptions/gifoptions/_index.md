---
title: "GifOptions クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | 新しい [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) クラスのインスタンスを初期化します。 |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | 新しい [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | GIF の背景色インデックスを取得または設定します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| color_resolution | byte | r/w | GIF の色解像度を取得または設定します。 |
| default_replacement_font | string | r/w | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートする際にテキスト描画に使用されるフォント）。<br/>            正しいデフォルトフォント名を取得するには、次のコードスニペットを使用できます：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| do_palette_correction | bool | r/w | パレット補正が適用されるかどうかを示す値を取得または設定します。 |
| full_frame | bool | r/w | [full frame] かどうかを示す値を取得または設定します。 |
| has_trailer | bool | r/w | GIF にトレーラーがあるかどうかを示す値を取得または設定します。 |
| interlaced | bool | r/w | 画像をインターレース化すべき場合は true。 |
| is_palette_sorted | bool | r/w | パレットエントリがソートされているかどうかを示す値を取得または設定します。 |
| max_diff | int | r/w | 許容される最大ピクセル差を取得または設定します。0 より大きい場合、非可逆圧縮が使用されます。<br/>            最適な非可逆圧縮の推奨値は 80 です。30 は非常に軽い圧縮、200 は重い圧縮です。<br/>            ほとんど損失が導入されない場合に最適に機能し、圧縮アルゴリズムの制限により非常に高い損失レベルではそれほど大きな効果が得られません。<br/>            許容値の範囲は [0, 1000] です。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | マルチページオプション |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。 |
| pixel_aspect_ratio | byte | r/w | GIF のピクセルアスペクト比を取得または設定します。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 解像度設定を取得または設定します。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 画像を作成するためのソースを取得または設定します。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | ベクトルラスター化オプションを取得または設定します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータ コンテナを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

新しい [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) クラスのインスタンスを初期化します。

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

新しい [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | GIF のオプション。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | このインスタンスの浅いコピーを返します。 |


