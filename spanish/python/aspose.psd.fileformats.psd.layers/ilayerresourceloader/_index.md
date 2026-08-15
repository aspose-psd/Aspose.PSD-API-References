---
title: "Clase ILayerResourceLoader"
type: docs
weight: 720
url: /es/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Determina si el recurso de capa puede cargarse desde el [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) especificado. |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Carga el [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Determina si el recurso de capa puede cargarse desde el [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| psd_version | int | La versión PSD. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si el recurso de capa puede cargarse desde el [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) especificado; de lo contrario, <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Carga el [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo desde el cual cargar. |
| psd_version | int | La versión PSD. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | El recurso cargado. |


