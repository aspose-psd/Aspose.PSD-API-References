---
title: "ILayerResourceLoader Klasse"
type: docs
weight: 720
url: /de/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Bestimmt, ob die Ebenenressource aus dem angegebenen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) geladen werden kann. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Lädt die [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Bestimmt, ob die Ebenenressource aus dem angegebenen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) geladen werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn die Ebenenressource aus dem angegebenen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) geladen werden kann; andernfalls <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Lädt die [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container, aus dem geladen werden soll. |
| psd_version | int | Die PSD-Version. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Die geladene Ressource. |


