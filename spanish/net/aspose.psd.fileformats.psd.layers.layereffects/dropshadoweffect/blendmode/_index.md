---
title: "DropShadowEffect.BlendMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad DropShadowEffect. Obtiene o establece el modo de fusión"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/
---
{{< psd/tize >}}
## DropShadowEffect.BlendMode property

Obtiene o establece el modo de fusión.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

El modo de fusión.

## Ejemplos

El siguiente código demuestra el uso de la propiedad Opacity de DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Ejemplo con Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Ejemplo con Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Ver también

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


