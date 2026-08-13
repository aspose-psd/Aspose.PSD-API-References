---
title: "Arayüz IVectorPathData"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData arayüzü. Vektör yol verilerine erişim için arayüz."
type: docs
weight: 1360
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

Vektör yol verilerine erişim için arayüz.

```csharp
public interface IVectorPathData
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Bu örneğin bağlanmamış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Yol kayıtlarını alır veya ayarlar. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Sürümü alır veya ayarlar. |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


