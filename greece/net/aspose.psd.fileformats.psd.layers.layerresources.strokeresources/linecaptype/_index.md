---
title: Enum LineCapType
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType αρίθμηση. Τύπος καπακιού γραμμής.
type: docs
weight: 3040
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Τύπος καπακιού γραμμής.

```csharp
public enum LineCapType : short
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| RoundCap | `0` | Τύπος στρογγυλού καπακιού. |
| SquareCap | `1` | Τύπος τετράγωνου καπακιού. |
| ButtCap | `2` | Τύπος καπέλου γλουτών. |

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


