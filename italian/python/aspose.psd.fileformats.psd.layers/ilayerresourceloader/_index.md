---
title: "Classe ILayerResourceLoader"
type: docs
weight: 720
url: /it/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Determina se la risorsa del layer può essere caricata dal [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) specificato. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Carica il [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Determina se la risorsa del layer può essere caricata dal [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |
| psd_version | int | La versione PSD. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se la risorsa del layer può essere caricata dal [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) specificato; altrimenti, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Carica il [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream da cui caricare. |
| psd_version | int | La versione PSD. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | La risorsa caricata. |


