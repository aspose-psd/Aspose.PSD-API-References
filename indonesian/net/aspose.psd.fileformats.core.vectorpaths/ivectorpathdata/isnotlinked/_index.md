---
title: "IVectorPathData.IsNotLinked"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti IVectorPathData. Mengambil atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung."
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/
---
{{< psd/tize >}}
## IVectorPathData.IsNotLinked property

Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung.

```csharp
public bool IsNotLinked { get; set; }
```

### Property Value

`true` jika instance ini tidak terhubung; selainnya, `false`.

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

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


