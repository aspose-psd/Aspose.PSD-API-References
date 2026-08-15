---
title: "TiffDataType-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata). |
| count | uint | r | Hämtar antalet element. |
| data_size | uint | r | Hämtar den extra datastorleken i byte (om de 12 byte inte räcker för att rymma taggdata). |
| id | ushort | r | Hämtar tagg‑id:s heltalsrepresentation. |
| is_valid | bool | r | Hämtar ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Hämtar tagg‑id. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Hämtar taggtypen. |
| värde | object | r/w | Hämtar eller anger värdet som denna datatyp innehåller. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet. |
| [deep_clone()](#deep_clone__2) | Utför en djupkloning av denna instans. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Läser taggdata. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Skriver den extra taggdata. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Skriver taggdata. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller ligger på samma position i sorteringsordningen som det andra objektet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| obj | object | Ett objekt att jämföra med denna instans. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | En 32‑bit signerad heltal som indikerar den relativa ordningen för de objekt som jämförs. Returvärdet har följande betydelser:<br/>            Värde<br/>            Betydelse<br/>            Mindre än noll<br/>            Denna instans är mindre än <paramref name="obj" />.<br/>            Noll<br/>            Denna instans är lika med <paramref name="obj" />.<br/>            Större än noll<br/>            Denna instans är större än <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Utför en djupkloning av denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | En djupkloning av den aktuella instansen. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Läser taggdata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Datastreamen. |
| position | long | Taggpositionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Den lästa taggen. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Skriver den extra taggdata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Datastreamen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | De faktiska skrivna byten. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Skriver taggdata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Datastreamen. |
| additional_data_offset | long | Offseten att skriva ytterligare data till. |

