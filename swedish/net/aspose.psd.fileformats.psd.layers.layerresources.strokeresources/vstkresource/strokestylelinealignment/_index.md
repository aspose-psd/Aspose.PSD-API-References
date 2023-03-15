---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD för .NET API-referens
description: VstkResource fast egendom. Hämtar eller ställer in linjejustering av linjestil.
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Hämtar eller ställer in linjejustering av linjestil.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

### Exempel

Följande kod visar stödet för VstkResource-resursen.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### Se även

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* hopsättning [Aspose.PSD](../../../)


