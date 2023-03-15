---
title: Enum LineJoinType
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType uppräkning. Linjekopplingstyp.
type: docs
weight: 3050
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Linjekopplingstyp.

```csharp
public enum LineJoinType : short
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| BevelJoin | `0` | Fasad sammanfogningstyp. |
| RoundJoin | `1` | Roundd kopplingstyp. |
| MiterJoin | `2` | Geringskopplingstyp. |

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

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* hopsättning [Aspose.PSD](../../)


