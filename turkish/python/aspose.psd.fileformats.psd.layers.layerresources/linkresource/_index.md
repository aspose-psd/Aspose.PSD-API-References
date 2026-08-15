---
title: "LinkResource Sınıfı"
type: docs
weight: 540
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---

**Summary:** Defines the LinkResource class that contains information about linked or embedded files in the PSD format image.<br/>            The link resource may contain several [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instances which can be accessed by indexers in any derived class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| data_source_count | int | r | Dizleyici tarafından erişilebilen bağlantı veri kaynaklarının sayısını alır. |
| is_empty | bool | r | Bu bağlantı kaynağı örneğinin boş olup olmadığını gösteren bir değeri alır. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | PSD genel bağlantı kaynağı uzunluğunu bayt cinsinden alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynak blok verisini kaydeder. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Kaynak blok verisini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

