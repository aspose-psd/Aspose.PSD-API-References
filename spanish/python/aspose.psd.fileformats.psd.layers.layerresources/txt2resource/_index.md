---
title: "Clase Txt2Resource"
type: docs
weight: 970
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Inicializa una nueva instancia de la clase Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| datos | byte | r/w | Obtiene o establece los datos. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Agrega el registro de texto a Resource y devuelve el id del registro de texto. |
| [get_text_data()](#get_text_data__2) | Obtiene el registro de texto de los datos del recurso. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Guarda el contenedor de flujo especificado. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Inicializa una nueva instancia de la clase Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Agrega el registro de texto a Resource y devuelve el id del registro de texto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | string | El texto del registro. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Los límites. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Devuelve el Id del registro de texto para el recurso |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Obtiene el registro de texto de los datos del recurso.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Matriz de registro de texto |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Guarda el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| psd_version | int | La versión PSD. |

