---
title: "クラス Pen"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Pen クラス。線、曲線、図形を描画するために使用されるオブジェクトを定義します。"
type: docs
weight: 5690
url: /ja/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

線、曲線、図形の描画に使用されるオブジェクトを定義します。

```csharp
public class Pen : TransparencySupporter
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | `Pen` クラスの新しいインスタンスを、指定された [`Brush`](./brush/) で初期化します。 |
| [Pen](pen/#constructor_2)(Color) | 指定された色で `Pen` クラスの新しいインスタンスを初期化します。 |
| [Pen](pen/#constructor_1)(Brush, float) | 指定された [`Brush`](./brush/) と [`Width`](./width/) で `Pen` クラスの新しいインスタンスを初期化します。 |
| [Pen](pen/#constructor_3)(Color, float) | 指定された [`Color`](./color/) と [`Width`](./width/) プロパティで `Pen` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | この `Pen` の配置を取得または設定します。 |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | この `Pen` の属性を決定する [`Brush`](./brush/) を取得または設定します。 |
| [Color](../../aspose.psd/pen/color/) { get; set; } | この `Pen` の色を取得または設定します。 |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | 複合ペンを指定する値の配列を取得または設定します。複合ペンは平行線と間隔で構成された複合線を描画します。 |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | この `Pen` で描画された線の終端に使用するカスタムキャップを取得または設定します。 |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | この `Pen` で描画された線の開始点に使用するカスタムキャップを取得または設定します。 |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | この `Pen` で描画された破線のダッシュの終端に使用されるキャップスタイルを取得または設定します。 |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | 線の開始点からダッシュパターンの開始までの距離を取得または設定します。 |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | カスタムダッシュとスペースの配列を取得または設定します。 |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | この `Pen` で描画された破線に使用されるスタイルを取得または設定します。 |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | この `Pen` で描画された線の終端に使用されるキャップスタイルを取得または設定します。 |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | この `Pen` で描画された連続する2本の線の端部に使用される結合スタイルを取得または設定します。 |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | 斜め角の結合部の厚さの上限を取得または設定します。 |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | オブジェクトの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はオブジェクトが完全に可視であることを意味し、1 の値はオブジェクトが完全に不透明であることを意味します。 |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | この `Pen` で描画された線のスタイルを取得します。 |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | この `Pen` で描画された線の先頭で使用されるキャップスタイルを取得または設定します。 |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | この `Pen` の幾何変換のコピーを取得または設定します。 |
| [Width](../../aspose.psd/pen/width/) { get; set; } | 描画に使用される Graphics オブジェクトの単位で、この `Pen` の幅を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | この `Pen` の変換行列に、指定された [`Matrix`](../matrix/) を掛けます。 |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | この `Pen` の変換行列に、指定された順序で指定された [`Matrix`](../matrix/) を掛けます。 |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | この `Pen` の幾何変換行列を単位行列にリセットします。 |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | ローカルの幾何変換を指定された角度だけ回転させます。このメソッドは回転を変換の先頭に追加します。 |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | ローカルの幾何変換を指定された角度で、指定された順序で回転させます。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | ローカルの幾何変換を指定された係数で拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | ローカルの幾何変換を指定された係数で、指定された順序で拡大縮小します。 |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | この `Pen` で描画された線の終端に使用されるキャップのスタイルを決定する値を設定します。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | ローカルの幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | ローカルの幾何変換を指定された寸法で、指定された順序で平行移動します。 |

## 例

この例は Pen オブジェクトの作成と使用方法を示しています。例では新しい Image を作成し、Image の表面に矩形を描画します。

```csharp
[C#]

//Image のインスタンスを作成します。
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics のインスタンスを作成し、Image オブジェクトで初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスを白色でクリアします
    graphics.Clear(Aspose.PSD.Color.White);

    //Pen のインスタンスを作成し、色を Red、幅を 5 に設定します
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush のインスタンスを作成し、そのプロパティを設定します
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen のインスタンスを作成します
    //それを HatchBrush オブジェクトと幅で初期化します
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen オブジェクトを指定して矩形を描画します
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen オブジェクトを指定して矩形を描画します
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // エクスポート オプションを作成し、初期化します。
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // すべての変更を保存します。
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 関連項目

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


