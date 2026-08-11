---
title: "クラス TiffOptions"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageOptions.TiffOptions クラス。tiff ファイル形式オプション。幅と高さのタグは画像作成時に幅と高さのパラメータで上書きされるため、直接指定する必要はありません。多くのオプションはデフォルト値を返しますが、これはそのオプションがタグ値として明示的に設定されていることを意味しません。タグが存在するか確認するには Tags プロパティまたは対応する IsTagPresent メソッドを使用してください"
type: docs
weight: 5430
url: /ja/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

tiff ファイル形式のオプションです。幅と高さのタグは、画像作成時に幅と高さのパラメータによって上書きされるため、直接指定する必要はありません。多くのオプションはデフォルト値を返しますが、これはそのオプションがタグ値として明示的に設定されていることを意味しません。タグが存在するか確認するには、Tags プロパティまたは対応する IsTagPresent メソッドを使用してください。

```csharp
public class TiffOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | `TiffOptions` クラスの新しいインスタンスを初期化します。 |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | `TiffOptions` クラスの新しいインスタンスを初期化します。デフォルトではリトルエンディアン方式が使用されます。 |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | `TiffOptions` クラスの新しいインスタンスを初期化します。 |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | `TiffOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | アルファストレージオプションを取得または設定します。`Unspecified` 以外のオプションは、3 つ以上の [`SamplesPerPixel`](./samplesperpixel/) が定義されている場合に使用されます。 |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | アーティストを取得または設定します。 |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | ピクセルあたりのビット数を取得します。 |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | サンプルあたりのビット数を取得または設定します。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | tiff バイトオーダーを示す値を取得または設定します。 |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | カラー マップを取得または設定します。 |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | 圧縮画像の品質を取得または設定します。Jpeg 圧縮と共に使用されます。 |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | 圧縮を取得または設定します。 |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | 著作権情報を取得または設定します。 |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | 日付と時刻を取得または設定します。 |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | デフォルトのメモリ割り当て上限を取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートするときにテキスト描画に使用されるフォント）。デフォルトフォント名を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | ドキュメントの名前を取得または設定します。 |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | EXIF IFD へのポインタを取得または設定します。 |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | FAX T4 オプションを取得または設定します。 |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF ファイル標準を取得または設定します。 |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | バイトビットのフィル順序を取得または設定します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | フルフレームかどうかを示す値を取得または設定します。 |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | ハーフトーンヒントを取得または設定します。 |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | ICC プロファイルストリームを取得または設定します。 |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | 画像の説明を取得または設定します。 |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | 画像の長さを取得または設定します。 |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | 画像の幅を取得または設定します。 |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | インク名を取得または設定します。 |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | 余分なサンプルが存在するかどうかを示す値を取得します。 |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | 画像がタイル状かどうかを示す値を取得します。 |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | `TiffOptions` が適切に構成されているかどうかを示す値を取得します。失敗理由を見つけるには Validate メソッドを使用してください。 |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | 最大サンプル値を取得または設定します。 |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | 最小サンプル値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページオプション |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | 向きを取得または設定します。 |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | ページ名を取得または設定します。 |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | ページ番号タグを取得または設定します。 |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | カラーパレットを取得または設定します。 |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | フォトメトリックを取得または設定します。 |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | 平面構成を取得または設定します。 |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW 圧縮用の予測子を取得または設定します。 |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 取得または設定するのは、進行状況イベント ハンドラーです。 |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | 解像度の単位を取得または設定します。 |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | ストリップあたりの行数を取得または設定します。 |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | サンプル形式を取得または設定します。 |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | ピクセルあたりのサンプル数を取得します。このプロパティの値を変更するには、[`BitsPerSample`](./bitspersample/) プロパティのセッターを使用します。 |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | スキャナの製造元を取得または設定します。 |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | スキャナのモデルを取得または設定します。 |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | 最大サンプル値を取得または設定します。この値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。 |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | 最小サンプル値を取得または設定します。この値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。 |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | ソフトウェアのタイプを取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 画像を作成するソースを取得または設定します。 |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | ストリップのバイト数を取得または設定します。 |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | ストリップのオフセットを取得または設定します。 |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | このサブファイルに含まれるデータの種類に関する一般的な指標を取得または設定します。 |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | タグを取得または設定します。 |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | 対象プリンターを取得または設定します。 |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | しきい値設定を取得または設定します。 |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | タイルのバイト数を取得または設定します。 |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | タイルの長さを取得 ot 設定します。 |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | タイルのオフセットを取得または設定します。 |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | タイルの幅を取得 ot 設定します。 |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | 総ページ数を取得します。 |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | 有効なタグ数を取得します。これは総タグ数ではなく、保持できる可能性のあるタグの数です。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクターラスタライズオプションを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | XMP メタデータ コンテナを取得または設定します。 |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | 画像の作者を取得または設定します。これは Windows Explorer で使用されます。 |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | 画像のコメントを取得または設定します。これは Windows Explorer で使用されます。 |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | 画像の件名を取得または設定します。これは Windows Explorer で使用されます。 |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | X 位置を取得または設定します。 |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Windows Explorer で使用される画像に関する情報を取得または設定します。 |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Windows Explorer で使用される画像に関する情報を取得または設定します。 |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | X 解像度を取得または設定します。 |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | YCbCrCoefficients を取得または設定します。 |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | YCbCr フォトメトリックのサブサンプリング係数を取得または設定します。 |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Y 位置を取得または設定します。 |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Y 解像度を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | 新しいタグを追加します。 |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | タグを追加します。 |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスをクローンします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | タイプでタグのインスタンスを取得します。 |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | オプションにタグが存在するかどうかを判断します。 |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | タグを削除します。 |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | オプションが有効なタグの組み合わせを持つか検証します。 |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | 有効なタグの数を取得します。 |

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

この例では GraphicsPath クラスと Graphics クラスを使用して、Image 表面上に Figure を作成および操作します。例では新しい Image を作成し、GraphicsPath クラスを使用してパスを描画します。最後に Graphics クラスが提供する DrawPath メソッドが呼び出され、表面上にパスが描画されます。最終的に画像は Tiff ファイル形式にエクスポートされます。

```csharp
[C#]

//Image のインスタンスを作成します。
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します。
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします。
    graphics.Clear(Color.Wheat);

    //GraphicsPath クラスのインスタンスを作成します。
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure クラスのインスタンスを作成します。
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure オブジェクトにシェイプを追加します。
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath に Figure オブジェクトを追加します。
    graphicspath.AddFigure(figure);

    //黒色の Pen オブジェクトでパスを描画します。
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions のインスタンスを作成し、さまざまなプロパティを設定します。
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 関連項目

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


