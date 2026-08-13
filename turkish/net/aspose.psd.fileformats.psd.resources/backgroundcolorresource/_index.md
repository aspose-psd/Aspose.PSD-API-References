---
title: "Sınıf BackgroundColorResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource sınıfı. Görüntü baskı ayarlarının kenar bilgileri içeren kaynak"
type: docs
weight: 4130
url: /tr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
{{< psd/tize >}}
## BackgroundColorResource class

Görüntü yazdırma ayarlarının kenar bilgilerini içeren kaynak.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | Arka plan rengini alır veya ayarlar. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

## Örnekler

Aşağıdaki örnek, BackgroundColorResource kaynağının desteğini gösterir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // BackgroundColorResource güncelle
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


