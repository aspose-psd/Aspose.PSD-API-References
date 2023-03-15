---
title: Enum LineJoinType
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. Jenis Gabung Baris.
type: docs
weight: 3050
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Jenis Gabung Baris.

```csharp
public enum LineJoinType : short
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| BevelJoin | `0` | Jenis gabungan bevel. |
| RoundJoin | `1` | Jenis gabung bulat. |
| MiterJoin | `2` | Mitre join type. |

### Contoh

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

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* perakitan [Aspose.PSD](../../)


