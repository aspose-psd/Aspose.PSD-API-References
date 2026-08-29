---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Graphics-metod. Ritar en serie rektanglar som anges av RectangleF-strukturer"
type: docs
weight: 320
url: /sv/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Ritar en serie rektanglar som anges av [`RectangleF`](../../rectanglef/) strukturer.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | RectangleF[] | Array av [`RectangleF`](../../rectanglef/) strukturer som representerar rektanglarna som ska ritas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *rects* är null. |

### Se även

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Ritar en serie rektanglar som anges av [`Rectangle`](../../rectangle/) strukturer.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | Rectangle[] | Array av [`Rectangle`](../../rectangle/) strukturer som representerar rektanglarna som ska ritas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *rects* är null. |

## Exempel

Detta exempel visar skapandet och användningen av Pen‑objekt. Exemplet skapar en ny Image och ritar rektanglar på Image‑ytan.

```csharp
[C#]

//Skapa en instans av Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa en instans av Graphics och initiera den med ett Image‑objekt
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics‑ytan med vit färg.
    graphics.Clear(Aspose.PSD.Color.White);

    //Skapa en instans av Pen med färgen röd och bredd 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Skapa en instans av HatchBrush och ange dess egenskaper
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Skapa en instans av Pen
    //initiera den med HatchBrush‑objektet och bredden
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen‑objektet
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Rita rektanglar genom att ange Pen‑objektet
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Se även

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


