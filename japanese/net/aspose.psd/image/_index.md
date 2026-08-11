---
title: "Image クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Image クラス。画像はすべての画像タイプの基底クラスです。"
type: docs
weight: 5060
url: /ja/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

画像はすべての画像タイプの基底クラスです。

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 自動調整パレットかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | 画像のピクセルあたりのビット数を取得します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [Container](../../aspose.psd/image/container/) { get; } | `Image` コンテナを取得します。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | ファイル形式の値を取得します。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 画像の高さを取得します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データ読み取りが不要であるかどうかを示す値を取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 画像パレットが使用されているかどうかを示す値を取得します。 |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 画像の幅を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | 指定された作成オプションを使用して新しい画像を作成します。 |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | 指定されたストリームから新しい画像を読み込みます。 |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | 指定されたファイルから新しい画像を読み込みます。 |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | 指定されたストリームから新しい画像を読み込みます。 |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | 指定されたファイルから新しい画像を読み込みます。 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基礎となる [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) からの追加データ読み込みが行われないことを保証します。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトオプションを取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づくオプションを取得します。これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。例えば、1 ビット/ピクセルの白黒 PNG 画像を読み込み、[`Save`](../datastreamsupporter/save/) メソッドで保存すると、出力は 8 ビット/ピクセルの PNG 画像になります。これを回避し、1 ビット/ピクセルの PNG 画像として保存するには、このメソッドを使用して対応する保存オプションを取得し、[`Save`](./save/) メソッドの第2パラメータとして渡します。 |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | 画像のサイズを変更します。デフォルトの NearestNeighbourResample が使用されます。 |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 高さを比例的にリサイズします。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | 幅を比例的にリサイズします。デフォルトの NearestNeighbourResample が使用されます。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 幅を比例的にリサイズします。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 幅を比例的にリサイズします。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 画像を回転、フリップ、または回転とフリップを行います。 |
| [Save](../../aspose.psd/image/save/#save)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 画像のパレットを設定します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | 指定されたストリームから画像をロードできるかどうかを判断します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | 指定されたファイルパスから画像をロードできるかどうかを判断します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | 指定されたストリームから画像をロードできるか、またはオプションで指定された *loadOptions* を使用してロードできるかどうかを判断します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | 指定されたファイルパスから画像をロードできるか、またはオプションで指定されたオープンオプションを使用してロードできるかどうかを判断します。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | ファイル形式を取得します。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | ファイル形式を取得します。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 現在の画像にフィットする矩形を取得します。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 現在の画像にフィットする矩形を取得します。 |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | 比例高さを取得します。 |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | 比例幅を取得します。 |

## 例

この例では、PsdOptions インスタンスの Source プロパティで指定されたディスク上の場所に新しい Image ファイルを作成します。PsdOptions インスタンスの複数のプロパティが実際の画像を作成する前に設定されます。特に、この場合は実際のディスク位置を指す Source プロパティです。

```csharp
[C#]

//PsdOptions のインスタンスを作成し、さまざまなプロパティを設定します。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource のインスタンスを作成し、PsdOptions インスタンスの Source として割り当てます。
//2 番目の Boolean パラメーターは、作成するファイルが一時的かどうかを決定します。
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image のインスタンスを作成し、Create メソッドを呼び出して PsdOptions のインスタンスで初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //画像処理を行います。

    // すべての変更を保存します。
    image.Save();
}
```

### 関連項目

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


