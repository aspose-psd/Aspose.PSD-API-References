---
title: "ObjectArrayStructure Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | Initialisiert eine neue Instanz der [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) Klasse. |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | Initialisiert eine neue Instanz der [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifiziert den 'ObAr' Struktur-Schlüssel. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt die Klassen-ID des Objektarrays. |
| class_name | string | r/w | Liest oder setzt den Klassennamen des Objektarrays. |
| Schlüssel | int | r | Liest den Struktur-Schlüssel des Objektarrays. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt den Schlüsselnamen. |
| length | int | r | Liest die Länge von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes. |
| structure_count | int | r | Liest die Anzahl der Untersstrukturen des Objektarrays. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt eine Kopie eines Arrays von Strukturen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Liest die Header-Länge. |
| [save(stream_container)](#save_stream_container_2) | Speichert die Struktur im angegebenen Stream-Container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Speichert die Struktur im angegebenen Stream-Container. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

Initialisiert eine neue Instanz der [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | int | Der ganzzahlige Schlüssel. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Schlüsselname. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Klassenbezeichner. |
| class_name | string | Name der Klasse. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Die Strukturen. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

Initialisiert eine neue Instanz der [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key_name | string | Name des Schlüssels. |
| class_id_name | string | Name des Klassenbezeichners. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Die Strukturen. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Liest die Header-Länge.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Header-Länge |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Speichert die Struktur im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Speichert die Struktur im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |

