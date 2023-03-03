---
title: DropShadowEffect.Angle
second_title: Referencia de API de Aspose.PSD para .NET
description: DropShadowEffect propiedad. Obtiene o establece el ángulo en grados.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

Obtiene o establece el ángulo en grados.

```csharp
public int Angle { get; set; }
```

### El valor de la propiedad

El ángulo.

### Ejemplos

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

    // Ejemplo con Opacidad = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Ejemplo con Opacidad = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Ver también

* class [DropShadowEffect](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* asamblea [Aspose.PSD](../../../)


