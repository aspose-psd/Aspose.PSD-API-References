---
title: "Figure.AddShape"
second_title: "Aspose.PSD for .NET API Reference"
description: "Figure メソッド。図形にシェイプを追加します。"
type: docs
weight: 60
url: /ja/net/aspose.psd/figure/addshape/
---
{{< psd/tize >}}
## Figure.AddShape method

図形にシェイプを追加します。

```csharp
public void AddShape(Shape shape)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| シェイプ | シェイプ | 追加するシェイプ。 |

## 例

この例では GraphicsPath クラスと Graphics クラスを使用して、Image 表面上に Figure を作成および操作します。例では新しい Image を作成し、GraphicsPath クラスを使用してパスを描画します。最後に Graphics クラスが提供する DrawPath メソッドが呼び出され、表面上にパスが描画されます。最終的に画像は Tiff ファイル形式にエクスポートされます。

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure オブジェクトにシェイプを追加します。
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath に Figure オブジェクトを追加します。
    graphicspath.AddFigure(figure);

    //黒色の Pen オブジェクトでパスを描画します。
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions のインスタンスを作成し、さまざまなプロパティを設定します。
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 関連項目

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


