---
title: "Enum LineCapType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enum. Linjekaptyp"
type: docs
weight: 3400
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

Linjekaptyp.

```csharp
public enum LineCapType : short
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| RoundCap | `0` | Rund kaptyp. |
| SquareCap | `1` | Fyrkantig kaptyp. |
| ButtCap | `2` | Platt kaptyp. |

## Exempel

Följande kod demonstrerar stödet för VstkResource-resursen.

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


