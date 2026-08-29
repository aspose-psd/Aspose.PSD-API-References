---
title: "クラス VectorImage"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.VectorImage クラス。ベクター画像はすべての種類のベクター画像の基底クラスです"
type: docs
weight: 6220
url: /ja/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

ベクター画像はすべてのベクター画像タイプの基底クラスです。

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | 画像の高さを取得します。 |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | オブジェクトの高さをインチ単位で取得します。 |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データ読み取りが不要であるかどうかを示す値を取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | オブジェクトのサイズをインチ単位で取得します。 |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | 画像パレットが使用されているかどうかを示す値を取得します。 |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | 画像の幅を取得します。 |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | オブジェクトの幅をインチ単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基礎となる [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) からの追加データ読み込みが行われないことを保証します。 |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトオプションを取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づくオプションを取得します。これにより、元画像のビット深度やその他のパラメータを変更せずに保持できます。例えば、1ビット/ピクセルの白黒 PNG 画像を読み込み、[`Save`](../datastreamsupporter/save/) メソッドで保存すると、8ビット/ピクセルの PNG 画像が出力されます。これを回避し、1ビット/ピクセルの PNG 画像として保存するには、このメソッドで対応する保存オプションを取得し、[`Save`](../image/save/) メソッドの第2パラメータとして渡します。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトの NearestNeighbourResample が使用されます。 |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例的にリサイズします。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例的にリサイズします。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例的にリサイズします。デフォルトの NearestNeighbourResample が使用されます。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例的にリサイズします。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例的にリサイズします。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 画像を回転、フリップ、または回転とフリップを行います。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 画像のパレットを設定します。 |

### 関連項目

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


