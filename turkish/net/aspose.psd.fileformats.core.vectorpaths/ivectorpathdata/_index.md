---
title: Interface IVectorPathData
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData arayüz. Vektör yolu verilerine erişim için arayüz.
type: docs
weight: 1350
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

Vektör yolu verilerine erişim için arayüz.

```csharp
public interface IVectorPathData
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Bu örneğin devre dışı bırakılıp bırakılmadığını gösteren bir değer alır veya ayarlar. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Bu örneğin ters çevrildiğini gösteren bir değer alır veya ayarlar. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Bu örneğin bağlantılı olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Yol kayıtlarını alır veya ayarlar. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Sürümü alır veya ayarlar. |

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

* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* toplantı [Aspose.PSD](../../)


