---
title: "TiffStreamWriter Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Initialiseert een nieuw exemplaar van de [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| position | long | r/w | Haalt op of stelt de streampositie in. |
| sync_root | object | r | Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [write(data)](#write_data_1) | Schrijft de opgegeven gegevens. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Schrijft de opgegeven gegevens. |
| [write_double(data)](#write_double_data_3) | Schrijft een enkele double-waarde naar de stream. |
| [write_double_array(data)](#write_double_array_data_4) | Schrijft een array van double-waarden naar de stream. |
| [write_float(data)](#write_float_data_5) | Schrijft een enkele float-waarde naar de stream. |
| [write_float_array(data)](#write_float_array_data_6) | Schrijft een array van float-waarden naar de stream. |
| [write_rational(data)](#write_rational_data_7) | Schrijft een enkele rationale getalwaarde naar de stream. |
| [write_rational_array(data)](#write_rational_array_data_8) | Schrijft een array van niet-ondertekende rationale waarden naar de stream. |
| [write_s_byte(data)](#write_s_byte_data_9) | Schrijft een enkele ondertekende byte-waarde naar de stream. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Schrijft een array van ondertekende byte-waarden naar de stream. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Schrijft een array van integer-waarden naar de stream. |
| [write_s_rational(data)](#write_s_rational_data_12) | Schrijft een enkele ondertekende rationale getalwaarde naar de stream. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Schrijft een array van ondertekende rationale waarden naar de stream. |
| [write_s_short(data)](#write_s_short_data_14) | Schrijft een enkele short-waarde naar de stream. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Schrijft een array van short-waarden naar de stream. |
| [write_slong(data)](#write_slong_data_16) | Schrijft een enkele integer-waarde naar de stream. |
| [write_u_byte(data)](#write_u_byte_data_17) | Schrijft een enkele byte-waarde naar de stream. |
| [write_u_long(data)](#write_u_long_data_18) | Schrijft een enkele niet-ondertekende integer-waarde naar de stream. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Schrijft een array van niet-ondertekende integer-waarden naar de stream. |
| [write_u_short(data)](#write_u_short_data_20) | Schrijft een enkele niet-ondertekende short-waarde naar de stream. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Schrijft een array van niet-ondertekende short-waarden naar de stream. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Initialiseert een nieuw exemplaar van de [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamwriter. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Schrijft de opgegeven gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De gegevens om te schrijven. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Schrijft de opgegeven gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De gegevens om te schrijven. |
| offset | int | De gegevensoffset. |
| data_length | int | Lengte van de gegevens om te schrijven. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Schrijft een enkele double-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | double | De waarde om te schrijven. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Schrijft een array van double-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | double | De array om te schrijven. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Schrijft een enkele float-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | float | De waarde om te schrijven. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Schrijft een array van float-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | float | De array om te schrijven. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Schrijft een enkele rationale getalwaarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | De waarde om te schrijven. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Schrijft een array van niet-ondertekende rationale waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | De array om te schrijven. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Schrijft een enkele ondertekende byte-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | sbyte | De waarde om te schrijven. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Schrijft een array van ondertekende byte-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | sbyte | De array om te schrijven. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Schrijft een array van integer-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | int | De array om te schrijven. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Schrijft een enkele ondertekende rationale getalwaarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | De waarde om te schrijven. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Schrijft een array van ondertekende rationale waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | De array om te schrijven. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Schrijft een enkele short-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | short | De waarde om te schrijven. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Schrijft een array van short-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | short | De array om te schrijven. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Schrijft een enkele integer-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | int | De waarde om te schrijven. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Schrijft een enkele byte-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De waarde om te schrijven. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Schrijft een enkele niet-ondertekende integer-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | uint | De waarde om te schrijven. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Schrijft een array van niet-ondertekende integer-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | uint | De array om te schrijven. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Schrijft een enkele niet-ondertekende short-waarde naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | ushort | De waarde om te schrijven. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Schrijft een array van niet-ondertekende short-waarden naar de stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | ushort | De array om te schrijven. |

