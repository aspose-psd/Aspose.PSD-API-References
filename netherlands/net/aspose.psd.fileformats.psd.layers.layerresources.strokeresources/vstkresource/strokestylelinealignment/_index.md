---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD voor .NET API-referentie
description: VstkResource eigendom. Lijnuitlijning lijnstijl ophalen of instellen.
type: docs
weight: 100
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Lijnuitlijning lijnstijl ophalen of instellen.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* montage [Aspose.PSD](../../../)


