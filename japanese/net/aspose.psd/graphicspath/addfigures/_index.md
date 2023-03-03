---
title: GraphicsPath.AddFigures
second_title: Aspose.PSD for .NET API リファレンス
description: GraphicsPath 方法. 新しい図を追加します
type: docs
weight: 60
url: /ja/net/aspose.psd/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

新しい図を追加します。

```csharp
public void AddFigures(Figure[] figures)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| figures | Figure[] | 追加する数値。 |

### 例

この例では、新しいイメージを作成し、イメージ サーフェスで Figure と GraphicsPath を使用してさまざまな形状を描画します。

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // Figure オブジェクトに Shape を追加
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // Figure クラスのインスタンスを作成
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // Figure オブジェクトに Shape を追加
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //GraphicsPath に Figure オブジェクトを追加
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //色が黒の Pen オブジェクトでパスを描画します
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // エクスポート オプションを作成して初期化します。
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // すべての変更を保存します。
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 関連項目

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* 名前空間 [Aspose.PSD](../../graphicspath/)
* 組み立て [Aspose.PSD](../../../)


