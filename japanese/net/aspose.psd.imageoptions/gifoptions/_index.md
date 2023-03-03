---
title: Class GifOptions
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageOptions.GifOptions クラス. gif ファイル形式の作成オプション
type: docs
weight: 4810
url: /ja/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

gif ファイル形式の作成オプション。

```csharp
public class GifOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | の新しいインスタンスを初期化します`GifOptions`class. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | の新しいインスタンスを初期化します`GifOptions`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | GIF 背景色インデックスを取得または設定します。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | GIF の色解像度を取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します (PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合、ラスターにエクスポートするときにテキストの描画に使用されるフォント)。 デフォルト フォントの適切な名前を取得するには、次のコード スニペットを使用できます。 : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] ファミリー = col.Families; 文字列 defaultFontName = ファミリー[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | パレット補正を適用するかどうかを示す値を取得または設定します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [フル フレーム] かどうかを示す値を取得または設定します。 |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | GIF にトレーラーがあるかどうかを示す値を取得または設定します。 |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | 画像をインターレースする必要がある場合は true. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | パレット エントリが並べ替えられているかどうかを示す値を取得または設定します。 |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | 最大許容ピクセル差を取得または設定します。 0 より大きい場合、非可逆圧縮が使用されます。 最適な非可逆圧縮の推奨値は 80 です。30 は非常に軽い圧縮で、200 は重い圧縮です。 圧縮アルゴリズムの制限により、損失がほとんどない場合に最適に機能します。非常に高い損失レベルでは、それほど多くの利益は得られません. 許容値の範囲は [0, 1000]. です。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページ オプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラー パレットを取得または設定します。 |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | GIF ピクセルの縦横比を取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 進行状況イベント ハンドラーを取得または設定します。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | でイメージを作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクター ラスター化オプションを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | XMP メタデータ コンテナーを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスを複製します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

### 例

この例では、エクスポート目的で SaveOptions 名前空間のさまざまなクラスを使用する方法を示します。 Psd 型の画像は、Image のインスタンスに読み込まれ、いくつかの形式にエクスポートされます。

```csharp
[C#]

// Image クラスのインスタンスに既存の画像をロードする
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //デフォルトのオプションを使用して BMP ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //デフォルトのオプションを使用して JPEG ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //デフォルトのオプションを使用して JPEG 2000 ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //デフォルトのオプションを使用して PNG ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //デフォルトのオプションを使用して TIFF ファイル形式にエクスポートします
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### 関連項目

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* 名前空間 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 組み立て [Aspose.PSD](../../)


