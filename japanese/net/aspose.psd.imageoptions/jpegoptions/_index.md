---
title: "JpegOptions クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageOptions.JpegOptions クラス。jpeg ファイル形式の作成オプション"
type: docs
weight: 5330
url: /ja/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

jpeg ファイル形式の作成オプション。

```csharp
public class JpegOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | `JpegOptions` クラスの新しいインスタンスを初期化します。 |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | `JpegOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | ロスレス JPEG 画像のチャンネルあたりビット数を取得または設定します。現在、2 ビットから 8 ビットまでサポートしています。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg 画像用の宛先 CMYK カラープロファイルです。画像の保存に使用します。正しい色変換のために RGBColorProfile とペアで使用する必要があります。 |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | jpeg 画像のカラータイプを取得または設定します。 |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | jpeg ファイルのコメントを取得または設定します。 |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | 圧縮タイプを取得または設定します。 |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | デフォルトのメモリ割り当て上限を取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートするときにテキスト描画に使用されるフォント）。デフォルトフォント名を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | EXIF データコンテナを取得または設定します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | フルフレームかどうかを示す値を取得または設定します。 |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | 各コンポーネントの水平サブサンプリングを取得または設定します。 |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | jfif を取得または設定します。 |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | ニアロスレス符号化のための JPEG-LS 差分境界 (JPEG-LS 仕様の NEAR パラメータ) を取得または設定します。 |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS のインタリーブモードを取得または設定します。 |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS のプリセットパラメータを取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページオプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラーパレットを取得または設定します。 |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | アルファチャンネルが存在する場合、赤、緑、青の各コンポーネントを背景色と混合すべきかを示す値を取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 取得または設定するのは、進行状況イベント ハンドラーです。 |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | 画像の品質を取得または設定します。 |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD オプティマイザ設定を取得または設定します。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | 解像度の単位を取得または設定します。 |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK JPEG 画像用の宛先 RGB カラープロファイルです。画像の保存に使用します。正しい色変換のためには CMYKColorProfile とペアで使用する必要があります。 |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | スケーリングされた品質です。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 画像を作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクターラスタライズオプションを取得または設定します。 |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | 各コンポーネントの垂直サブサンプリングを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP メタデータ コンテナを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスをクローンします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

## 例

この例は Aspose.PSD for .Net API を使用して画像を JPEG 形式に変換する方法を示しています。この目的を達成するために、既存の画像を読み込み、JPEG ファイル形式に変換します。

```csharp
[C#]

//画像クラスのインスタンスを作成し、ファイルパスを介して既存のファイルで初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions クラスのインスタンスを作成します。
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //出力画像のサイズを小さくするために品質を 50% に設定します。
    jpegOptions.Quality = 50;

    //EXIF コメントを設定します。
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //指定された JpegOptions 設定で画像をディスク上の場所に保存します。
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

この例は System.IO.Stream を使用して新しい画像ファイルを作成する方法を示しています。

```csharp
[C#]

//PsdOptions のインスタンスを作成し、さまざまなプロパティを設定します。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream のインスタンスを作成します。
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions インスタンスの source プロパティを定義します。
//2 番目のブールパラメータは、スコープを抜けたときに Stream が破棄されるかどうかを決定します。
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image のインスタンスを作成し、PsdOptions をパラメータとして Create メソッドを呼び出して Image オブジェクトを初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //画像処理を行います。
}
```

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


