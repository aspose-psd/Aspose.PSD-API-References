---
title: Class BorderInformationResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource sınıf. Görüntü yazdırma ayarlarının sınır bilgilerini içeren kaynak.
type: docs
weight: 3650
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
## BorderInformationResource class

Görüntü yazdırma ayarlarının sınır bilgilerini içeren kaynak.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Kaynak veri boyutunu bayt cinsinden alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Gereken minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Boyutu çift yapmak için doldurulmuş Pascal dizesi (boş ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Verileri dahil olmak üzere kaynak bloğu boyutunu bayt cinsinden alır. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Sınır birimlerini alır veya ayarlar. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Kenarlık genişliğini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Örnekler

Aşağıdaki örnek, BorderInformationResource kaynağının desteğini göstermektedir.

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

    // BorderInformationResource'u güncelle
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* toplantı [Aspose.PSD](../../)


