---
title: IVectorPathData.IsInverted
second_title: Aspose.PSD untuk Referensi .NET API
description: IVectorPathData Properti. Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terbalik.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/
---
## IVectorPathData.IsInverted property

Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terbalik.

```csharp
public bool IsInverted { get; set; }
```

### Nilai properti

`BENAR` jika hal ini terbalik; jika tidak,`PALSU` .

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

* interface [IVectorPathData](../)
* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* perakitan [Aspose.PSD](../../../)


