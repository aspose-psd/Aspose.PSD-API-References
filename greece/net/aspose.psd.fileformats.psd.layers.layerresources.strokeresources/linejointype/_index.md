---
title: "Enum LineJoinType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. Τύπος ένωσης γραμμής"
type: docs
weight: 3410
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

Τύπος ένωσης γραμμής.

```csharp
public enum LineJoinType : short
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| BevelJoin | `0` | Τύπος ένωσης Bevel. |
| RoundJoin | `1` | Τύπος ένωσης Rounnd. |
| MiterJoin | `2` | Τύπος ένωσης Miter. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


