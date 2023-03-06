---
title: IVectorPathData.Paths
second_title: Aspose.PSD for .NET API Referansı
description: IVectorPathData mülk. Yol kayıtlarını alır veya ayarlar.
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/
---
## IVectorPathData.Paths property

Yol kayıtlarını alır veya ayarlar.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Mülk değeri

Yollar.

### Örnekler

Bu örnek, Kırpma işleminin doğru çalışması için PsdImage.ImageResources içindeki 'WorkingPathResource' kaynağının desteğini gösterir.

```csharp
[C#]

// Resmi kırpın ve kaydedin.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // WorkingPathResource kaynağını arayın.
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

    // Kırp ve kaydet.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Kayıtlı görüntüyü yükleyin ve değişiklikleri kontrol edin.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // WorkingPathResource kaynağını arayın.
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

### Ayrıca bakınız

* class [VectorPathRecord](../../vectorpathrecord/)
* interface [IVectorPathData](../)
* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* toplantı [Aspose.PSD](../../../)


