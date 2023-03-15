---
title: Graphics.DrawRectangles
second_title: Aspose.PSD för .NET API-referens
description: Graphics metod. Ritar en serie rektanglar specificerade avRectangleF strukturer.
type: docs
weight: 310
url: /sv/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Ritar en serie rektanglar specificerade av[`RectangleF`](../../rectanglef/) strukturer.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil på rektanglarnas konturer. |
| rects | RectangleF[] | Uppsättning av[`RectangleF`](../../rectanglef/) strukturer som representerar rektanglarna som ska ritas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *rects* är inget. |

### Se även

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Ritar en serie rektanglar specificerade av[`Rectangle`](../../rectangle/) strukturer.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) som bestämmer färg, bredd och stil på rektanglarnas konturer. |
| rects | Rectangle[] | Uppsättning av[`Rectangle`](../../rectangle/) strukturer som representerar rektanglarna som ska ritas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *rects* är inget. |

### Exempel

Det här exemplet visar skapande och användning av Pen-objekt. Exemplet skapar en ny bild och ritar rektanglar på bildytan.

```csharp
[C#]

//Skapa en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa en instans av Graphics och initiera den med Image object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan med vit färg
    graphics.Clear(Aspose.PSD.Color.White);

    //Skapa en instans av Pen med färgen Röd och bredd 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Skapa en instans av HatchBrush och ställ in dess egenskaper
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Skapa en instans av Pen
    //initiera det med HatchBrush-objekt och bredd
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Rita rektanglar genom att ange Pen-objekt
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
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)


