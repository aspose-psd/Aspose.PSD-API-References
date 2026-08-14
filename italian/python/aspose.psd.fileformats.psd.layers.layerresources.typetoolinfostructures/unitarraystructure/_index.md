---
title: "UnitArrayStructure Classe"
type: docs
weight: 170
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---

**Summary:** Defines the UnitArrayStructure class that holds float values array and their measure unit.<br/>            It is used in the PSD file resources, usually by [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnitArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [UnitArrayStructure(key_name, unit_type, values)](#UnitArrayStructure_key_name_unit_type_values_1) | Inizializza una nuova istanza della classe [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Definisce la chiave 'UnFl' della [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/). |
| key | int | r | Ottiene questa chiave della struttura dell'array di unità. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Ottiene o imposta il nome della chiave. |
| length | int | r | Ottiene la lunghezza in byte della [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | r/w | Ottiene o imposta il tipo di unità di misura dei valori della [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/). |
| value_count | int | r | Ottiene il conteggio dei valori. |
| valori | double | r/w | Ottiene o imposta i valori della struttura dell'array di unità. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Ottiene la lunghezza dell'intestazione. |
| [save(stream_container)](#save_stream_container_2) | Salva la struttura nel contenitore di stream specificato. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Salva la struttura nel contenitore di stream specificato. |


### Constructor: UnitArrayStructure(key_name, unit_type, values) {#UnitArrayStructure_key_name_unit_type_values_1}


```
 UnitArrayStructure(key_name, unit_type, values) 
```

Inizializza una nuova istanza della classe [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nome della chiave. |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | Tipo dell'unità. |
| valori | double | I valori. |

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

