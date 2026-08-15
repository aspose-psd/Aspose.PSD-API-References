---
title: "Clase LmskResource"
type: docs
weight: 560
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | Inicializa una nueva instancia de la clase [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| color_component1 | ushort | r/w | Obtiene el componente de color 1. |
| color_component2 | ushort | r/w | Obtiene el componente de color 2. |
| color_component3 | ushort | r/w | Obtiene el componente de color 3. |
| color_component4 | ushort | r/w | Obtiene el componente de color 4. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | Obtiene el espacio de color. |
| bandera | byte | r | Obtiene la bandera. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| opacity | short | r/w | Obtiene la opacidad. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

Inicializa una nueva instancia de la clase [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/).

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

