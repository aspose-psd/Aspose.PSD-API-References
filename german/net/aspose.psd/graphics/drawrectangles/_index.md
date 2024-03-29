---
title: Graphics.DrawRectangles
second_title: Aspose.PSD für .NET-API-Referenz
description: Graphics methode. Zeichnet eine Reihe von Rechtecken angegeben durchRectangleF Strukturen.
type: docs
weight: 310
url: /de/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Zeichnet eine Reihe von Rechtecken, angegeben durch[`RectangleF`](../../rectanglef/) Strukturen.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und den Stil der Umrisse der Rechtecke bestimmt. |
| rects | RectangleF[] | Anordnung von[`RectangleF`](../../rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *rects* ist Null. |

### Siehe auch

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Zeichnet eine Reihe von Rechtecken, angegeben durch[`Rectangle`](../../rectangle/) Strukturen.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die die Farbe, Breite und den Stil der Umrisse der Rechtecke bestimmt. |
| rects | Rectangle[] | Anordnung von[`Rectangle`](../../rectangle/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *rects* ist Null. |

### Beispiele

Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Bild und zeichnet Rechtecke auf der Bildoberfläche.

```csharp
[C#]

//Eine Instanz von Image erstellen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Eine Instanz von Graphics erstellen und mit dem Image-Objekt initialisieren
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Löschen Sie die Grafikoberfläche mit weißer Farbe
    graphics.Clear(Aspose.PSD.Color.White);

    // Erstellen Sie eine Instanz von Pen mit der Farbe Rot und der Breite 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Eine Instanz von HatchBrush erstellen und ihre Eigenschaften festlegen
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Eine Instanz von Pen erstellen
    // mit HatchBrush-Objekt und -Breite initialisieren
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Zeichne Rechtecke durch Angabe des Pen-Objekts
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Zeichne Rechtecke durch Angabe des Pen-Objekts
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Exportoptionen erstellen und initialisieren.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Alle Änderungen speichern.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Siehe auch

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)


