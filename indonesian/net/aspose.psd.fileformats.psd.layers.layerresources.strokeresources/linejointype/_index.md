---
title: "Enum LineJoinType"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. Tipe sambungan garis"
type: docs
weight: 3410
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

Tipe Sambungan Garis.

```csharp
public enum LineJoinType : short
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| BevelJoin | `0` | Tipe sambungan bevel. |
| RoundJoin | `1` | Tipe sambungan bulat. |
| MiterJoin | `2` | Tipe sambungan miter. |

## Contoh

Kode berikut menunjukkan dukungan sumber daya VstkResource.

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

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


