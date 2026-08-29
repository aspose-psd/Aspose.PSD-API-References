---
title: "クラス RectangleShape"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Shapes.RectangleShape クラス。長方形の形状を表します"
type: docs
weight: 6030
url: /ja/net/aspose.psd.shapes/rectangleshape/
---
{{< psd/tize >}}
## RectangleShape class

矩形形状を表します。

```csharp
public class RectangleShape : RectangleProjectedShape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | `RectangleShape` クラスの新しいインスタンスを初期化します。 |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | `RectangleShape` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 形状の中心を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 左下の矩形点を取得します。 |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 左上の矩形点を取得します。 |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 矩形の高さを取得します。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 矩形の幅を取得します。 |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 矩形の右下の点を取得します。 |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 矩形の右上の点を取得します。 |
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | シェイプのセグメントを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 指定された変換をシェイプに適用します。 |

## 例

この例では、新しい Image を作成し、Image の表面上で Figures と GraphicsPath を使用してさまざまなシェイプを描画します。

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Figure オブジェクトにシェイプを追加します
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Figure クラスのインスタンスを作成します。
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Figure オブジェクトにシェイプを追加します
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //GraphicsPath に Figure オブジェクトを追加します。
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //黒色の Pen オブジェクトでパスを描画します。
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // エクスポート オプションを作成し、初期化します。
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // すべての変更を保存します。
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 関連項目

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


