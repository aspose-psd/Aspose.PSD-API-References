---
title: Enum LineCapType
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType Sıralama. Satır Sonu tipi.
type: docs
weight: 3040
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Satır Sonu tipi.

```csharp
public enum LineCapType : short
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| RoundCap | `0` | Yuvarlak kapak tipi. |
| SquareCap | `1` | Kare kapak tipi. |
| ButtCap | `2` | Alın başlığı tipi. |

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


