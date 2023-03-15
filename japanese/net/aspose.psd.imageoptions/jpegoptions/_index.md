---
title: Class JpegOptions
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageOptions.JpegOptions クラス. jpeg ファイル形式作成オプション.
type: docs
weight: 4840
url: /ja/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

jpeg ファイル形式作成オプション.

```csharp
public class JpegOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | の新しいインスタンスを初期化します`JpegOptions`class. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | の新しいインスタンスを初期化します`JpegOptions`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | ロスレス jpeg 画像のチャネルあたりのビット数を取得または設定します。現在、チャネルごとに 2 ～ 8 ビットをサポートしています。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg 画像の宛先 CMYK カラー プロファイル。画像の保存に使用します。正しい色変換を行うには、RGBColorProfile とペアにする必要があります。 |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | jpeg 画像の色の種類を取得または設定します。 |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | jpeg ファイルのコメントを取得または設定します。 |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | 圧縮タイプを取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します (PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合、ラスターにエクスポートするときにテキストの描画に使用されるフォント)。 デフォルト フォントの適切な名前を取得するには、次のコード スニペットを使用できます。 : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] ファミリー = col.Families; 文字列 defaultFontName = ファミリー[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | exif データを取得または設定する container |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [フル フレーム] かどうかを示す値を取得または設定します。 |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | 各コンポーネントの水平サブサンプリングを取得または設定します。 |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | jfif を取得または設定します。 |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | ニア ロスレス コーディングの JPEG-LS 差分バウンドを取得または設定します (JPEG-LS 仕様の NEAR パラメータ). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS インターリーブ モードを取得または設定します。 |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS プリセット パラメータを取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページ オプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラー パレットを取得または設定します。 |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | アルファ チャネルが存在する場合、赤、緑、および青のコンポーネントを背景色と混合するかどうかを示す値を取得または設定します. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 進行状況イベント ハンドラーを取得または設定します。 |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | 画質を取得または設定します。 |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD オプティマイザーの設定を取得または設定します。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | 解像度の単位を取得または設定します。 |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg 画像の宛先 RGB カラー プロファイル。画像の保存に使用します。正しい色変換を行うには、CMYKColorProfile とペアにする必要があります。 |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | スケーリングされた品質. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | でイメージを作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクター ラスター化オプションを取得または設定します。 |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | 各コンポーネントの垂直サブサンプリングを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP メタデータ コンテナーを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスを複製します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

### 例

この例では、Aspose.PSD for .Net API を使用して画像を Jpeg 形式に変換する方法を示します。この目標を達成するために、この例では既存の画像を読み込み、それを Jpeg ファイル形式に変換します。

```csharp
[C#]

//画像クラスのインスタンスを作成し、ファイル パスを介して既存のファイルで初期化します
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions クラスのインスタンスを作成します
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //品質を 50% に設定して、出力画像のサイズを小さくします。
    jpegOptions.Quality = 50;

    //exif コメントを設定します。
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //指定された JpegOptions 設定で画像をディスクの場所に保存します
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

この例では、System.IO.Stream を使用して新しいイメージ ファイルを作成する方法を示します。

```csharp
[C#]

//PsdOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// System.IO.Stream のインスタンスを作成します
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions のインスタンスのソース プロパティを定義します
// 2 番目のブール値パラメーターは、Stream がスコープ外になった後に破棄されるかどうかを決定します
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// Image のインスタンスを作成し、PsdOptions をパラメーターとして Create メソッドを呼び出して Image オブジェクトを初期化します   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 画像処理を行います
}
```

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


