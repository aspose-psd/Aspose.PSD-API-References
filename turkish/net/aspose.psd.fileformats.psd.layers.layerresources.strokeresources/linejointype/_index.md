---
title: Enum LineJoinType
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType Sıralama. Satır Birleştirme türü.
type: docs
weight: 3050
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Satır Birleştirme türü.

```csharp
public enum LineJoinType : short
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| BevelJoin | `0` | Eğim birleştirme türü. |
| RoundJoin | `1` | Yuvarlak birleştirme türü. |
| MiterJoin | `2` | Gönye birleştirme türü. |

### Örnekler

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

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* toplantı [Aspose.PSD](../../)


