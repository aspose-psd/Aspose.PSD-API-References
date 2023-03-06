---
title: Class LinkResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource sınıf. PSD biçimindeki görüntüdeki bağlantılı veya katıştırılmış dosyalar hakkında bilgi içeren LinkResource sınıfını tanımlar. Bağlantı kaynağı birkaç tane içerebilirLinkDataSource herhangi bir türetilmiş sınıftaki indeksleyiciler tarafından erişilebilen örnekler.
type: docs
weight: 2710
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

PSD biçimindeki görüntüdeki bağlantılı veya katıştırılmış dosyalar hakkında bilgi içeren LinkResource sınıfını tanımlar. Bağlantı kaynağı birkaç tane içerebilir[`LinkDataSource`](../linkdatasource/) herhangi bir türetilmiş sınıftaki indeksleyiciler tarafından erişilebilen örnekler.

```csharp
public abstract class LinkResource : LayerResource
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Dizin oluşturucu tarafından erişilebilen bağlantı veri kaynaklarının sayısını alır. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Bu bağlantı kaynağı örneğinin boş olup olmadığını gösteren bir değer alır. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Şunu alır:[`LinkDataSource`](../linkdatasource/) bağlantı veri kaynağı benzersiz tanımlayıcısı olan belirtilen dizinde.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD genel bağlantı kaynağı uzunluğunu bayt olarak alır. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | PSD biçimi sürümünü alır. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | PSD genel bağlantı kaynağı imzasını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Kaynak bloğu verilerini kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

### Ayrıca bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


