---
title: "ThresholdLayer.Level"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad ThresholdLayer. Obtiene y establece el nivel de umbral"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

Obtiene y establece el nivel de umbral.

```csharp
public short Level { get; set; }
```

### Property Value

El nivel.

## Ejemplos

El siguiente código demuestra el soporte de la capa de ajuste ThresholdLayer.

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Obtén, verifica y cambia la capa de ajuste Threshold de la imagen.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Obtener capa de ajuste Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Verificar los parámetros de las capas.
            AssertAreEqual(level, (short)115);

            // Establecer los parámetros de las capas.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Agregar y establecer la capa de ajuste Threshold en la imagen.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Agregar capa de ajuste Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Establecer los parámetros de las capas.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Ver también

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


