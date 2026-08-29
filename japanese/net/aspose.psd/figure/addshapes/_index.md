---
title: "Figure.AddShapes"
second_title: "Aspose.PSD for .NET API Reference"
description: "Figure メソッド。図形に複数のシェイプを追加します。"
type: docs
weight: 70
url: /ja/net/aspose.psd/figure/addshapes/
---
{{< psd/tize >}}
## Figure.AddShapes method

図形にシェイプの範囲を追加します。

```csharp
public void AddShapes(Shape[] shapes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| シェイプ | Shape[] | 追加するシェイプ群。 |

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

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


