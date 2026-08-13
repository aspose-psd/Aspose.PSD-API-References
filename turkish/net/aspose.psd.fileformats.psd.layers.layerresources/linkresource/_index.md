---
title: "Sınıf LinkResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource sınıfı. PSD formatındaki görüntüde bağlanmış veya gömülü dosyalar hakkında bilgi içeren LinkResource sınıfını tanımlar. Bağlantı kaynağı, türetilen herhangi bir sınıfta indeksleyicilerle erişilebilen birkaç LinkDataSource örneği içerebilir."
type: docs
weight: 3010
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

PSD formatındaki görüntüde bağlanmış veya gömülü dosyalar hakkında bilgi içeren LinkResource sınıfını tanımlar. Bağlantı kaynağı, türetilen herhangi bir sınıfta indeksleyicilerle erişilebilen birkaç [`LinkDataSource`](../linkdatasource/) örneği içerebilir.

```csharp
public abstract class LinkResource : LayerResource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | İndeksleyiciyle erişilebilen bağlantı veri kaynaklarının sayısını alır. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Bu bağlantı kaynağı örneğinin boş olup olmadığını gösteren bir değeri alır. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Belirtilen indeksteki [`LinkDataSource`](../linkdatasource/) öğesini alır; bu, bağlantı veri kaynağının benzersiz tanımlayıcısıdır. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD genel bağlantı kaynağı uzunluğunu bayt olarak alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Kaynak blok verisini kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


