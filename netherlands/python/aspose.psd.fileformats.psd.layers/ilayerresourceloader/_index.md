---
title: "ILayerResourceLoader Klasse"
type: docs
weight: 720
url: /nl/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Bepaalt of de laagresource kan worden geladen vanuit de opgegeven [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Laadt de [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Bepaalt of de laagresource kan worden geladen vanuit de opgegeven [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| psd_version | int | De PSD‑versie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als de laagresource kan worden geladen vanuit de opgegeven [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/); anders, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Laadt de [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om van te laden. |
| psd_version | int | De PSD‑versie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | De geladen resource. |


