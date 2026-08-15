---
title: "VersionInfoResource Sınıfı"
type: docs
weight: 300
url: /tr/python-net/aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Summary:** Version Info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.VersionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [VersionInfoResource()](#VersionInfoResource__1) | VersionInfoResource sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady'ın kaynak imzası. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Normal Photoshop kaynak imzası. |
| data_size | int | r | Kaynak veri boyutunu bayt cinsinden alır. |
| file_version | uint | r/w | Dosya sürümünü alır veya ayarlar. |
| has_real_merged_data | bool | r/w | Bu örneğin gerçek birleştirilmiş veri içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| id | short | r/w | Kaynak için benzersiz tanımlayıcıyı alır veya ayarlar. |
| minimal_version | int | r | Gerekli minimum PSD sürümünü alır. |
| name | string | r/w | Kaynak adını alır veya ayarlar. Pascal dizesi, boyutu çift yapmak için doldurulur (null bir ad iki bayt 0'dan oluşur). |
| reader_name | string | r/w | Okuyucunun adını alır veya ayarlar. |
| signature | int | r | Kaynak imzasını alır. Her zaman '8BIM' olmalıdır. |
| boyut | int | r | Veri dahil olmak üzere kaynak blok boyutunu bayt cinsinden alır. |
| version | uint | r/w | Sürümü alır veya ayarlar. |
| writer_name | string | r/w | Yazıcının adını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Kaynak bloğunu belirtilen akışa kaydeder. |
| validate_values() | Kaynak değerlerini doğrular. |


### Constructor: VersionInfoResource() {#VersionInfoResource__1}


```
 VersionInfoResource() 
```

VersionInfoResource sınıfının yeni bir örneğini başlatır.

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Kaynak bloğunu belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaynak bloğunun kaydedileceği akış. |

