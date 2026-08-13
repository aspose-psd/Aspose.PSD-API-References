---
title: "ResolutionInfoResource sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource sınıfı. Çözünürlük bilgisi kaynağı"
type: docs
weight: 4380
url: /tr/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
{{< psd/tize >}}
## ResolutionInfoResource class

Çözünürlük bilgi kaynağı

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | Yatay DPI. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Yükseklik görüntü birimini alır veya ayarlar. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Yatay çözünürlük için görüntü birimleri. Bu sadece kullanıcı arayüzünü etkiler; çözünürlük hâlâ PSD dosyasında piksel/inç olarak saklanır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Gerekli minimum PSD sürümünü alır. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null ad iki bayt 0'dan oluşur). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Veri dahil olmak üzere kaynak blok boyutunu bayt olarak alır. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | Dikey DPI. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Dikey çözünürlük için görüntü birimleri. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Genişlik görüntü birimini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Kaynak bloğunu belirtilen akışa kaydeder. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Kaynak değerlerini doğrular. |

### Ayrıca Bakınız

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


