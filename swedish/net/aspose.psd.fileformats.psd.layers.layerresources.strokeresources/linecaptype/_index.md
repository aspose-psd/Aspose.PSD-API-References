---
title: Enum LineCapType
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType uppräkning. Line Cap type.
type: docs
weight: 3040
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Line Cap type.

```csharp
public enum LineCapType : short
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| RoundCap | `0` | Typ av rund keps. |
| SquareCap | `1` | Typ av fyrkantig lock. |
| ButtCap | `2` | Butt cap typ. |

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


