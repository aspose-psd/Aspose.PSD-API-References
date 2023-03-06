---
title: Enum LineCapType
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType opsomming. Type lijnkap.
type: docs
weight: 3040
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Type lijnkap.

```csharp
public enum LineCapType : short
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| RoundCap | `0` | Type ronde dop. |
| SquareCap | `1` | Type vierkante dop. |
| ButtCap | `2` | Type stootdop. |

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


