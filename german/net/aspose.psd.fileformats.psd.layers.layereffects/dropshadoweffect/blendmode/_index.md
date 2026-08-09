---
title: "DropShadowEffect.BlendMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "DropShadowEffect-Eigenschaft. Liest oder setzt den Mischmodus"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/
---
{{< psd/tize >}}
## DropShadowEffect.BlendMode property

Liest oder setzt den Mischmodus.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

Der Mischmodus.

## Beispiele

Der folgende Code demonstriert die Verwendung der Opacity-Eigenschaft von DropShadowEffect.

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

    // Beispiel mit Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Beispiel mit Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Siehe auch

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


