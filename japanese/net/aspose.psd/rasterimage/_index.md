---
title: "クラス RasterImage"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.RasterImage クラス。ラスター画像を表し、ラスターグラフィック操作をサポートします。"
type: docs
weight: 5820
url: /ja/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

ラスターグラフィック操作をサポートするラスター画像を表します。

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 自動調整パレットかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 画像のピクセルあたりのビット数を取得します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../image/) コンテナを取得します。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | ファイル形式の値を取得します。 |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | このインスタンスがアルファを持つかどうかを示す値を取得します。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 画像に透明色があるかどうかを示す値を取得します。 |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 画像の高さを取得します。 |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | `RasterImage` の水平解像度（インチあたりのピクセル数）を取得または設定します。 |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | この画像の不透明度を取得します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データ読み取りが不要であるかどうかを示す値を取得します。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 生データのロードが利用可能かどうかを示す値を取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 画像コンポーネントが事前乗算されている必要があるかどうかを示す値を取得または設定します。 |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | カスタムカラーコンバータを取得または設定します |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 生データ形式を取得します。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 現在の生データ設定を取得します。これらの設定を使用すると、データは変換せずにロードされることに注意してください。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | インデックスカラーコンバータを取得または設定します |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 生ラインサイズ（バイト単位）を取得します。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 画像の透過色を取得します。 |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMPメタデータを更新するかどうかを示す値を取得または設定します。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 画像パレットが使用されているかどうかを示す値を取得します。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 生データロードが利用可能な場合に、生データロードを使用するかどうかを示す値を取得または設定します。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | `RasterImage` の垂直解像度（インチあたりのピクセル数）を取得または設定します。 |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 画像の幅を取得します。 |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMPメタデータを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | 画像の明るさを調整します。 |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | 画像のコントラスト調整 |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | 画像のガンマ補正。 |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | 画像のガンマ補正。 |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Bradley の適応的閾値アルゴリズム（積分画像閾値）を使用した画像の二値化 |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Bradley の適応的閾値アルゴリズム（積分画像閾値）を使用した画像の二値化 |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | 事前定義されたしきい値を使用した画像の二値化 |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Otsuしきい値処理による画像の二値化 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基礎となる [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) からの追加データ読み込みが行われないことを保証します。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | 指定された矩形を切り取ります。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | シフト付きで画像をトリミングします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | 現在の画像にディザ処理を実行します。 |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 現在の画像にディザ処理を実行します。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 指定された矩形をフィルタリングします。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトオプションを取得します。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | デフォルトの生データ配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | リソース画像が最後に変更された日時を取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づくオプションを取得します。これにより、元画像のビット深度やその他のパラメータを変更せずに保持できます。例えば、1ビット/ピクセルの白黒 PNG 画像を読み込み、[`Save`](../datastreamsupporter/save/) メソッドで保存すると、8ビット/ピクセルの PNG 画像が出力されます。これを回避し、1ビット/ピクセルの PNG 画像として保存するには、このメソッドで対応する保存オプションを取得し、[`Save`](../image/save/) メソッドの第2パラメータとして渡します。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 画像のピクセルを取得します。パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドを使用すると、重大なパフォーマンス問題が発生する可能性があります。より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 傾き角度を取得します。このメソッドはスキャンされたテキスト文書に適用でき、スキャン時の傾き角度を判定します。 |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | 画像をグレースケール表現に変換する |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32ビット ARGB ピクセルを読み込みます。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64ビット ARGB ピクセルを読み込みます。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK 形式のピクセルを読み込みます。 |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK 形式でピクセルを読み込みます。このメソッドは非推奨です。より効果的な [`LoadCmyk32Pixels`](./loadcmyk32pixels/) メソッドを使用してください。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32ビット ARGB ピクセルをパック単位で部分的に読み込みます。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | ピクセルをパック単位で部分的に読み込みます。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | ピクセルを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | 角度を正規化します。このメソッドは、スキャンされたテキスト文書の歪んだスキャンを除去するために適用できます。このメソッドは [`GetSkewAngle`](./getskewangle/) と [`Rotate`](./rotate/) メソッドを使用します。 |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | 角度を正規化します。このメソッドは、スキャンされたテキスト文書の歪んだスキャンを除去するために適用できます。このメソッドは [`GetSkewAngle`](./getskewangle/) と [`Rotate`](./rotate/) メソッドを使用します。 |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 指定されたスキャンラインインデックスでスキャンライン全体を読み取ります。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 指定されたスキャンラインインデックスでスキャンライン全体を読み取ります。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | 許容差を持たせてある色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | 許容差を持たせてある色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | すべての非透明色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保ちます。注意: 透明度のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトの NearestNeighbourResample が使用されます。 |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | 拡張オプションを使用して画像のサイズを変更します。 |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例的にリサイズします。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例的にリサイズします。デフォルトの NearestNeighbourResample が使用されます。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例的にリサイズします。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例的にリサイズします。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | 画像を中心を基準に回転させます。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | 画像を中心を基準に回転させます。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 画像を回転、フリップ、または回転とフリップを行います。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32ビット ARGB ピクセルを保存します。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | ピクセルを保存します。 |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | ピクセルを保存します。このメソッドは非推奨です。より効果的な [`SaveCmyk32Pixels`](./savecmyk32pixels/) メソッドを使用してください。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | ピクセルを保存します。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 生データを保存します。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 画像のパレットを設定します。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 指定された位置に画像ピクセルを設定します。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | `RasterImage` の解像度を設定します。 |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | ラスタ画像をビットマップに変換します。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |

## 例

この例では、Color 型の配列にピクセル情報をロードし、配列を操作して画像に戻す方法を示します。これらの操作を実行するために、MemoryStream オブジェクトを使用して新しい Image ファイル（PSD 形式）を作成します。

```csharp
[C#]

//MemoryStream のインスタンスを作成します。
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions のインスタンスを作成し、Source プロパティを含むさまざまなプロパティを設定します。
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image のインスタンスを作成します。
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //画像の境界を領域として指定して、画像のピクセルを取得します
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //配列をループし、代替インデックスピクセルの色を設定します
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //インデックスピクセルの色を黄色に設定します
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //インデックスピクセルの色を青に設定します
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //画像にピクセルの変更を適用します
        image.SavePixels(image.Bounds, pixels);

        // すべての変更を保存します。
        image.Save();
    }

    //MemoryStream をファイルに書き込みます
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 関連項目

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


