---
title: "Kelas DataStreamSupporter"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.DataStreamSupporter. Kontainer aliran data"
type: docs
weight: 750
url: /id/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Kontainer aliran data.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapatkan aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Mendapatkan nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [`DataStreamContainer`](./datastreamcontainer/) yang mendasarinya. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Menyimpan data objek ke `DataStreamSupporter` saat ini. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |

### Lihat Juga

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


