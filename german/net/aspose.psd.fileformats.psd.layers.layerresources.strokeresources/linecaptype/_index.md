---
title: Enum LineCapType
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType opsomming. Linienkappentyp.
type: docs
weight: 3040
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Linienkappentyp.

```csharp
public enum LineCapType : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| RoundCap | `0` | Typ mit runder Kappe. |
| SquareCap | `1` | Quadratischer Kappentyp. |
| ButtCap | `2` | Kolbenkappentyp. |

### Beispiele

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

* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* Montage [Aspose.PSD](../../)


