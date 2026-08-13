---
title: "Sınıf LayerGroupInformationResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.LayerGroupInformationResource sınıfı. Katman grubu bilgi kaynağı"
type: docs
weight: 4280
url: /tr/net/aspose.psd.fileformats.psd.resources/layergroupinformationresource/
---
{{< psd/tize >}}
## LayerGroupInformationResource class

Katman grup bilgisi kaynağı

```csharp
public sealed class LayerGroupInformationResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LayerGroupInformationResource](layergroupinformationresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [Groups](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/groups/) { get; set; } | Grupları alır veya ayarlar. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
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


