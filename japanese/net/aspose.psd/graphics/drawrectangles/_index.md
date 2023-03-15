---
title: Graphics.DrawRectangles
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. で指定された一連の長方形を描画しますRectangleF構造物.
type: docs
weight: 310
url: /ja/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

で指定された一連の長方形を描画します[`RectangleF`](../../rectanglef/)構造物.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)長方形のアウトラインの色、幅、およびスタイルを決定します。 |
| rects | RectangleF[] | の配列[`RectangleF`](../../rectanglef/)描画する四角形を表す構造体。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *rects*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

で指定された一連の長方形を描画します[`Rectangle`](../../rectangle/)構造物.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)長方形のアウトラインの色、幅、およびスタイルを決定します。 |
| rects | Rectangle[] | の配列[`Rectangle`](../../rectangle/)描画する四角形を表す構造体。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *rects*無効である。 |

### 例

この例は、Pen オブジェクトの作成と使用を示しています。この例では、新しい Image を作成し、Image 表面に Rectangles を描画します。

```csharp
[C#]

//Image のインスタンスを作成する
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics のインスタンスを作成し、Image オブジェクトで初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics sutface を白色でクリアする
    graphics.Clear(Aspose.PSD.Color.White);

    // 色が赤で幅が 5 の Pen のインスタンスを作成する
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush のインスタンスを作成し、そのプロパティを設定します
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    // Pen のインスタンスを作成する
    //HatchBrush オブジェクトと幅で初期化します
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //ペンオブジェクトを指定して長方形を描画
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //ペンオブジェクトを指定して長方形を描画
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // エクスポート オプションを作成して初期化します。
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // すべての変更を保存します。
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 関連項目

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)


