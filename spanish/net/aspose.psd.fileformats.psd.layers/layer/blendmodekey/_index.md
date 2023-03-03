---
title: Layer.BlendModeKey
second_title: Referencia de API de Aspose.PSD para .NET
description: Layer propiedad. Obtiene o establece la clave del modo de combinación.
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

Obtiene o establece la clave del modo de combinación.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### El valor de la propiedad

La tecla de modo de mezcla.

### Ejemplos

El siguiente ejemplo demuestra cómo puede usar el modo de fusión de capas PassThrough en Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* asamblea [Aspose.PSD](../../../)


