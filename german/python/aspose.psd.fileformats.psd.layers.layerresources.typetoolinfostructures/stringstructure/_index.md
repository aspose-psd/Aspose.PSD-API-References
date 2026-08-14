---
title: "StringStructure Klasse"
type: docs
weight: 160
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | Initialisiert eine neue Instanz der Klasse [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/). |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | Initialisiert eine neue Instanz der Klasse [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) mit einem Wert. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Identifiziert den Struktur‑Schlüssel. |
| Schlüssel | int | r | Liest den Schlüssel. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt den Schlüsselnamen. |
| length | int | r | Liest die Länge von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes. |
| Wert | string | r/w | Liest oder setzt den Wert. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Liest die Header-Länge. |
| [save(stream_container)](#save_stream_container_2) | Speichert die Struktur im angegebenen Stream-Container. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Speichert die Struktur im angegebenen Stream-Container. |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

Initialisiert eine neue Instanz der Klasse [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Schlüsselname. |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

Initialisiert eine neue Instanz der Klasse [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) mit einem Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Schlüsselname. |
| Wert | string | Der Wert. |

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

