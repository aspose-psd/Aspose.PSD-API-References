---
title: "Enum LineJoinType"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. Çizgi Birleştirme türü"
type: docs
weight: 3410
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

Çizgi birleşim türü.

```csharp
public enum LineJoinType : short
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| BevelJoin | `0` | Eğimli birleştirme türü. |
| RoundJoin | `1` | Rounnd birleştirme türü. |
| MiterJoin | `2` | Köşe birleştirme türü. |

## Örnekler

Aşağıdaki kod, VstkResource kaynağının desteğini gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


