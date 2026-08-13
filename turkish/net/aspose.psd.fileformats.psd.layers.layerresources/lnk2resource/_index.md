---
title: "Sınıf Lnk2Resource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource sınıfı. PSD formatındaki görüntüde gömülü dosyalar hakkında bilgi içeren sınıfı tanımlar. Bağlantı kaynağı, indeksleyici ile erişilebilen birkaç LiFdDataSource örneği içerebilir."
type: docs
weight: 3030
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

PSD formatındaki görüntüde gömülü dosyalar hakkında bilgi içeren sınıfı tanımlar. Bağlantı kaynağı, indeksleyici ile erişilebilen birkaç [`LiFdDataSource`](../lifddatasource/) örneği içerebilir.

```csharp
public class Lnk2Resource : LinkResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | Yeni bir `Lnk2Resource` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | İndeksleyiciyle erişilebilen bağlantı veri kaynaklarının sayısını alır. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Bu bağlantı kaynağı örneğinin boş olup olmadığını gösteren bir değeri alır. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Belirtilen indeksteki [`LiFdDataSource`](../lifddatasource/) öğesini alır. (2 indeksleyici) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD genel bağlantı kaynağı uzunluğunu bayt olarak alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Kaynak blok verisini kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


