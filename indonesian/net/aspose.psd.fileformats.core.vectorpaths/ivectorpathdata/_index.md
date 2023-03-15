---
title: Interface IVectorPathData
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData antarmuka. Antarmuka untuk mengakses data jalur vektor.
type: docs
weight: 1350
url: /id/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

Antarmuka untuk mengakses data jalur vektor.

```csharp
public interface IVectorPathData
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terbalik. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini tidak ditautkan. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Mendapat atau menyetel catatan jalur. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Mendapatkan atau menyetel versi. |

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

* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* perakitan [Aspose.PSD](../../)


