---
title: "ClblResource Sınıfı"
type: docs
weight: 160
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Yeni bir [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) sınıfı örneği başlatır. |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Yeni bir [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) sınıfı örneği başlatır. |
| [ClblResource(data)](#ClblResource_data_3) | Yeni bir [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) sınıfı örneği başlatır.<br/>            Özel veya bilinmeyen değer ile |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| blend_clipped_elements | bool | r/w | Kesilmiş öğelerin karıştırılıp karıştırılmayacağını gösteren bir değeri alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Belirtilen akış konteynerini kaydeder. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Yeni bir [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) sınıfı örneği başlatır.

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Yeni bir [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| blend_clipped_elements | bool | eğer <c>true</c> [kesilmiş öğeleri karıştır]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Yeni bir [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) sınıfı örneği başlatır.<br/>            Özel veya bilinmeyen değer ile

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynak verisi. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Belirtilen akış konteynerini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

