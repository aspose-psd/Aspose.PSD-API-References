---
title: DropShadowEffect.Opacity
second_title: Aspose.PSD for .NET API Reference
description: DropShadowEffect property. Gets or sets the opacity
type: docs
weight: 90
url: /net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/
---
{{< psd/tize >}}
## DropShadowEffect.Opacity property

Gets or sets the opacity.

```csharp
public byte Opacity { get; set; }
```

### Property Value

The opacity.

## Examples

The following code demonstrates using the Opacity property of DropShadowEffect.

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

    // Example with Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Example with Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### See Also

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* assembly [Aspose.PSD](../../../)


