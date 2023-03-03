---
title: Enum LineJoinType
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType opsomming. Linienverbindungstyp.
type: docs
weight: 3050
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Linienverbindungstyp.

```csharp
public enum LineJoinType : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| BevelJoin | `0` | Fasenverbindungstyp. |
| RoundJoin | `1` | Round-Join-Typ. |
| MiterJoin | `2` | Gehrungsverbindungstyp. |

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


