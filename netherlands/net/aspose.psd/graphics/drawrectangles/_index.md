---
title: Graphics.DrawRectangles
second_title: Aspose.PSD voor .NET API-referentie
description: Graphics methode. Tekent een reeks rechthoeken gespecificeerd doorRectangleF structuren.
type: docs
weight: 310
url: /nl/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Tekent een reeks rechthoeken gespecificeerd door[`RectangleF`](../../rectanglef/) structuren.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van de contouren van de rechthoeken bepaalt. |
| rects | RectangleF[] | Reeks van[`RectangleF`](../../rectanglef/) structuren die de te tekenen rechthoeken vertegenwoordigen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *rects* is niets. |

### Zie ook

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Tekent een reeks rechthoeken gespecificeerd door[`Rectangle`](../../rectangle/) structuren.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van de contouren van de rechthoeken bepaalt. |
| rects | Rectangle[] | Reeks van[`Rectangle`](../../rectangle/) structuren die de te tekenen rechthoeken vertegenwoordigen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *rects* is niets. |

### Voorbeelden

Dit voorbeeld toont het maken en gebruiken van Pen-objecten. Het voorbeeld maakt een nieuwe afbeelding aan en tekent rechthoeken op het afbeeldingsoppervlak.

```csharp
[C#]

//Maak een exemplaar van Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Maak een instantie van Graphics en initialiseer deze met het Image-object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Wis het grafische oppervlak met witte kleur
    graphics.Clear(Aspose.PSD.Color.White);

    //Maak een instantie van Pen met kleur Rood en breedte 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Maak een instantie van HatchBrush en stel de eigenschappen ervan in
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Maak een instantie van Pen
    // initialiseer het met HatchBrush-object en breedte
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Teken rechthoeken door een Pen-object op te geven
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Teken rechthoeken door een Pen-object op te geven
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Maak exportopties en initialiseer ze.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // sla alle veranderingen op.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Zie ook

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)


