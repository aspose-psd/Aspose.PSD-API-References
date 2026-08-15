---
title: "Clase EnumeratedDescriptorStructure"
type: docs
weight: 60
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/
---

**Summary:** The enumerated descriptor structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedDescriptorStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EnumeratedDescriptorStructure(key_name, type_id, enum_name)](#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1) | Inicializa una nueva instancia de la clase [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | La clave del descriptor enumerado. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el nombre del enum. |
| key | int | r | Obtiene la clave. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el nombre de la clave. |
| length | int | r | Obtiene la longitud en bytes de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtiene o establece el ID del tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtiene la longitud del encabezado. |
| [save(stream_container)](#save_stream_container_2) | Guarda los datos. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Guarda la estructura en el contenedor de flujo especificado. |


### Constructor: EnumeratedDescriptorStructure(key_name, type_id, enum_name) {#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1}


```
 EnumeratedDescriptorStructure(key_name, type_id, enum_name) 
```

Inicializa una nueva instancia de la clase [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El nombre de la clave. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El ID del tipo. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | El nombre del enum. |

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

Guarda los datos.

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

