---
title: WorkingPathResource.Paths
second_title: Aspose.PSD untuk Referensi .NET API
description: WorkingPathResource Properti. Mendapat atau menyetel catatan jalur.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
## WorkingPathResource.Paths property

Mendapat atau menyetel catatan jalur.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Nilai properti

Jalurnya.

### Contoh

Contoh ini menunjukkan dukungan sumber daya 'WorkingPathResource' di PsdImage.ImageResources untuk pengoperasian Pangkas yang benar.

```csharp
[C#]

// Pangkas gambar dan simpan.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Cari sumber daya WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Pangkas dan simpan.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Muat gambar yang disimpan dan periksa perubahannya.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Cari sumber daya WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Lihat juga

* class [VectorPathRecord](../../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/)
* class [WorkingPathResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* perakitan [Aspose.PSD](../../../)


