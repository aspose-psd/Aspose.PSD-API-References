---
title: "EnumeratedDescriptorStructure Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/
---

**Summary:** The enumerated descriptor structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedDescriptorStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EnumeratedDescriptorStructure(key_name, type_id, enum_name)](#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1) | Initialisiert eine neue Instanz der [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Der enumerierte Deskriptorschlüssel. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt den Enum-Namen. |
| Schlüssel | int | r | Liest den Schlüssel. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt den Schlüsselnamen. |
| length | int | r | Liest die Länge von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt die Typ-ID. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Liest die Header-Länge. |
| [save(stream_container)](#save_stream_container_2) | Speichert die Daten. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Speichert die Struktur im angegebenen Stream-Container. |


### Constructor: EnumeratedDescriptorStructure(key_name, type_id, enum_name) {#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1}


```
 EnumeratedDescriptorStructure(key_name, type_id, enum_name) 
```

Initialisiert eine neue Instanz der [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Schlüsselname. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Die Typ-ID. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Der Enum-Name. |

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

Speichert die Daten.

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

