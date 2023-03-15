---
title: Class TiffOptions
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageOptions.TiffOptions クラス. tiff ファイル形式のオプション 幅と高さのタグは画像の作成時に幅と高さのパラメーターによって上書きされるため直接指定する必要がないことに注意してください 多くのオプションがデフォルト値を返すことに注意してくださいこのオプションはタグ値として明示的に設定されますタグが存在することを確認するにはTags プロパティまたは対応する IsTagPresent メソッドを使用します
type: docs
weight: 4940
url: /ja/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

tiff ファイル形式のオプション。 幅と高さのタグは、画像の作成時に幅と高さのパラメーターによって上書きされるため、直接指定する必要がないことに注意してください。 多くのオプションがデフォルト値を返すことに注意してください。このオプションは、タグ値として明示的に設定されます。タグが存在することを確認するには、Tags プロパティまたは対応する IsTagPresent メソッドを使用します。

```csharp
public class TiffOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | の新しいインスタンスを初期化します`TiffOptions`class. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | の新しいインスタンスを初期化します`TiffOptions`クラス。デフォルトでは、リトル エンディアン規則が使用されます。 |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | の新しいインスタンスを初期化します`TiffOptions`class. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | の新しいインスタンスを初期化します`TiffOptions`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | アルファ ストレージ オプションを取得または設定します。以外のオプションUnspecified は 3 つ以上ある場合に使用されます[`SamplesPerPixel`](./samplesperpixel/)定義済み. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | アーティストを取得または設定します。 |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | ピクセルあたりのビット数を取得します。 |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | サンプルあたりのビット数を取得または設定します。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | tiff バイト順を示す値を取得または設定します。 |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | カラー マップを取得または設定します。 |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | 圧縮された画像の品質を取得または設定します。 JPEG 圧縮で使用されます。 |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | 圧縮を取得または設定します。 |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | 著作権を取得または設定します。 |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | 日付と時刻を取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します (PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合、ラスターにエクスポートするときにテキストの描画に使用されるフォント)。 デフォルト フォントの適切な名前を取得するには、次のコード スニペットを使用できます。 : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] ファミリー = col.Families; 文字列 defaultFontName = ファミリー[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | ドキュメントの名前を取得または設定します。 |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | EXIF IFD へのポインターを取得または設定します。 |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | ファックス t4 オプションを取得または設定します。 |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF ファイル規格を取得または設定します。 |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | バイト ビットのフィル順序を取得または設定します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [フル フレーム] かどうかを示す値を取得または設定します。 |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | ハーフトーン ヒントを取得または設定します。 |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Icc プロファイル ストリームを取得または設定します。 |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | 画像の説明を取得または設定します。 |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | 画像の長さを取得または設定します。 |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | 画像の幅を取得または設定します。 |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | インク名を取得または設定します。 |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | 余分なサンプルが存在するかどうかを示す値を取得します. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | 画像が並べて表示されているかどうかを示す値を取得します。 |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | かどうかを示す値を取得します。`TiffOptions`適切に構成されています。 Validate メソッドを使用して、失敗の理由を見つけます。 |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | 最大サンプル値を取得または設定します。 |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | 最小サンプル値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページ オプション |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | 向きを取得または設定します。 |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | ページ名を取得または設定します。 |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | ページ番号タグを取得または設定します。 |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | カラー パレットを取得または設定します。 |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | フォトメトリックを取得または設定します。 |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | 平面構成を取得または設定します。 |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW 圧縮の予測子を取得または設定します。 |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 進行状況イベント ハンドラーを取得または設定します。 |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | 解像度の単位を取得または設定します。 |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | ストリップごとの行を取得または設定します。 |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | サンプル形式を取得または設定します。 |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | ピクセルごとのサンプルを取得します。このプロパティ値を変更するには、[`BitsPerSample`](./bitspersample/)プロパティ setter. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | スキャナーの製造元を取得または設定します。 |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | スキャナー モデルを取得または設定します。 |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | 最大サンプル値を取得または設定します。値には、サンプル データに最も一致するフィールド タイプがあります (Byte、Short、または Long タイプ). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | 最小サンプル値を取得または設定します。値には、サンプル データに最も一致するフィールド タイプがあります (Byte、Short、または Long タイプ). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | ソフトウェア タイプを取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | でイメージを作成するソースを取得または設定します。 |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | ストリップ バイト数を取得または設定します。 |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | ストリップのオフセットを取得または設定します。 |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | このサブファイルに含まれるデータの種類の一般的な表示を取得または設定します。 |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | タグを取得または設定します。 |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | ターゲット プリンターを取得または設定します。 |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | しきい値を取得または設定します。 |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | タイルのバイト数を取得または設定します。 |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | タイルの長さを取得または設定します。 |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | タイル オフセットを取得または設定します。 |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | 取得またはタイル幅の設定. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | 総ページ数を取得します。 |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | 有効なタグ数を取得します。これはタグの総数ではなく、保持できるタグの数です。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクター ラスター化オプションを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | XMP メタデータ コンテナーを取得または設定します。 |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Windows エクスプローラーで使用される画像作成者を取得または設定します。 |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Windows エクスプローラーで使用される画像のコメントを取得または設定します。 |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Windows エクスプローラーで使用される対象の画像を取得または設定します。 |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | x 位置を取得または設定します。 |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Windows エクスプローラーで使用されるイメージに関する情報を取得または設定します。 |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Windows エクスプローラーで使用されるイメージに関する情報を取得または設定します。 |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | x 解像度を取得または設定します。 |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | YCbCrCoefficients. を取得または設定します |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | YCbCr 測光のサブサンプリング係数を取得または設定します。 |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | y 位置を取得または設定します。 |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | y 解像度を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | 新しいタグを追加します。 |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | タグを追加します。 |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスを複製します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | タイプ別にタグのインスタンスを取得します。 |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | タグがオプションに存在するかどうかを決定します. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | タグを削除します。 |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | オプションにタグの有効な組み合わせがあるかどうかを検証します |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | 有効なタグ数を取得します。 |

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

この例では、GraphicsPath および Graphics クラスを使用して、イメージ サーフェス上に Figure を作成および操作します。例では、新しい Image を作成し、GraphicsPath クラスを使用してパスを描画します。最後に、Graphics クラスによって公開された DrawPath メソッドが呼び出され、表面にパスがレンダリングされます。最後に、画像が Tiff ファイル形式にエクスポートされます。

```csharp
[C#]

//Image のインスタンスを作成する 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics クラスのインスタンスを作成して初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // グラフィック サーフェスをクリアする
    graphics.Clear(Color.Wheat);

    // GraphicsPath クラスのインスタンスを作成します
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // Figure クラスのインスタンスを作成
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Figure オブジェクトにシェイプを追加
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath に Figure オブジェクトを追加
    graphicspath.AddFigure(figure);

    //色が黒の Pen オブジェクトでパスを描画します
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // TiffOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 関連項目

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* 名前空間 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 組み立て [Aspose.PSD](../../)


