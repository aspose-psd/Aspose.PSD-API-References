---
title: RasterCachedImage.Crop
second_title: Aspose.PSD für .NET-API-Referenz
description: RasterCachedImage methode. Bild zuschneiden.
type: docs
weight: 90
url: /de/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Bild zuschneiden.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck. |

### Beispiele

Der folgende Code demonstriert die Möglichkeit, das Bild anhand eines bestimmten Rechtecks zuzuschneiden.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // PSD speichern
    image.Save(exportPath, new PsdOptions());

    // png speichern
    image.Save(exportPathPng, new PngOptions());
}
```

### Siehe auch

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* namensraum [Aspose.PSD](../../rastercachedimage/)
* Montage [Aspose.PSD](../../../)


