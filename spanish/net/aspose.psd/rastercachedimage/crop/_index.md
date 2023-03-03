---
title: RasterCachedImage.Crop
second_title: Referencia de API de Aspose.PSD para .NET
description: RasterCachedImage método. Recortando la imagen.
type: docs
weight: 90
url: /es/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Recortando la imagen.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | el rectángulo |

### Ejemplos

El siguiente código demuestra la capacidad de recortar la imagen por un rectángulo específico.

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

    // Guardar psd
    image.Save(exportPath, new PsdOptions());

    // Guardar png
    image.Save(exportPathPng, new PngOptions());
}
```

### Ver también

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* espacio de nombres [Aspose.PSD](../../rastercachedimage/)
* asamblea [Aspose.PSD](../../../)


