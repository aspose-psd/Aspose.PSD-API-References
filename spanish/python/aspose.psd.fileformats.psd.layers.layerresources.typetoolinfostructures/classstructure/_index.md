---
title: "Clase ClassStructure"
type: docs
weight: 30
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | Inicializa una nueva instancia de la clase [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | Identifica la clave de la estructura. |
| STRUCTURE_KEY_GLBC [static] | int | r | Identifica la clave de la estructura. |
| STRUCTURE_KEY_TYPE [static] | int | r | Identifica la clave de la estructura. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el ID de la clase. |
| class_name | string | r/w | Obtiene o establece el nombre de la clase. |
| key | int | r | Obtiene la clave de la estructura. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el nombre de la clave. |
| length | int | r | Obtiene la longitud en bytes de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtiene la longitud del encabezado. |
| [save(stream_container)](#save_stream_container_2) | Guarda la estructura en el contenedor de flujo especificado. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Guarda la estructura en el contenedor de flujo especificado. |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

Inicializa una nueva instancia de la clase [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nombre de la clave. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El ID de la clase. |
| structure_key | int | La clave de estructura. |

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

