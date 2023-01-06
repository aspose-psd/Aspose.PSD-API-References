---
title: Pen
second_title: Aspose.PSD für .NET-API-Referenz
description: Definiert ein Objekt zum Zeichnen von Linien Kurven und Figuren.
type: docs
weight: 5130
url: /de/net/aspose.psd/pen/
---
## Pen class

Definiert ein Objekt zum Zeichnen von Linien, Kurven und Figuren.

```csharp
public class Pen : TransparencySupporter
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit den angegebenen[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit der angegebenen Farbe. |
| [Pen](pen#constructor_1)(Brush, float) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit den angegebenen[`Brush`](./brush) und[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit den angegebenen[`Color`](./color) und[`Width`](./width) Eigenschaften. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment) { get; set; } | Holt oder setzt die Ausrichtung dafür[`Pen`](../pen) . |
| [Brush](../../aspose.psd/pen/brush) { get; set; } | Ruft ab oder setzt die[`Brush`](./brush) das bestimmt Attribute davon[`Pen`](../pen) . |
| [Color](../../aspose.psd/pen/color) { get; set; } | Holt oder setzt die Farbe davon[`Pen`](../pen) . |
| [CompoundArray](../../aspose.psd/pen/compoundarray) { get; set; } | Ruft ein Array von Werten ab oder legt es fest, das einen zusammengesetzten Stift angibt. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie aus parallelen Linien und Zwischenräumen. |
| [CustomEndCap](../../aspose.psd/pen/customendcap) { get; set; } | Ruft eine benutzerdefinierte Obergrenze ab oder legt sie fest, die am Ende der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap) { get; set; } | Ruft eine benutzerdefinierte Obergrenze ab oder legt sie fest, die am Anfang der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [DashCap](../../aspose.psd/pen/dashcap) { get; set; } | Ermittelt oder setzt den Kappenstil, der am Ende der Bindestriche verwendet wird, aus denen die damit gezeichneten gestrichelten Linien bestehen[`Pen`](../pen) . |
| [DashOffset](../../aspose.psd/pen/dashoffset) { get; set; } | Ruft den Abstand vom Anfang einer Linie zum Anfang eines Strichmusters ab oder legt ihn fest. |
| [DashPattern](../../aspose.psd/pen/dashpattern) { get; set; } | Ruft ein Array benutzerdefinierter Bindestriche und Leerzeichen ab oder legt es fest. |
| [DashStyle](../../aspose.psd/pen/dashstyle) { get; set; } | Ermittelt oder setzt den Stil, der für damit gezeichnete gestrichelte Linien verwendet wird[`Pen`](../pen) . |
| [EndCap](../../aspose.psd/pen/endcap) { get; set; } | Ermittelt oder setzt den Kappenstil, der am Ende der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [LineJoin](../../aspose.psd/pen/linejoin) { get; set; } | Ermittelt oder setzt den Verbindungsstil für die Enden zweier aufeinanderfolgender Linien, die damit gezeichnet werden[`Pen`](../pen) . |
| [MiterLimit](../../aspose.psd/pen/miterlimit) { get; set; } | Ruft die Grenze der Dicke der Verbindung an einer Gehrungsecke ab oder legt sie fest. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity) { get; set; } | Ruft die Deckkraft des Objekts ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass das Objekt vollständig sichtbar ist, der Wert 1 bedeutet, dass das Objekt vollständig undurchsichtig ist. |
| [PenType](../../aspose.psd/pen/pentype) { get; } | Ruft den Stil der damit gezeichneten Linien ab[`Pen`](../pen) . |
| [StartCap](../../aspose.psd/pen/startcap) { get; set; } | Ermittelt oder setzt den Kappenstil, der am Anfang der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [Transform](../../aspose.psd/pen/transform) { get; set; } | Holt oder setzt eine Kopie der geometrischen Transformation dafür[`Pen`](../pen) . |
| [Width](../../aspose.psd/pen/width) { get; set; } | Holt oder setzt die Breite davon[`Pen`](../pen) , in Einheiten des Graphics-Objekts, das zum Zeichnen verwendet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform#multiplytransform)(Matrix) | Multipliziert dazu die Transformationsmatrix[`Pen`](../pen) durch die angegebenen[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multipliziert dazu die Transformationsmatrix[`Pen`](../pen) durch die angegebenen[`Matrix`](../matrix) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd/pen/resettransform)() | Setzt hierfür die geometrische Transformationsmatrix zurück[`Pen`](../pen) zur Identität. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform#rotatetransform)(float) | Dreht die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode stellt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform#scaletransform)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode stellt der Transformation die Skalierungsmatrix voran. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [SetLineCap](../../aspose.psd/pen/setlinecap)(LineCap, LineCap, DashCap) | Legt die Werte fest, die den Stil der Kappe bestimmen, der verwendet wird, um damit gezeichnete Linien zu beenden[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform#translatetransform)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Maße. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

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

* class [TransparencySupporter](../transparencysupporter)
* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
