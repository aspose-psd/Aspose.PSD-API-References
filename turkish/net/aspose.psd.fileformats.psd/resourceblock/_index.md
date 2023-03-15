---
title: Class ResourceBlock
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.ResourceBlock sınıf. Kaynak bloğu.
type: docs
weight: 3610
url: /tr/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

Kaynak bloğu.

```csharp
public abstract class ResourceBlock
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Kaynak veri boyutunu bayt cinsinden alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Gereken minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Boyutu çift yapmak için doldurulmuş Pascal dizesi (boş ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Verileri dahil olmak üzere kaynak bloğu boyutunu bayt cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady. kaynak imzası |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | Normal Photoshop kaynak imzası. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | Kaynak bloğu durumunu temsil eder. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* toplantı [Aspose.PSD](../../)


