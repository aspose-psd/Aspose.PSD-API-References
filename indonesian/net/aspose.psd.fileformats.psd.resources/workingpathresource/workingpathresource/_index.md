---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD untuk Referensi .NET API
description: WorkingPathResource konstruktor. Menginisialisasi instance baru dariWorkingPathResource kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

Menginisialisasi instance baru dari[`WorkingPathResource`](../) kelas.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| dataBytes | Byte[] | Data jalur vektor. |

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

* class [WorkingPathResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* perakitan [Aspose.PSD](../../../)


