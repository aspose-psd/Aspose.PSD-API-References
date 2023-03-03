---
title: Class Image
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Image クラス. 画像はすべての種類の画像の基本クラスです
type: docs
weight: 4590
url: /ja/net/aspose.psd/image/
---
## Image class

画像は、すべての種類の画像の基本クラスです。

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | パレットを自動調整するかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | ピクセルあたりの画像ビット数を取得します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [Container](../../aspose.psd/image/container/) { get; } | を取得します`Image`コンテナ. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータ ストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | ファイル形式の値を取得 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | 画像の高さを取得します. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要かどうかを示す値を取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラー パレットを取得または設定します。ピクセルが直接表現されている場合、カラー パレットは使用されません。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| abstract [Width](../../aspose.psd/image/width/) { get; } | 画像の幅を取得します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | 指定された作成オプションを使用して新しいイメージを作成します。 |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | 指定されたストリームから新しい画像を読み込みます。 |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | 指定したファイルから新しい画像を読み込みます。 |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | 指定されたストリームから新しい画像を読み込みます。 |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | 指定したファイルから新しい画像を読み込みます。 |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基盤から追加のデータ読み込みが実行されないようにします[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式で画像を保存できるかどうかを決定します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトのオプションを取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づいてオプションを取得します. これは、元の画像のビット深度やその他のパラメーターを変更しないで保持するのに役立ちます. たとえば、1 ビットあたり 1 ビットの白黒 PNG 画像をロードし、 the を使用して保存します[`Save`](../datastreamsupporter/save/) これを回避し、1 ピクセルあたり 1 ビットの PNG 画像を保存するには、このメソッドを使用して対応する保存オプションを取得し、 を[`Save`](./save/) 番目のパラメーターとしてのメソッド。 |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | 画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | 高さを比例してサイズ変更します。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | 幅を比例してサイズ変更します。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 画像を回転、反転、または回転して反転します。 |
| [Save](../../aspose.psd/image/save/#save)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 画像パレットを設定します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | 指定されたストリームからイメージをロードできるかどうかを決定します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | 指定したファイル パスからイメージをロードできるかどうかを判断します。 |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | 指定されたストリームから、オプションで指定されたストリームを使用してイメージをロードできるかどうかを決定します*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | 指定されたファイル パスから、オプションで指定された開くオプションを使用してイメージをロードできるかどうかを決定します。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | ファイル形式を取得します。 |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | ファイル形式を取得します。 |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | 現在の画像に合う四角形を取得します. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | 現在の画像に合う四角形を取得します. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | 比例高さを取得します。 |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | プロポーショナル幅を取得します。 |

### 例

この例では、PsdOptions インスタンスの Source プロパティで指定されたディスクの場所に新しいイメージ ファイルを作成します。実際のイメージを作成する前に、PsdOptions インスタンスのいくつかのプロパティが設定されます。特に、この場合、実際のディスクの場所を参照する Source プロパティ。

```csharp
[C#]

// PsdOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource のインスタンスを作成し、それを PsdOptions のインスタンスの Source として割り当てます
//2 番目のブール値パラメーターは、作成するファイルが IsTemporal かどうかを決定します
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// Image のインスタンスを作成し、Create メソッドを呼び出して PsdOptions のインスタンスで初期化します
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 画像処理を行います

    // すべての変更を保存
    image.Save();
}
```

### 関連項目

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


