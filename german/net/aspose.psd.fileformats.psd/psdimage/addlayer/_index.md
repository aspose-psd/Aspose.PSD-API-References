---
title: PsdImage.AddLayer
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdImage methode. Fügt die Ebene hinzu.
type: docs
weight: 370
url: /de/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Fügt die Ebene hinzu.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layer | Layer | Die Schicht. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie auf einer neu erstellten Ebene zeichnen können, wenn die einfache Konstruktorversion in Aspose.PSD verwendet wird

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // Zeichnen Sie ein Rechteck mit dem Stiftwerkzeug
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // zeichne ein weiteres Rechteck mit Solid Brush in blauer Farbe
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Siehe auch

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)


