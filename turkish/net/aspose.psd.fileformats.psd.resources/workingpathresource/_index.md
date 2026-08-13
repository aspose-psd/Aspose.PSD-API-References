---
title: "Sınıf WorkingPathResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource sınıfı. Çalışma yolu kaynağı"
type: docs
weight: 4480
url: /tr/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource class

Çalışma yolu kaynağı.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Yeni bir `WorkingPathResource` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Bu örneğin bağlanmamış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Yol kayıtlarını alır veya ayarlar. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


