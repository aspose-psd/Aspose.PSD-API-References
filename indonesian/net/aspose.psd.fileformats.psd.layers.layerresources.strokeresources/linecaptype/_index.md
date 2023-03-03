---
title: Enum LineCapType
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enum. Jenis Tutup Baris.
type: docs
weight: 3040
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Jenis Tutup Baris.

```csharp
public enum LineCapType : short
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| RoundCap | `0` | Jenis topi bulat. |
| SquareCap | `1` | Jenis tutup persegi. |
| ButtCap | `2` | Jenis tutup bokong. |

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


