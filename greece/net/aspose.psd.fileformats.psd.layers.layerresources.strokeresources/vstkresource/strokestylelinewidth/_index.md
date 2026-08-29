---
title: "VstkResource.StrokeStyleLineWidth"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "VstkResource ιδιότητα. Λαμβάνει ή ορίζει το πλάτος γραμμής Stroke"
type: docs
weight: 140
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineWidth property

Λαμβάνει ή ορίζει το πλάτος γραμμής του Stroke.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του πόρου VstkResource.

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

### Δείτε επίσης

* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


