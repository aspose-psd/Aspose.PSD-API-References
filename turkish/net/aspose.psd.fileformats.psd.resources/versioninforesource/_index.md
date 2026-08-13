---
title: "VersionInfoResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.VersionInfoResource sınıfı. Sürüm Bilgisi kaynağı"
type: docs
weight: 4460
url: /tr/net/aspose.psd.fileformats.psd.resources/versioninforesource/
---
{{< psd/tize >}}
## VersionInfoResource class

Sürüm Bilgi kaynağı

```csharp
public sealed class VersionInfoResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [VersionInfoResource](versioninforesource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/versioninforesource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [FileVersion](../../aspose.psd.fileformats.psd.resources/versioninforesource/fileversion/) { get; set; } | Dosya sürümünü alır veya ayarlar. |
| [HasRealMergedData](../../aspose.psd.fileformats.psd.resources/versioninforesource/hasrealmergeddata/) { get; set; } | Bu örneğin gerçek birleştirilmiş veri içerip içermediğini gösteren değeri alır veya ayarlar. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/versioninforesource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [ReaderName](../../aspose.psd.fileformats.psd.resources/versioninforesource/readername/) { get; set; } | Okuyucunun adını alır veya ayarlar. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |
| [Version](../../aspose.psd.fileformats.psd.resources/versioninforesource/version/) { get; set; } | Sürümü alır veya ayarlar. |
| [WriterName](../../aspose.psd.fileformats.psd.resources/versioninforesource/writername/) { get; set; } | Yazıcının adını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Ayrıca Bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


