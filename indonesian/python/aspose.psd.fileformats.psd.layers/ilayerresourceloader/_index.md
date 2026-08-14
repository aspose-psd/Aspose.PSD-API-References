---
title: "ILayerResourceLoader Kelas"
type: docs
weight: 720
url: /id/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Menentukan apakah sumber daya lapisan dapat dimuat dari [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) yang ditentukan. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Memuat [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Menentukan apakah sumber daya lapisan dapat dimuat dari [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| psd_version | int | Versi PSD. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika sumber daya lapisan dapat dimuat dari [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) yang ditentukan; sebaliknya, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Memuat [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk dimuat. |
| psd_version | int | Versi PSD. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Sumber daya yang dimuat. |


