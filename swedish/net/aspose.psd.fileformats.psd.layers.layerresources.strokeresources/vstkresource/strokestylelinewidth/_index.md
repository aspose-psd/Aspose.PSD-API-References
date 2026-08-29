---
title: "VstkResource.StrokeStyleLineWidth"
second_title: "Aspose.PSD för .NET API‑referens"
description: "VstkResource egenskap. Hämtar eller anger Stroke-linjebredd"
type: docs
weight: 140
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineWidth property

Hämtar eller anger stroke‑linjebredd.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

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

* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


