---
title: Class VectorImage
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.VectorImage クラス. ベクター イメージはすべてのタイプのベクター イメージの基本クラスです
type: docs
weight: 5720
url: /ja/net/aspose.psd/vectorimage/
---
## VectorImage class

ベクター イメージは、すべてのタイプのベクター イメージの基本クラスです。

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | 画像の高さを取得します. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | オブジェクトの高さをインチで取得します. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要かどうかを示す値を取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラー パレットを取得または設定します。ピクセルが直接表現されている場合、カラー パレットは使用されません。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | オブジェクトのサイズをインチで取得します. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | 画像の幅を取得します. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | オブジェクトの幅をインチで取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | データをキャッシュし、基盤から追加のデータ読み込みが実行されないようにします[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式で画像を保存できるかどうかを決定します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトのオプションを取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づいてオプションを取得します. これは、元の画像のビット深度やその他のパラメーターを変更しないで保持するのに役立ちます. たとえば、1 ビットあたり 1 ビットの白黒 PNG 画像をロードし、 the を使用して保存します[`Save`](../datastreamsupporter/save/) これを回避し、1 ピクセルあたり 1 ビットの PNG 画像を保存するには、このメソッドを使用して対応する保存オプションを取得し、 を[`Save`](../image/save/) 番目のパラメーターとしてのメソッド。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例してサイズ変更します。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例してサイズ変更します。 |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | 画像を回転、反転、または回転して反転します。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | 画像パレットを設定します。 |

### 関連項目

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


