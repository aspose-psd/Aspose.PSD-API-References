---
title: "TiffStreamReader‑klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| längd | long | r | Hämtar läsarens längd. |
| throw_exceptions | bool | r/w | Hämtar eller anger ett värde som indikerar om undantag kastas vid felaktig dataprocessering (läsa eller skriva till strömmen). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Läser en matris av byte‑värden från strömmen. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Läser en matris av osignerade byte‑värden från strömmen. |
| [read_double(position)](#read_double_position_3) | Läs ett enskilt double‑värde från strömmen. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Läser en matris av double‑värden från strömmen. |
| [read_float(position)](#read_float_position_5) | Läs ett enskilt float‑värde från strömmen. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Läser en matris av float‑värden från strömmen. |
| [read_rational(position)](#read_rational_position_7) | Läs ett enskilt rationellt talvärde från strömmen. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Läser en matris av rationella värden från strömmen. |
| [read_s_byte(position)](#read_s_byte_position_9) | Läser signerad byte‑data från strömmen. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Läser en matris av signerade byte‑värden från strömmen. |
| [read_s_long(position)](#read_s_long_position_11) | Läs signerad heltalsvärde från strömmen. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Läser en matris av signerade heltalsvärden från strömmen. |
| [read_s_rational(position)](#read_s_rational_position_13) | Läs ett enda signerat rationellt talvärde från strömmen. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Läser en array av signerade rationella värden från strömmen. |
| [read_s_short(position)](#read_s_short_position_15) | Läs ett signerat short‑värde från strömmen. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Läser en array av signerade short‑värden från strömmen. |
| [read_u_long(position)](#read_u_long_position_17) | Läs ett osignerat heltalvärde från strömmen. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Läser en array av osignerade heltalsvärden från strömmen. |
| [read_u_short(position)](#read_u_short_position_19) | Läs ett osignerat short‑värde från strömmen. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Läser en array av osignerade heltalsvärden från strömmen. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Konverterar den underliggande datan till strömbehållaren. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Byte‑array‑data. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Byte‑array‑data. |
| start_index | int | Startindexen i <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Byte‑array‑data. |
| start_index | int | Startindexen i <paramref name="data" />. |
| data_length | int | Längden på datan. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Initierar en ny instans av klassen [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Läser en matris av byte‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| array | byte | Arrayen att fylla. |
| array_index | int | Array‑indexet att börja lägga in värden i. |
| position | long | Strömmens position att läsa från. |
| count | long | Antalet element att läsa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | Arrayen av byte‑värden. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Läser en matris av osignerade byte‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Arrayen av osignerade byte‑värden. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Läs ett enskilt double‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Det enkla double‑värdet. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Läser en matris av double‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Arrayen av double‑värden. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Läs ett enskilt float‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Det enkla float‑värdet. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Läser en matris av float‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Arrayen av float‑värden. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Läs ett enskilt rationellt talvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Det rationella talet. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Läser en matris av rationella värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Arrayen med rationella värden. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Läser signerad byte‑data från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| sbyte | Det signerade bytevärdet. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Läser en matris av signerade byte‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| sbyte | Arrayen med signerade bytevärden. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Läs signerad heltalsvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett signerat heltalsvärde. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Läser en matris av signerade heltalsvärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Arrayen med signerade heltalsvärden. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Läs ett enda signerat rationellt talvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Det signerade rationella talet. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Läser en array av signerade rationella värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Arrayen med signerade rationella värden. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Läs ett signerat short‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| short | Ett signerat kortvärde. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Läser en array av signerade short‑värden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| short | Arrayen med signerade kortvärden. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Läs ett osignerat heltalvärde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| uint | Ett osignerat heltalsvärde. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Läser en array av osignerade heltalsvärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| uint | Arrayen med osignerade heltalsvärden. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Läs ett osignerat short‑värde från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| ushort | Ett osignerat kortvärde. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Läser en array av osignerade heltalsvärden från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| position | long | Positionen att läsa från. |
| count | long | Antalet element. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| ushort | Arrayen med osignerade heltalsvärden. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Konverterar den underliggande datan till strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_position | long | Startpositionen att börja konverteringen från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Den [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) med konverterad data. |


