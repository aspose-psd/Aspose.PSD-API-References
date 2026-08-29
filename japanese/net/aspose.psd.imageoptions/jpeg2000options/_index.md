---
title: "クラス Jpeg2000Options"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageOptions.Jpeg2000Options クラス。Jpeg2000 ファイル形式のオプション"
type: docs
weight: 5320
url: /ja/net/aspose.psd.imageoptions/jpeg2000options/
---
{{< psd/tize >}}
## Jpeg2000Options class

Jpeg2000 ファイル形式のオプション。

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | `Jpeg2000Options` クラスの新しいインスタンスを初期化します。 |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | `Jpeg2000Options` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | JPEG2000 コーデックを取得または設定します |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Jpeg コメントマーカーを取得または設定します。 |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | 圧縮率の配列を取得または設定します。連続するレイヤーごとに異なる圧縮率があります。各品質レベルで指定されたレートは希望する圧縮係数です。圧縮率は低くする必要があります。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートするときにテキスト描画に使用されるフォント）。デフォルトフォント名を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | フルフレームかどうかを示す値を取得または設定します。 |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | 不可逆 DWT 9-7（true）を使用するか、可逆 DWT 5-3 圧縮（デフォルト）を使用するかを示す値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページオプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラーパレットを取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 取得または設定するのは、進行状況イベント ハンドラーです。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 画像を作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクターラスタライズオプションを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | XMP メタデータ コンテナを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスをクローンします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

## 例

この例は、エクスポート目的で SaveOptions 名前空間のさまざまなクラスの使用方法を示しています。Psd タイプの画像が Image のインスタンスにロードされ、複数の形式にエクスポートされます。

```csharp
[C#]

//既存の画像を Image クラスのインスタンスにロードします
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //デフォルト オプションを使用して BMP ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //デフォルト オプションを使用して JPEG ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //デフォルト オプションを使用して JPEG 2000 ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //デフォルト オプションを使用して PNG ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //デフォルト オプションを使用して TIFF ファイル形式にエクスポートします
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### 関連項目

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


