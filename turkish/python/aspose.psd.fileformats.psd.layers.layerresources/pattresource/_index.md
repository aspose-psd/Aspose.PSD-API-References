---
title: "PattResource Sınıfı"
type: docs
weight: 770
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PattResource()](#PattResource__1) | Yeni bir [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) sınıfının örneğini başlatır. |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Yeni bir [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | 'Patt' tip araç bilgi anahtarı 8-bit için. |
| TYPE_TOOL_KEY2 [static] | int | r | 'Pat2' tip araç bilgi anahtarı 16-bit için. |
| TYPE_TOOL_KEY3 [static] | int | r | 'Pat3' tip araç bilgi anahtarı 32-bit için. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Desen verilerini alır veya ayarlar; |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynak blok verisini kaydeder. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Yeni bir [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) sınıfının örneğini başlatır.

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Yeni bir [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | int | Kaynak türü anahtarı. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Desen verileri. |

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

