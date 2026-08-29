---
title: "ILayerResourceLoader Sınıfı"
type: docs
weight: 720
url: /tr/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Belirtilen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) üzerinden katman kaynağının yüklenip yüklenemeyeceğini belirler. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) yükler. |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Belirtilen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) üzerinden katman kaynağının yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer katman kaynağı belirtilen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) üzerinden yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

[LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Yüklenecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Yüklenen kaynak. |


