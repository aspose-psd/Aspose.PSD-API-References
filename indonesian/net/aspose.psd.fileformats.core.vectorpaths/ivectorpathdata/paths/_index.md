---
title: "IVectorPathData.Paths"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti IVectorPathData. Mengambil atau mengatur catatan jalur."
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/
---
{{< psd/tize >}}
## IVectorPathData.Paths property

Mendapatkan atau mengatur catatan jalur.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Property Value

Jalur.

## Contoh

Contoh ini menunjukkan dukungan sumber daya 'WorkingPathResource' dalam PsdImage.ImageResources untuk kerja yang benar dari operasi Crop.

```csharp
[C#]

// Potong gambar dan simpan.
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

    // Potong dan simpan.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Muat gambar yang disimpan dan periksa perubahan.
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

### Lihat Juga

* class [VectorPathRecord](../../vectorpathrecord/)
* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


