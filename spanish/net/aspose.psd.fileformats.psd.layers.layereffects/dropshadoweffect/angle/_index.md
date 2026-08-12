---
title: "DropShadowEffect.Angle"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad DropShadowEffect. Obtiene o establece el ángulo en grados"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
{{< psd/tize >}}
## DropShadowEffect.Angle property

Obtiene o establece el ángulo en grados.

```csharp
public int Angle { get; set; }
```

### Property Value

El ángulo.

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

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


