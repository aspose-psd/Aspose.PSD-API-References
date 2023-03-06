---
title: Class UnknownResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Resources.UnknownResource sınıf. Bilinmeyen kaynak. Bir kaynak bloğu tanınmadığında bu kaynak bloğu oluşturulur.
type: docs
weight: 3940
url: /tr/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
## UnknownResource class

Bilinmeyen kaynak. Bir kaynak bloğu tanınmadığında bu kaynak bloğu oluşturulur.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Kaynak verilerini alır. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Kaynak veri boyutunu bayt cinsinden alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Gereken minimum psd sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Boyutu çift yapmak için doldurulmuş Pascal dizesi (boş ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Verileri dahil olmak üzere kaynak bloğu boyutunu bayt cinsinden alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Ayrıca bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* toplantı [Aspose.PSD](../../)


