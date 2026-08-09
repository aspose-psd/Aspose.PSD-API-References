---
title: "Enum LineCapType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType Enum. Linienstiltyp"
type: docs
weight: 3400
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

Linienende-Typ.

```csharp
public enum LineCapType : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| RoundCap | `0` | Runder Endtyp. |
| SquareCap | `1` | Quadratischer Endtyp. |
| ButtCap | `2` | Flacher Endtyp. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der VstkResource-Ressource.

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

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


