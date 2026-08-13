---
title: "WatermarkResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.WatermarkResource sınıfı. Filigran kaynağı"
type: docs
weight: 4470
url: /tr/net/aspose.psd.fileformats.psd.resources/watermarkresource/
---
{{< psd/tize >}}
## WatermarkResource class

Filigran kaynağı

```csharp
public sealed class WatermarkResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WatermarkResource](watermarkresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/watermarkresource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| [IsWatermark](../../aspose.psd.fileformats.psd.resources/watermarkresource/iswatermark/) { get; set; } | Bu örneğin filigran olup olmadığını belirten bir değeri alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/watermarkresource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Ayrıca Bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


