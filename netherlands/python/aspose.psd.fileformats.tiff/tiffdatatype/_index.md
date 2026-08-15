---
title: "TiffDataType Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Haalt de extra gegevensgrootte op in bytes (voor het geval de 12 bytes niet voldoende zijn om de taggegevens te bevatten). |
| count | uint | r | Haalt het aantal elementen op. |
| data_size | uint | r | Haalt de extra gegevensgrootte op in bytes (voor het geval de 12 bytes niet voldoende zijn om de taggegevens te bevatten). |
| id | ushort | r | Haalt de integerrepresentatie van de tag-id op. |
| is_valid | bool | r | Haalt een waarde op die aangeeft of taggegevens geldig zijn. Een geldige tag bevat gegevens die bewaard kunnen worden. Een ongeldige tag kan niet worden opgeslagen. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Haalt de tag-id op. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Haalt het tagtype op. |
| value | object | r/w | Haalt op of stelt de waarde in die dit gegevenstype bevat. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Vergelijkt het huidige exemplaar met een ander object van hetzelfde type en retourneert een integer die aangeeft of het huidige exemplaar voorafgaat, volgt of zich op dezelfde positie in de sorteervolgorde bevindt als het andere object. |
| [deep_clone()](#deep_clone__2) | Voert een diepe kloon uit van dit exemplaar. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Leest de taggegevens. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Schrijft de extra taggegevens. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Schrijft de taggegevens. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Vergelijkt het huidige exemplaar met een ander object van hetzelfde type en retourneert een integer die aangeeft of het huidige exemplaar voorafgaat, volgt of zich op dezelfde positie in de sorteervolgorde bevindt als het andere object.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| obj | object | Een object om te vergelijken met deze instantie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Een 32-bits ondertekend geheel getal dat de relatieve volgorde van de te vergelijken objecten aangeeft. De geretourneerde waarde heeft deze betekenissen:<br/>            Waarde<br/>            Betekenis<br/>            Minder dan nul<br/>            Deze instantie is kleiner dan <paramref name="obj" />.<br/>            Nul<br/>            Deze instantie is gelijk aan <paramref name="obj" />.<br/>            Groter dan nul<br/>            Deze instantie is groter dan <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Voert een diepe kloon uit van dit exemplaar.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Een diepe kloon van de huidige instantie. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Leest de taggegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | De gegevensstroom. |
| position | long | De tagpositie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | De gelezen tag. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Schrijft de extra taggegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | De gegevensstroom. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | De daadwerkelijk geschreven bytes. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Schrijft de taggegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | De gegevensstroom. |
| additional_data_offset | long | De offset om extra gegevens naar te schrijven. |

