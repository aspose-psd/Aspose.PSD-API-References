---
title: "Clase StringStructure"
type: docs
weight: 160
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | Inicializa una nueva instancia de la clase [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/). |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | Inicializa una nueva instancia de la clase [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) con valor. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifica la clave de la estructura. |
| key | int | r | Obtiene la clave. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el nombre de la clave. |
| length | int | r | Obtiene la longitud en bytes de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| value | string | r/w | Obtiene o establece el valor. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtiene la longitud del encabezado. |
| [save(stream_container)](#save_stream_container_2) | Guarda la estructura en el contenedor de flujo especificado. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Guarda la estructura en el contenedor de flujo especificado. |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

Inicializa una nueva instancia de la clase [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El nombre de la clave. |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

Inicializa una nueva instancia de la clase [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) con valor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El nombre de la clave. |
| value | string | El valor. |

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

