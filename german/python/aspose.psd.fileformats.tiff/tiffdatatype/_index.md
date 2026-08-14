---
title: "TiffDataType Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Liest die zusätzliche Datengröße in Bytes (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern). |
| Anzahl | uint | r | Liest die Anzahl der Elemente. |
| data_size | uint | r | Liest die zusätzliche Datengröße in Bytes (falls die 12 Bytes nicht ausreichen, um die Tag-Daten zu speichern). |
| id | ushort | r | Liest die ganzzahlige Darstellung der Tag-ID. |
| is_valid | bool | r | Liest einen Wert, der angibt, ob Tag-Daten gültig sind. Der gültige Tag enthält Daten, die erhalten bleiben können. Der ungültige Tag kann nicht gespeichert werden. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Liest die Tag-ID. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Liest den Tag-Typ. |
| Wert | object | r/w | Liest oder setzt den Wert, den dieser Datentyp enthält. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge liegt. |
| [deep_clone()](#deep_clone__2) | Führt eine tiefe Kopie dieser Instanz aus. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Liest die Tag-Daten. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Schreibt die zusätzlichen Tag-Daten. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Schreibt die Tag-Daten. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt eine Ganzzahl zurück, die angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| obj | object | Ein Objekt zum Vergleich mit dieser Instanz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein 32‑Bit‑vorzeichenbehafteter Integer, der die relative Reihenfolge der zu vergleichenden Objekte angibt. Der Rückgabewert hat folgende Bedeutungen:<br/>            Wert<br/>            Bedeutung<br/>            Kleiner als Null<br/>            Diese Instanz ist kleiner als <paramref name="obj" />.<br/>            Null<br/>            Diese Instanz ist gleich <paramref name="obj" />.<br/>            Größer als Null<br/>            Diese Instanz ist größer als <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Führt eine tiefe Kopie dieser Instanz aus.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Eine tiefe Kopie der aktuellen Instanz. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Liest die Tag-Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Der Datenstrom. |
| Position | long | Die Tag-Position. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Das gelesene Tag. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Schreibt die zusätzlichen Tag-Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Der Datenstrom. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long | Die tatsächlich geschriebenen Bytes. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Schreibt die Tag-Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Der Datenstrom. |
| additional_data_offset | long | Der Offset, zu dem zusätzliche Daten geschrieben werden. |

