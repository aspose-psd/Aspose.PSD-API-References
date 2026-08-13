---
title: "Sınıf DisplaceSmartFilter"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.DisplaceSmartFilter sınıfı. Displace akıllı filtresi"
type: docs
weight: 3840
url: /tr/net/aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/
---
{{< psd/tize >}}
## DisplaceSmartFilter class

Displace akıllı filtresi.

```csharp
public sealed class DisplaceSmartFilter : SmartFilter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DisplaceSmartFilter](displacesmartfilter/)(string, bool) | `DisplaceSmartFilter` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Karıştırma modunu alır veya ayarlar. |
| [DisplaceMapData](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/displacemapdata/) { get; } | Gömülü yer değiştirme haritası verisini (DspD) alır veya ayarlar. |
| [DisplacementMapPath](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/displacementmappath/) { get; } | DspF yapısından çıkarılan yer değiştirme haritasının tam yolunu alır, bulunamazsa null döner. |
| [DisplacementMethod](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/displacementmethod/) { get; set; } | Yer değiştirme yöntemini alır veya ayarlar. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/filterid/) { get; } | Akıllı filtre türü tanımlayıcısını alır. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/horizontalscale/) { get; set; } | Yatay ölçeği (yüzde) alır veya ayarlar. |
| [IsDisplacementMapEmbedded](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/isdisplacementmapembedded/) { get; } | Gömülü bayrak (EmbF) değerini alır veya ayarlar. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Akıllı filtrenin etkin olup olmadığını alır veya ayarlar. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/name/) { get; } | Akıllı filtre adını alır. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Akıllı filtrenin opaklık değerini alır veya ayarlar. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Akıllı filtre verileri içeren kaynak tanımlayıcı yapısı. |
| [UndefinedAreas](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/undefinedareas/) { get; set; } | Eksik dosya işleme yöntemini alır veya ayarlar. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/verticalscale/) { get; set; } | Dikey ölçeği (yüzde) alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Geçerli filtreyi giriş [`RasterImage`](../../aspose.psd/rasterimage/) görüntüsüne uygular. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Geçerli filtreyi giriş [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) maske verilerine uygular. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Türün geçerli örneğinin üye bazlı klonunu oluşturur. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/filtertype/) | Mevcut akıllı filtrenin tanımlayıcısı (sınıf kimliği "Dspl"). |

### Ayrıca Bakınız

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


