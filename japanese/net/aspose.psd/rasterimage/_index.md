---
title: Class RasterImage
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.RasterImage クラス. ラスター グラフィック操作をサポートするラスター イメージを表します
type: docs
weight: 5320
url: /ja/net/aspose.psd/rasterimage/
---
## RasterImage class

ラスター グラフィック操作をサポートするラスター イメージを表します。

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | パレットを自動調整するかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | ピクセルあたりの画像ビット数を取得します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [Container](../../aspose.psd/image/container/) { get; } | を取得します[`Image`](../image/)コンテナ. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータ ストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | ファイル形式の値を取得 |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | このインスタンスがアルファを持っているかどうかを示す値を取得します. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | 画像に透明色があるかどうかを示す値を取得します. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 画像の高さを取得します. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | 水平方向の解像度を取得または設定します (1 インチあたりのピクセル数)。`RasterImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | この画像の不透明度を取得します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要かどうかを示す値を取得します。 |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | 生データの読み込みが可能かどうかを示す値を取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラー パレットを取得または設定します。ピクセルが直接表現されている場合、カラー パレットは使用されません。 |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | 画像コンポーネントをあらかじめ乗算する必要があるかどうかを示す値を取得または設定します. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | カスタム カラー コンバーターを取得または設定します |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | 生データ形式を取得します。 |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | 現在の生データ設定を取得します。これらの設定を使用する場合、データは変換されずに読み込まれることに注意してください。 |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | パレット インデックスが範囲外の場合に使用するフォールバック インデックスを取得または設定します |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | インデックス付きカラー コンバーターを取得または設定します |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | 生の行サイズをバイト単位で取得します。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | 画像の透明色を取得します. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP メタデータを更新するかどうかを示す値を取得または設定します。 |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | 生データの読み込みが可能な場合に、生データの読み込みを使用するかどうかを示す値を取得または設定します。 |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | この解像度の垂直方向の解像度 (1 インチあたりのピクセル数) を取得または設定します`RasterImage` . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 画像の幅を取得します. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP メタデータを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | 画像の明るさを調整します。 |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | 画像のコントラスト |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | 画像のガンマ補正. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | 画像のガンマ補正. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | インテグラル イメージしきい値処理を使用した Bradley の適応しきい値処理アルゴリズムを使用したイメージの 2 値化 |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | インテグラル イメージしきい値処理を使用した Bradley の適応しきい値処理アルゴリズムを使用したイメージの 2 値化 |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | 事前定義されたしきい値による画像の 2 値化 |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | 大津閾値処理による画像の二値化 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基盤から追加のデータ読み込みが実行されないようにします[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式で画像を保存できるかどうかを決定します。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | 指定された長方形をトリミングします。 |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | シフトで画像をトリミングします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | 現在の画像でディザリングを実行します。 |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | 現在の画像でディザリングを実行します。 |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | 指定された四角形をフィルタリングします。 |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトのオプションを取得します。 |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | 部分ピクセル ローダーを使用してデフォルトのピクセル配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | デフォルトの生データ配列を取得します。 |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | 部分ピクセル ローダーを使用して、デフォルトの生データ配列を取得します。 |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | リソース イメージが最後に変更された日時を取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づいてオプションを取得します. これは、元の画像のビット深度やその他のパラメーターを変更しないで保持するのに役立ちます. たとえば、1 ビットあたり 1 ビットの白黒 PNG 画像をロードし、 the を使用して保存します[`Save`](../datastreamsupporter/save/) これを回避し、1 ピクセルあたり 1 ビットの PNG 画像を保存するには、このメソッドを使用して対応する保存オプションを取得し、 を[`Save`](../image/save/) 番目のパラメーターとしてのメソッド。 |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | 画像ピクセルを取得します。 |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | 傾斜角度を取得します。 このメソッドは、スキャン時の傾斜角度を決定するために、スキャンされたテキスト ドキュメントに適用されます。 |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | グレースケール表現への画像の変換 |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32 ビット ARGB ピクセルをロードします。 |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64 ビット ARGB ピクセルをロードします。 |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | ピクセルを CMYK 形式で読み込みます。 |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32 ビット ARGB ピクセルを部分的にパックで読み込みます。 |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | パック単位で部分的にピクセルを読み込みます。 |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | ピクセルを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | 生データを読み込みます。 |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | 角度を正規化します。 この方法は、スキャンされたテキスト ドキュメントに適用され、スキャンの歪みを取り除きます。 この方法は、[`GetSkewAngle`](./getskewangle/)と[`Rotate`](./rotate/)メソッド. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | 角度を正規化します。 この方法は、スキャンされたテキスト ドキュメントに適用され、スキャンの歪みを取り除きます。 この方法は、[`GetSkewAngle`](./getskewangle/)と[`Rotate`](./rotate/)メソッド. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | 指定されたスキャン ライン インデックスでスキャン ライン全体を読み取ります。 |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | 指定されたスキャン ライン インデックスでスキャン ライン全体を読み取ります。 |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | ある色を別の許容差で置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | ある色を別の許容差で置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | すべての不透明な色を新しい色に置き換え、元のアルファ値を維持して滑らかなエッジを保存します。 |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | すべての不透明な色を新しい色に置き換え、元のアルファ値を維持して滑らかなエッジを保存します。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | 拡張オプションで画像のサイズを変更します。 |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例してサイズ変更します。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例してサイズ変更します。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | 画像を中心に回転します。 |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | 画像を中心に回転します。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 画像を回転、反転、または回転して反転します。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32 ビット ARGB ピクセルを保存します。 |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | ピクセルを保存します。 |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | ピクセルを保存します。 |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | 生データを保存します。 |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | 画像パレットを設定します。 |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | 指定された位置にイメージ ピクセルを設定します。 |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | この解像度を設定します`RasterImage` . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | ラスター イメージをビットマップに変換します。 |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | スキャン ライン全体を指定されたスキャン ライン インデックスに書き込みます。 |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | スキャン ライン全体を指定されたスキャン ライン インデックスに書き込みます。 |

### 例

この例では、Type Color の配列にピクセル情報をロードし、配列を操作して画像に戻す方法を示します。これらの操作を実行するために、この例では、MemoryStream オブジェクトを使用して新しいイメージ ファイル (PSD 形式) を作成します。

```csharp
[C#]

//MemoryStream のインスタンスを作成する
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions のインスタンスを作成し、Source プロパティを含むさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image のインスタンスを作成する
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //領域を画像境界として指定して、画像のピクセルを取得します
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //配列をループし、代替インデックス付きピクセルの色を設定します
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //インデックス付きピクセルの色を黄色に設定
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //インデックス付きピクセルの色を青に設定
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // ピクセルの変更を画像に適用します
        image.SavePixels(image.Bounds, pixels);

        // すべての変更を保存します。
        image.Save();
    }

    //メモリストリームをファイルに書き込む
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 関連項目

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


