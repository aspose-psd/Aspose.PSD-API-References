---
title: "Sınıf ShmdResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ShmdResource sınıf. ShmdResource sınıf. Meta veri ayarları"
type: docs
weight: 3330
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---
{{< psd/tize >}}
## ShmdResource class

Sınıf ShmdResource. Meta veri ayarları

```csharp
public class ShmdResource : LayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ShmdResource](shmdresource/#constructor)() | Yeni bir `ShmdResource` sınıf örneği başlatır. |
| [ShmdResource](shmdresource/#constructor_1)(byte[]) | Yeni bir `ShmdResource` sınıf örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| [LayerCreatedDateTime](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/layercreateddatetime/) { get; set; } | Katmanın oluşturulma zamanını alır veya ayarlar. Katman oluşturulma zamanı belirtilmemişse yeni DateTime(0) döndürür. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [SubResources](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/) { get; } | shmd kaynağının alt kaynaklarını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/save/)(StreamContainer, int) | Belirtilen akış konteynerini kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [SubResourceHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresourceheaderlength/) | Alt kaynak başlık uzunluğu |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


