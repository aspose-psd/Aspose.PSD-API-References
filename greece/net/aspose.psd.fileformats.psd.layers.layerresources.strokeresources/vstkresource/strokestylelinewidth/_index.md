---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD για Αναφορά API .NET
description: VstkResource ιδιοκτησία. Λαμβάνει ή ορίζει πλάτος γραμμής διαδρομής.
type: docs
weight: 160
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Λαμβάνει ή ορίζει πλάτος γραμμής διαδρομής.

```csharp
public double StrokeStyleLineWidth { get; set; }
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

* class [VstkResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* συνέλευση [Aspose.PSD](../../../)


