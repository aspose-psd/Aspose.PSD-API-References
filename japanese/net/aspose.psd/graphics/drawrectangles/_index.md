---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。RectangleF 構造体で指定された矩形の系列を描画します。"
type: docs
weight: 320
url: /ja/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

[`RectangleF`](../../rectanglef/) 構造体で指定された矩形の系列を描画します。

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は、矩形の輪郭の色、幅、スタイルを決定します。 |
| rects | RectangleF[] | 描画する矩形を表す [`RectangleF`](../../rectanglef/) 構造体の配列です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* が null です。-or- *rects* が null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

[`Rectangle`](../../rectangle/) 構造体で指定された矩形の系列を描画します。

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は、矩形の輪郭の色、幅、スタイルを決定します。 |
| rects | Rectangle[] | 描画する矩形を表す [`Rectangle`](../../rectangle/) 構造体の配列です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* が null です。-or- *rects* が null です。 |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


