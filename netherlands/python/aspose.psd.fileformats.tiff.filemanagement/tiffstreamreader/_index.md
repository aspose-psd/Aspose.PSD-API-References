---
title: "TiffStreamReader Class"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse. |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse. |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse. |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| lengte | long | r | Haalt de lengte van de lezer op. |
| throw_exceptions | bool | r/w | Haalt op of stelt een waarde in die aangeeft of uitzonderingen worden gegooid bij onjuiste gegevensverwerking (lezen of schrijven naar de stream). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Leest een array van byte-waarden van de stream. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Leest een array van onondertekende byte-waarden van de stream. |
| [read_double(position)](#read_double_position_3) | Lees een enkele double-waarde van de stream. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Leest een array van double-waarden van de stream. |
| [read_float(position)](#read_float_position_5) | Lees een enkele float-waarde van de stream. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Leest een array van float-waarden van de stream. |
| [read_rational(position)](#read_rational_position_7) | Lees een enkele rationele getalwaarde van de stream. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Leest een array van rationele waarden van de stream. |
| [read_s_byte(position)](#read_s_byte_position_9) | Leest ondertekende byte-gegevens van de stream. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Leest een array van ondertekende byte-waarden van de stream. |
| [read_s_long(position)](#read_s_long_position_11) | Lees ondertekende integer-waarde van de stream. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Leest een array van ondertekende integer-waarden van de stream. |
| [read_s_rational(position)](#read_s_rational_position_13) | Lees een enkele ondertekende rationele getalwaarde van de stream. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Leest een array van ondertekende rationele waarden van de stream. |
| [read_s_short(position)](#read_s_short_position_15) | Lees ondertekende short-waarde van de stream. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Leest een array van ondertekende short-waarden van de stream. |
| [read_u_long(position)](#read_u_long_position_17) | Lees onondertekende integer-waarde van de stream. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Leest een array van onondertekende integer-waarden van de stream. |
| [read_u_short(position)](#read_u_short_position_19) | Lees onondertekende short-waarde van de stream. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Leest een array van onondertekende integer-waarden van de stream. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Converteert de onderliggende gegevens naar de streamcontainer. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De byte-arraygegevens. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De byte-arraygegevens. |
| start_index | int | De startindex in <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De byte-arraygegevens. |
| start_index | int | De startindex in <paramref name="data" />. |
| data_length | int | Lengte van de gegevens. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Initialiseert een nieuw exemplaar van de [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Leest een array van byte-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| array | byte | De array om te vullen. |
| array_index | int | De array-index om waarden te beginnen plaatsen. |
| position | long | De streampositie om van te lezen. |
| count | long | Het aantal elementen om te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | De array van byte-waarden. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Leest een array van onondertekende byte-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De array van ongetekende byte-waarden. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Lees een enkele double-waarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | De enkele double-waarde. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Leest een array van double-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | De array van double-waarden. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Lees een enkele float-waarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| float | De enkele float-waarde. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Leest een array van float-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| float | De array van float-waarden. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Lees een enkele rationele getalwaarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Het rationale getal. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Leest een array van rationele waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | De array van rationale waarden. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Leest ondertekende byte-gegevens van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| sbyte | De ondertekende byte-waarde. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Leest een array van ondertekende byte-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| sbyte | De array van ondertekende byte-waarden. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Lees ondertekende integer-waarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Een ondertekende integer-waarde. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Leest een array van ondertekende integer-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De array van ondertekende integer-waarden. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Lees een enkele ondertekende rationele getalwaarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Het ondertekende rationale getal. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Leest een array van ondertekende rationele waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | De array van ondertekende rationale waarden. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Lees ondertekende short-waarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| short | Een ondertekende short-waarde. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Leest een array van ondertekende short-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| short | De array van ondertekende short-waarden. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Lees onondertekende integer-waarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| uint | Een ongetekende integer-waarde. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Leest een array van onondertekende integer-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| uint | De array van ongetekende integer-waarden. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Lees onondertekende short-waarde van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| ushort | Een ongetekende short-waarde. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Leest een array van onondertekende integer-waarden van de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| position | long | De positie om van te lezen. |
| count | long | Het aantal elementen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| ushort | De array van ongetekende integer-waarden. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Converteert de onderliggende gegevens naar de streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| start_position | long | De startpositie om de conversie vanaf te starten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) met geconverteerde gegevens. |


