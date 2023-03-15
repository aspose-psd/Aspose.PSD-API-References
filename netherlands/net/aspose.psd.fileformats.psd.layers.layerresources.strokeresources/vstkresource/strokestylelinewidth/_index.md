---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD voor .NET API-referentie
description: VstkResource eigendom. Haalt of stelt Lijnlijndikte in.
type: docs
weight: 160
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Haalt of stelt Lijnlijndikte in.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

### Voorbeelden

De volgende code demonstreert de ondersteuning van de VstkResource-resource.

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

### Zie ook

* class [VstkResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* montage [Aspose.PSD](../../../)


