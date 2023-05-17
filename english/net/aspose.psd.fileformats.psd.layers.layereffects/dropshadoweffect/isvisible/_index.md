---
title: DropShadowEffect.IsVisible
second_title: Aspose.PSD for .NET API Reference
description: DropShadowEffect property. Gets or sets a value indicating whether this instance is visible
type: docs
weight: 60
url: /net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

Gets or sets a value indicating whether this instance is visible.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` if this instance is visible; otherwise, `false`.

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


