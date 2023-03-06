---
title: Enum LineJoinType
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType opsomming. Lijnverbindingstype.
type: docs
weight: 3050
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Lijnverbindingstype.

```csharp
public enum LineJoinType : short
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| BevelJoin | `0` | Type schuine verbinding. |
| RoundJoin | `1` | Type ronde join. |
| MiterJoin | `2` | Type verstekverbinding. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van de VstkResource-resource.

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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* montage [Aspose.PSD](../../)


