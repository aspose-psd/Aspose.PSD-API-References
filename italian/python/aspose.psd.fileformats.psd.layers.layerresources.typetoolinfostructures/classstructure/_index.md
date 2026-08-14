---
title: "ClassStructure Classe"
type: docs
weight: 30
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | Inizializza una nuova istanza della classe [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | Identifica la chiave della struttura. |
| STRUCTURE_KEY_GLBC [static] | int | r | Identifica la chiave della struttura. |
| STRUCTURE_KEY_TYPE [static] | int | r | Identifica la chiave della struttura. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Ottiene o imposta l'ID della classe. |
| class_name | string | r/w | Ottiene o imposta il nome della classe. |
| key | int | r | Ottiene la chiave della struttura. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Ottiene o imposta il nome della chiave. |
| length | int | r | Ottiene la lunghezza in byte della [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Ottiene la lunghezza dell'intestazione. |
| [save(stream_container)](#save_stream_container_2) | Salva la struttura nel contenitore di stream specificato. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Salva la struttura nel contenitore di stream specificato. |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

Inizializza una nuova istanza della classe [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nome della chiave. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID della classe. |
| structure_key | int | La chiave della struttura. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Ottiene la lunghezza dell'intestazione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La lunghezza dell'intestazione |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Salva la struttura nel contenitore di stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Salva la struttura nel contenitore di stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |

