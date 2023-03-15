---
title: IVectorPathData.IsDisabled
second_title: Aspose.PSD for .NET API Referansı
description: IVectorPathData mülk. Bu örneğin devre dışı bırakılıp bırakılmadığını gösteren bir değer alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/
---
## IVectorPathData.IsDisabled property

Bu örneğin devre dışı bırakılıp bırakılmadığını gösteren bir değer alır veya ayarlar.

```csharp
public bool IsDisabled { get; set; }
```

### Mülk değeri

`doğru` bu örnek devre dışı bırakılırsa; aksi takdirde,`YANLIŞ` .

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

* interface [IVectorPathData](../)
* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* toplantı [Aspose.PSD](../../../)


