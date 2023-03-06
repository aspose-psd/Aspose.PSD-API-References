---
title: Class DataStreamSupporter
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.DataStreamSupporter sınıf. Veri akışı kabı.
type: docs
weight: 740
url: /tr/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

Veri akışı kabı.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temelden ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Nesnenin verilerini geçerli belleğe kaydeder.`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |

### Ayrıca bakınız

* class [DisposableObject](../disposableobject/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


