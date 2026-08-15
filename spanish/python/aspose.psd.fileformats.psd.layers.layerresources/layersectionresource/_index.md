---
title: "Clase LayerSectionResource"
type: docs
weight: 460
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/
---

**Summary:** The layer section resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LayerSectionResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LayerSectionResource()](#LayerSectionResource__1) | Inicializa una nueva instancia de la clase [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Obtiene o establece la clave del modo de fusión. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| section_type | [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype) | r/w | Obtiene o establece el tipo de sección. |
| signature | int | r | Obtiene la firma. |
| subtype | [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype) | r/w | Obtiene o establece el subtipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: LayerSectionResource() {#LayerSectionResource__1}


```
 LayerSectionResource() 
```

Inicializa una nueva instancia de la clase [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/).

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

