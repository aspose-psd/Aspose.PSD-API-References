---
title: "ILayerEffect.GetEffectBounds"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ILayerEffect. Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerBounds | Rectangle | Los límites de píxeles de la capa. |
| globalAngle | Int32 | El ángulo global para calcular el ángulo de luz global. |

### Valor devuelto

Los límites de los píxeles del efecto basados en los límites de los píxeles de la capa de entrada.

## Ejemplos

Demuestra cómo obtener los límites de una capa con efectos y exportarla con el tamaño correcto.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Para guardar dentro de los límites de PsdImage en la ubicación original de la capa

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### Ver también

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


