---
title: "UnitStructure Classe"
type: docs
weight: 180
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitstructure/
---

**Summary:** The unit structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnitStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [UnitStructure(key_name)](#UnitStructure_key_name_1) | Inizializza una nuova istanza della classe [UnitStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifica la chiave della struttura. |
| key | int | r | Ottiene la chiave della struttura. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Ottiene o imposta il nome della chiave. |
| length | int | r | Ottiene la lunghezza in byte della [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | r/w | Ottiene o imposta il tipo di unità. |
| value | double | r/w | Ottiene o imposta il valore. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Ottiene la lunghezza dell'intestazione. |
| [save(stream_container)](#save_stream_container_2) | Salva la struttura nel contenitore di stream specificato. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Salva la struttura nel contenitore di stream specificato. |


### Constructor: UnitStructure(key_name) {#UnitStructure_key_name_1}


```
 UnitStructure(key_name) 
```

Inizializza una nuova istanza della classe [UnitStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitstructure/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Il nome della chiave. |

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

