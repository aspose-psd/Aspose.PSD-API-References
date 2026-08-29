---
title: "DataStreamSupporter Sınıfı"
type: docs
weight: 1030
url: /tr/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Nesnenin veri akışını alır. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| önbellekte | bool | r | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| cache_data() | Verileri önbelleğe alır ve temel [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| save() | Nesnenin verilerini mevcut [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) üzerine kaydeder. |
| [save(file_path)](#save_file_path_1) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_3) | Nesnenin verilerini belirtilen akışa kaydeder. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verisinin kaydedileceği dosya yolu. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verisinin kaydedileceği dosya yolu. |
| over_write | bool | eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Nesnenin verilerini belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

