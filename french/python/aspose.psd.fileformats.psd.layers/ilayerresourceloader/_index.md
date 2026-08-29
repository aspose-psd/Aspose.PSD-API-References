---
title: "Classe ILayerResourceLoader"
type: docs
weight: 720
url: /fr/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Détermine si la ressource de calque peut être chargée depuis le [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) spécifié. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Charge le [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Détermine si la ressource de calque peut être chargée depuis le [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| psd_version | int | La version PSD. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si la ressource de calque peut être chargée depuis le [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) spécifié ; sinon, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Charge le [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux depuis lequel charger. |
| psd_version | int | La version PSD. |

**Returns**

| Type | Description |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | La ressource chargée. |


