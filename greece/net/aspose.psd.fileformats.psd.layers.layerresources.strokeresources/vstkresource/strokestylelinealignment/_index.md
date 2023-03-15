---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD για Αναφορά API .NET
description: VstkResource ιδιοκτησία. Λαμβάνει ή ορίζει τη στοίχιση γραμμής στυλ περιγράμματος.
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Λαμβάνει ή ορίζει τη στοίχιση γραμμής στυλ περιγράμματος.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη του πόρου VstkResource.

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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* συνέλευση [Aspose.PSD](../../../)


