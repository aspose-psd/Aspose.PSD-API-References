---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet eine Reihe von Rechtecken, die durch RectangleF-Strukturen angegeben werden."
type: docs
weight: 320
url: /de/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Zeichnet eine Reihe von Rechtecken, die durch [`RectangleF`](../../rectanglef/) Strukturen angegeben werden.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Umrisse der Rechtecke bestimmt. |
| rects | RectangleF[] | Array von [`RectangleF`](../../rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *rects* ist null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Zeichnet eine Reihe von Rechtecken, die durch [`Rectangle`](../../rectangle/) Strukturen angegeben werden.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) der die Farbe, Breite und den Stil der Umrisse der Rechtecke bestimmt. |
| rects | Rectangle[] | Array von [`Rectangle`](../../rectangle/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *rects* ist null. |

## Beispiele

Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Image und zeichnet Rechtecke auf der Image-Oberfläche.

```csharp
[C#]

//Erstelle eine Instanz von Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle eine Instanz von Graphics und initialisiere sie mit einem Image-Objekt
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche mit weißer Farbe.
    graphics.Clear(Aspose.PSD.Color.White);

    //Erstelle eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Erstelle eine Instanz von HatchBrush und setze ihre Eigenschaften
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Erstelle eine Instanz von Pen
    //initialisiere sie mit einem HatchBrush-Objekt und einer Breite
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Zeichne Rechtecke, indem du ein Pen-Objekt angibst
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Zeichne Rechtecke, indem du ein Pen-Objekt angibst
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Erstelle Exportoptionen und initialisiere sie.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Speichere alle Änderungen.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Siehe auch

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


