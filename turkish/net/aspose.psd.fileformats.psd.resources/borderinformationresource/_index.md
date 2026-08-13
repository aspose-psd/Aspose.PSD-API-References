---
title: "Sınıf BorderInformationResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource sınıfı. Görüntü baskı ayarlarının kenar bilgilerini içeren kaynak"
type: docs
weight: 4140
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
{{< psd/tize >}}
## BorderInformationResource class

Görüntü yazdırma ayarlarının kenar bilgilerini içeren kaynak.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Kenar birimlerini alır veya ayarlar. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Kenar genişliğini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

## Örnekler

Aşağıdaki örnek, BorderInformationResource kaynağının desteğini gösterir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // güncelle BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


