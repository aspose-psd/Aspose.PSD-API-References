---
title: "Classe StringStructure"
type: docs
weight: 160
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | Inizializza una nuova istanza della classe [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/). |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | Inizializza una nuova istanza della classe [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) con valore. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifica la chiave della struttura. |
| key | int | r | Ottiene la chiave. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Ottiene o imposta il nome della chiave. |
| length | int | r | Ottiene la lunghezza in byte della [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| value | string | r/w | Ottiene o imposta il valore. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Ottiene la lunghezza dell'intestazione. |
| [save(stream_container)](#save_stream_container_2) | Salva la struttura nel contenitore di stream specificato. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Salva la struttura nel contenitore di stream specificato. |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

Inizializza una nuova istanza della classe [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Il nome della chiave. |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

Inizializza una nuova istanza della classe [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) con valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Il nome della chiave. |
| value | string | Il valore. |

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

