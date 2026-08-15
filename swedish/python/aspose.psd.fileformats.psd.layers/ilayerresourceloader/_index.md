---
title: "ILayerResourceLoader-klass"
type: docs
weight: 720
url: /sv/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Bestämmer om lagerresurs kan laddas från den angivna [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Laddar [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Bestämmer om lagerresurs kan laddas från den angivna [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| psd_version | int | PSD-versionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om lagerresurs kan laddas från den angivna [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/); annars <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Laddar [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att ladda från. |
| psd_version | int | PSD-versionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Den laddade resursen. |


