---
title: "Sınıf DataStreamSupporter"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.DataStreamSupporter sınıfı. Veri akışı konteyneri"
type: docs
weight: 750
url: /tr/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Veri akışı konteyneri.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekmediğini gösteren bir değeri alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](./datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Nesnenin verilerini mevcut `DataStreamSupporter`'a kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |

### Ayrıca Bakınız

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


