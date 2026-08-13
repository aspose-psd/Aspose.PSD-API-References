---
title: "Sınıf ResourceBlock"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.ResourceBlock sınıfı. Kaynak bloğu"
type: docs
weight: 4100
url: /tr/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
## ResourceBlock class

Kaynak bloğu.

```csharp
public abstract class ResourceBlock
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady'ın kaynak imzası. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | Normal Photoshop kaynak imzası. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | Kaynak blok durumunu temsil eder. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


