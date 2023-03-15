---
title: Graphics.DrawPath
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. を描画しますGraphicsPath .
type: docs
weight: 270
url: /ja/net/aspose.psd/graphics/drawpath/
---
## Graphics.DrawPath method

を描画します[`GraphicsPath`](../../graphicspath/) .

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)パスの色、幅、およびスタイルを決定します。 |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/)描く。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *path*無効である。 |

### 例

この例では、GraphicsPath および Graphics クラスを使用して、イメージ サーフェス上に Figure を作成および操作します。例では、新しい Image を作成し、GraphicsPath クラスを使用してパスを描画します。最後に、Graphics クラスによって公開された DrawPath メソッドが呼び出され、表面にパスがレンダリングされます。最後に、画像が Tiff ファイル形式にエクスポートされます。

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Figure オブジェクトにシェイプを追加
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath に Figure オブジェクトを追加
    graphicspath.AddFigure(figure);

    //色が黒の Pen オブジェクトでパスを描画します
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // TiffOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 関連項目

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)


