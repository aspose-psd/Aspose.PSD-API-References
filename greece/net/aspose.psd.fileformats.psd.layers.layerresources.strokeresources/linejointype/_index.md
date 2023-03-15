---
title: Enum LineJoinType
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType αρίθμηση. Τύπος σύνδεσης γραμμής.
type: docs
weight: 3050
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Τύπος σύνδεσης γραμμής.

```csharp
public enum LineJoinType : short
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| BevelJoin | `0` | Τύπος λοξοτομής σύνδεσης. |
| RoundJoin | `1` | Στρογγυλός τύπος ένωσης. |
| MiterJoin | `2` | Τύπος σύνδεσης Miter. |

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

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* συνέλευση [Aspose.PSD](../../)


