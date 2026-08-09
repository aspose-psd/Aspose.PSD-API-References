---
title: "RasterCachedImage.Crop"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "RasterCachedImage method. Recadrage de l'image"
type: docs
weight: 90
url: /fr/net/aspose.psd/rastercachedimage/crop/
---
{{< psd/tize >}}
## RasterCachedImage.Crop method

Recadrage de l'image.

```csharp
public override void Crop(Rectangle rectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle. |

## Exemples

Le code suivant montre la capacité à recadrer l'image par un rectangle spécifique.

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

    // Enregistrer le PSD
    image.Save(exportPath, new PsdOptions());

    // Enregistrer le PNG
    image.Save(exportPathPng, new PngOptions());
}
```

### Voir aussi

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


