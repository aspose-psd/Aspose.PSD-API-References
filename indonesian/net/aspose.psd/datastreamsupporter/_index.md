---
title: Class DataStreamSupporter
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.DataStreamSupporter kelas. Wadah aliran data.
type: docs
weight: 740
url: /id/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

Wadah aliran data.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapat aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Mendapat nilai yang menunjukkan apakah data objek di-cache saat ini dan tidak diperlukan pembacaan data. |

## Metode

| Nama | Keterangan |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Meng-cache data dan memastikan tidak ada pemuatan data tambahan yang dilakukan dari dasarnya[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Menyimpan data objek ke saat ini`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |

### Lihat juga

* class [DisposableObject](../disposableobject/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


