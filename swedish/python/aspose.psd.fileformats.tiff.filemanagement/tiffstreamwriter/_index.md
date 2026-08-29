---
title: "TiffStreamWriter klass"
type: docs
weight: 20
url: /sv/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Initierar en ny instans av [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| position | long | r/w | Hämtar eller anger strömmens position. |
| sync_root | object | r | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [write(data)](#write_data_1) | Skriver den angivna datan. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Skriver den angivna datan. |
| [write_double(data)](#write_double_data_3) | Skriver ett enda double‑värde till strömmen. |
| [write_double_array(data)](#write_double_array_data_4) | Skriver en array av double‑värden till strömmen. |
| [write_float(data)](#write_float_data_5) | Skriver ett enda float‑värde till strömmen. |
| [write_float_array(data)](#write_float_array_data_6) | Skriver en array av float‑värden till strömmen. |
| [write_rational(data)](#write_rational_data_7) | Skriver ett enda rationellt talvärde till strömmen. |
| [write_rational_array(data)](#write_rational_array_data_8) | Skriver en array av osignerade rationella värden till strömmen. |
| [write_s_byte(data)](#write_s_byte_data_9) | Skriver ett enda signed byte‑värde till strömmen. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Skriver en array av signed byte‑värden till strömmen. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Skriver en array av heltalsvärden till strömmen. |
| [write_s_rational(data)](#write_s_rational_data_12) | Skriver ett enda signed rationellt talvärde till strömmen. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Skriver en array av signed rationella värden till strömmen. |
| [write_s_short(data)](#write_s_short_data_14) | Skriver ett enda short‑värde till strömmen. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Skriver en array av short‑värden till strömmen. |
| [write_slong(data)](#write_slong_data_16) | Skriver ett enda heltalsvärde till strömmen. |
| [write_u_byte(data)](#write_u_byte_data_17) | Skriver ett enda byte‑värde till strömmen. |
| [write_u_long(data)](#write_u_long_data_18) | Skriver ett enda osignerat heltalsvärde till strömmen. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Skriver en array av osignerade heltalsvärden till strömmen. |
| [write_u_short(data)](#write_u_short_data_20) | Skriver ett enda osignerat short‑värde till strömmen. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Skriver en matris av osignerade short‑värden till strömmen. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Initierar en ny instans av [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömmen‑skrivaren. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Skriver den angivna datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Data att skriva. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Skriver den angivna datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Data att skriva. |
| offset | int | Dataoffset. |
| data_length | int | Längd på data att skriva. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Skriver ett enda double‑värde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | double | Värdet att skriva. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Skriver en array av double‑värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | double | Matris att skriva. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Skriver ett enda float‑värde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | float | Värdet att skriva. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Skriver en array av float‑värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | float | Matris att skriva. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Skriver ett enda rationellt talvärde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Värdet att skriva. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Skriver en array av osignerade rationella värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Matris att skriva. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Skriver ett enda signed byte‑värde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | sbyte | Värdet att skriva. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Skriver en array av signed byte‑värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | sbyte | Matris att skriva. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Skriver en array av heltalsvärden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | int | Matris att skriva. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Skriver ett enda signed rationellt talvärde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Värdet att skriva. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Skriver en array av signed rationella värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Matris att skriva. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Skriver ett enda short‑värde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | short | Värdet att skriva. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Skriver en array av short‑värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | short | Matris att skriva. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Skriver ett enda heltalsvärde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | int | Värdet att skriva. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Skriver ett enda byte‑värde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Värdet att skriva. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Skriver ett enda osignerat heltalsvärde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | uint | Värdet att skriva. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Skriver en array av osignerade heltalsvärden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | uint | Matris att skriva. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Skriver ett enda osignerat short‑värde till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | ushort | Värdet att skriva. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Skriver en matris av osignerade short‑värden till strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | ushort | Matris att skriva. |

