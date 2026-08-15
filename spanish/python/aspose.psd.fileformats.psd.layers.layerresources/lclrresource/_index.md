---
title: "Clase LclrResource"
type: docs
weight: 470
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | Inicializa una nueva instancia de la clase [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(color)](#LclrResource_color_2) | Inicializa una nueva instancia de la clase [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(data)](#LclrResource_data_3) | Inicializa una nueva instancia de la clase [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Obtiene o establece el color de la capa. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

Inicializa una nueva instancia de la clase [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

Inicializa una nueva instancia de la clase [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | El color. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

Inicializa una nueva instancia de la clase [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos del recurso. |

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

