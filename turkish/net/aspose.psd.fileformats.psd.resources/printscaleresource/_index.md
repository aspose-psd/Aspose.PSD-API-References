---
title: "PrintScaleResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.PrintScaleResource sınıfı. Baskı ölçeği kaynağı."
type: docs
weight: 4340
url: /tr/net/aspose.psd.fileformats.psd.resources/printscaleresource/
---
{{< psd/tize >}}
## PrintScaleResource class

Yazdırma Ölçeği kaynağı

```csharp
public sealed class PrintScaleResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PrintScaleResource](printscaleresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/printscaleresource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/printscaleresource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Scale](../../aspose.psd.fileformats.psd.resources/printscaleresource/scale/) { get; set; } | Ölçeği alır veya ayarlar. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |
| [Style](../../aspose.psd.fileformats.psd.resources/printscaleresource/style/) { get; set; } | Stili alır veya ayarlar. |
| [XLocation](../../aspose.psd.fileformats.psd.resources/printscaleresource/xlocation/) { get; set; } | x konumunu alır veya ayarlar. |
| [YLocation](../../aspose.psd.fileformats.psd.resources/printscaleresource/ylocation/) { get; set; } | y konumunu alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Ayrıca Bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


