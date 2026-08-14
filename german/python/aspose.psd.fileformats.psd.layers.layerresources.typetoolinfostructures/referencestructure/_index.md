---
title: "ReferenceStructure Klasse"
type: docs
weight: 150
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/referencestructure/
---

**Summary:** The reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ReferenceStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ReferenceStructure(key_name)](#ReferenceStructure_key_name_1) | Initialisiert eine neue Instanz der [ReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/referencestructure/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifiziert den Struktur‑Schlüssel. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt eine Kopie eines Arrays von Strukturen. |
| Schlüssel | int | r | Liest den Struktur‑Schlüssel. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt den Schlüsselnamen. |
| length | int | r | Liest die Länge von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Liest die Header-Länge. |
| [save(stream_container)](#save_stream_container_2) | Speichert die Struktur im angegebenen Stream-Container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Speichert die Struktur im angegebenen Stream-Container. |


### Constructor: ReferenceStructure(key_name) {#ReferenceStructure_key_name_1}


```
 ReferenceStructure(key_name) 
```

Initialisiert eine neue Instanz der [ReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/referencestructure/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Schlüsselname. |

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

