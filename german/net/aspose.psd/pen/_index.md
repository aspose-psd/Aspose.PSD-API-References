---
title: "Klasse Pen"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Pen‑Klasse. Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird."
type: docs
weight: 5690
url: /de/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird.

```csharp
public class Pen : TransparencySupporter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initialisiert eine neue Instanz der `Pen`‑Klasse mit dem angegebenen [`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | Initialisiert eine neue Instanz der `Pen`‑Klasse mit der angegebenen Farbe. |
| [Pen](pen/#constructor_1)(Brush, float) | Initialisiert eine neue Instanz der `Pen`‑Klasse mit dem angegebenen [`Brush`](./brush/) und [`Width`](./width/). |
| [Pen](pen/#constructor_3)(Color, float) | Initialisiert eine neue Instanz der `Pen`‑Klasse mit den angegebenen [`Color`](./color/)‑ und [`Width`](./width/)‑Eigenschaften. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Liest oder legt die Ausrichtung für dieses `Pen` fest. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Liest oder legt das [`Brush`](./brush/) fest, das die Attribute dieses `Pen` bestimmt. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Liest oder legt die Farbe dieses `Pen` fest. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Liest oder legt ein Array von Werten fest, das einen zusammengesetzten Stift definiert. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Liest oder legt eine benutzerdefinierte Endkappe fest, die am Ende von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Liest oder legt eine benutzerdefinierte Anfangskappe fest, die am Anfang von mit diesem `Pen` gezeichneten Linien verwendet wird. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Liest oder legt den Endstil fest, der am Ende der Striche verwendet wird, aus denen gestrichelte Linien, die mit diesem `Pen` gezeichnet werden, bestehen. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Liest oder legt den Abstand vom Beginn einer Linie bis zum Anfang eines Strichmusters fest. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Liest oder legt ein Array benutzerdefinierter Striche und Lücken fest. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Liest oder legt den Stil fest, der für gestrichelte Linien verwendet wird, die mit diesem `Pen` gezeichnet werden. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Liest oder legt den Endstil fest, der am Ende von Linien verwendet wird, die mit diesem `Pen` gezeichnet werden. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Liest oder legt den Verbindungsstil für die Enden von zwei aufeinanderfolgenden Linien fest, die mit diesem `Pen` gezeichnet werden. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Liest oder legt die Begrenzung der Dicke der Verbindung an einer Gehrungsecke fest. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Liest oder setzt die Deckkraft des Objekts. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass das Objekt vollständig sichtbar ist, ein Wert von 1 bedeutet, dass das Objekt vollständig undurchsichtig ist. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Liest den Stil der mit diesem `Pen` gezeichneten Linien. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Liest oder legt den Anfangsstil fest, der am Beginn von Linien verwendet wird, die mit diesem `Pen` gezeichnet werden. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Liest oder legt eine Kopie der geometrischen Transformation für diesen `Pen` fest. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Liest oder legt die Breite dieses `Pen` fest, in Einheiten des zum Zeichnen verwendeten Graphics-Objekts. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multipliziert die Transformationsmatrix für diesen `Pen` mit der angegebenen [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multipliziert die Transformationsmatrix für diesen `Pen` mit der angegebenen [`Matrix`](../matrix/) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Setzt die geometrische Transformationsmatrix für diesen `Pen` auf die Identität zurück. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Rotiert die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode fügt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rotiert die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode fügt die Skalierungsmatrix der Transformation voran. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Legt die Werte fest, die den Endstil bestimmen, der zum Abschließen von Linien verwendet wird, die mit diesem `Pen` gezeichnet werden. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


