---
title: "WorkingPathResource.Paths"
second_title: "Aspose.PSD for .NET API Referansı"
description: "WorkingPathResource özelliği. Yol kayıtlarını alır veya ayarlar"
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
{{< psd/tize >}}
## WorkingPathResource.Paths property

Yol kayıtlarını alır veya ayarlar.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Property Value

Yollar.

## Örnekler

Bu örnek, 'WorkingPathResource' kaynağının PsdImage.ImageResources içinde Crop işleminin doğru çalışması için desteğini gösterir.

```csharp
[C#]

// Görüntüyü kırp ve kaydet.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // WorkingPathResource kaynağını ara.
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

// Kaydedilmiş görüntüyü yükle ve değişiklikleri kontrol et.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // WorkingPathResource kaynağını ara.
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

### Ayrıca Bakınız

* class [VectorPathRecord](../../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/)
* class [WorkingPathResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


