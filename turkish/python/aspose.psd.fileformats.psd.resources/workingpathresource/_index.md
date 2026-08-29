---
title: "WorkingPathResource Sınıfı"
type: docs
weight: 320
url: /tr/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Yeni bir [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady'ın kaynak imzası. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Normal Photoshop kaynak imzası. |
| data_size | int | r | Kaynak veri boyutunu bayt cinsinden alır. |
| id | short | r/w | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| is_disabled | bool | r/w | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| is_inverted | bool | r/w | Bu örneğin ters çevrilip çevrilmediğini gösteren bir değeri alır veya ayarlar. |
| is_not_linked | bool | r/w | Bu örneğin bağlanmamış olduğunu gösteren bir değeri alır veya ayarlar. |
| minimal_version | int | r | Gerekli minimum PSD sürümünü alır. |
| name | string | r/w | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null bir ad iki bayt 0'dan oluşur). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Yol kayıtlarını alır veya ayarlar. |
| signature | int | r | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| boyut | int | r | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| version | int | r/w | Sürümü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Kaynak bloğunu belirtilen akışa kaydeder. |
| validate_values() | Kaynak değerlerini doğrular. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Yeni bir [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| data_bytes | byte | Vektör yolunun verisi. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Kaynak bloğunu belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaynak bloğunun kaydedileceği akış. |

