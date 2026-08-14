---
title: "Kelas DataStreamSupporter"
type: docs
weight: 1030
url: /id/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Mendapatkan aliran data objek. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| tersimpan_di_cache | bool | r | Mendapatkan nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| cache_data() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) yang mendasari. |
| save() | Menyimpan data objek ke [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) saat ini. |
| [save(file_path)](#save_file_path_1) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(stream)](#save_stream_3) | Menyimpan data objek ke aliran yang ditentukan. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |
| over_write | bool | jika disetel ke <c>true</c> menimpa isi file, jika tidak akan menambahkan. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data objek. |

