---
title: Layer.BlendModeKey
second_title: Aspose.PSD för .NET API-referens
description: Layer fast egendom. Hämtar eller ställer in blandningslägestangenten.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

Hämtar eller ställer in blandningslägestangenten.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### Fastighetsvärde

Blandningslägestangenten.

### Exempel

Följande exempel visar hur du kan använda blandningsläget PassThrough-lager i Aspose.PSD

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

### Se även

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* hopsättning [Aspose.PSD](../../../)


