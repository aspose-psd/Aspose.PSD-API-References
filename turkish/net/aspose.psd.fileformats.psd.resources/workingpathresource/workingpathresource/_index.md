---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD for .NET API Referansı
description: WorkingPathResource inşaatçı. Yeni bir örneğini başlatır.WorkingPathResource sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

Yeni bir örneğini başlatır.[`WorkingPathResource`](../) sınıf.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| dataBytes | Byte[] | Vektör yolunun verileri. |

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

* class [WorkingPathResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* toplantı [Aspose.PSD](../../../)


