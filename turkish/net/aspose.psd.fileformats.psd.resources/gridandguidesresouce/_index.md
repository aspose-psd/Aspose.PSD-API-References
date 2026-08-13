---
title: "Sınıf GridAndGuidesResouce"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce sınıfı. Izgara ve kılavuzlar kaynağını temsil eder"
type: docs
weight: 4230
url: /tr/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
{{< psd/tize >}}
## GridAndGuidesResouce class

Izgara ve kılavuzlar kaynağını temsil eder.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Kaynak veri boyutunu bayt olarak alır. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Yatay ızgara döngüsünü alır veya ayarlar. Varsayılan değer 576'dir. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Dikey ızgara döngüsünü alır veya ayarlar. Varsayılan değer 576'dir. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Kılavuz kaynağı blok sayısını alır. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Kılavuzları alır veya ayarlar. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Üstbilgi sürümünü alır veya ayarlar. Bu değer her zaman 1 olmalıdır. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Gerekli minimum psd sürümünü alır. |
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


