---
title: Class BmpOptions
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageOptions.BmpOptions クラス. bmp ファイル形式の作成オプション
type: docs
weight: 4790
url: /ja/net/aspose.psd.imageoptions/bmpoptions/
---
## BmpOptions class

bmp ファイル形式の作成オプション。

```csharp
public class BmpOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | の新しいインスタンスを初期化します`BmpOptions`class. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | の新しいインスタンスを初期化します`BmpOptions`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | ピクセルあたりの画像ビット数を取得または設定します。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | 圧縮を取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します (PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合、ラスターにエクスポートするときにテキストの描画に使用されるフォント)。 デフォルト フォントの適切な名前を取得するには、次のコード スニペットを使用できます。 : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] ファミリー = col.Families; 文字列 defaultFontName = ファミリー[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [フル フレーム] かどうかを示す値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページ オプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラー パレットを取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 進行状況イベント ハンドラーを取得または設定します。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | でイメージを作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクター ラスター化オプションを取得または設定します。 |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP メタデータ コンテナーを取得または設定します。 |

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


