---
title: "Clase IntegerStructure"
type: docs
weight: 80
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/
---

**Summary:** The integer structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.IntegerStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [IntegerStructure(key_name)](#IntegerStructure_key_name_1) | Inicializa una nueva instancia de la clase [IntegerStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | La clave de la estructura entera. |
| key | int | r | Obtiene la clave. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el nombre de la clave. |
| length | int | r | Obtiene la longitud en bytes de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| value | int | r/w | Obtiene o establece un valor entero. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtiene la longitud del encabezado. |
| [save(stream_container)](#save_stream_container_2) | Guarda la estructura en el contenedor de flujo especificado. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Guarda la estructura en el contenedor de flujo especificado. |


### Constructor: IntegerStructure(key_name) {#IntegerStructure_key_name_1}


```
 IntegerStructure(key_name) 
```

Inicializa una nueva instancia de la clase [IntegerStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El nombre de la clave. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Obtiene la longitud del encabezado.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La longitud del encabezado |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Guarda la estructura en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Guarda la estructura en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |

