---
title: "TiffStreamWriter Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Initialisiert eine neue Instanz der [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Position | long | r/w | Liest oder setzt die Streamposition. |
| sync_root | object | r | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [write(data)](#write_data_1) | Schreibt die angegebenen Daten. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Schreibt die angegebenen Daten. |
| [write_double(data)](#write_double_data_3) | Schreibt einen einzelnen double-Wert in den Stream. |
| [write_double_array(data)](#write_double_array_data_4) | Schreibt ein Array von double-Werten in den Stream. |
| [write_float(data)](#write_float_data_5) | Schreibt einen einzelnen float-Wert in den Stream. |
| [write_float_array(data)](#write_float_array_data_6) | Schreibt ein Array von float-Werten in den Stream. |
| [write_rational(data)](#write_rational_data_7) | Schreibt einen einzelnen rationalen Zahlenwert in den Stream. |
| [write_rational_array(data)](#write_rational_array_data_8) | Schreibt ein Array von unsigned rational-Werten in den Stream. |
| [write_s_byte(data)](#write_s_byte_data_9) | Schreibt einen einzelnen signed byte-Wert in den Stream. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Schreibt ein Array von signed byte-Werten in den Stream. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Schreibt ein Array von integer-Werten in den Stream. |
| [write_s_rational(data)](#write_s_rational_data_12) | Schreibt einen einzelnen signed rational Zahlenwert in den Stream. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Schreibt ein Array von signed rational-Werten in den Stream. |
| [write_s_short(data)](#write_s_short_data_14) | Schreibt einen einzelnen short-Wert in den Stream. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Schreibt ein Array von short-Werten in den Stream. |
| [write_slong(data)](#write_slong_data_16) | Schreibt einen einzelnen integer-Wert in den Stream. |
| [write_u_byte(data)](#write_u_byte_data_17) | Schreibt einen einzelnen byte-Wert in den Stream. |
| [write_u_long(data)](#write_u_long_data_18) | Schreibt einen einzelnen unsigned integer-Wert in den Stream. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Schreibt ein Array von unsigned integer-Werten in den Stream. |
| [write_u_short(data)](#write_u_short_data_20) | Schreibt einen einzelnen unsigned short-Wert in den Stream. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Schreibt ein Array von unsigned short-Werten in den Stream. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Initialisiert eine neue Instanz der [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Schreiber. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die zu schreibenden Daten. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Schreibt die angegebenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die zu schreibenden Daten. |
| offset | int | Der Datenoffset. |
| data_length | int | Länge der Daten zum Schreiben. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Schreibt einen einzelnen double-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | double | Der zu schreibende Wert. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Schreibt ein Array von double-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | double | Das zu schreibende Array. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Schreibt einen einzelnen float-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | float | Der zu schreibende Wert. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Schreibt ein Array von float-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | float | Das zu schreibende Array. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Schreibt einen einzelnen rationalen Zahlenwert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Der zu schreibende Wert. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Schreibt ein Array von unsigned rational-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Das zu schreibende Array. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Schreibt einen einzelnen signed byte-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | sbyte | Der zu schreibende Wert. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Schreibt ein Array von signed byte-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | sbyte | Das zu schreibende Array. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Schreibt ein Array von integer-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | int | Das zu schreibende Array. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Schreibt einen einzelnen signed rational Zahlenwert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Der zu schreibende Wert. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Schreibt ein Array von signed rational-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Das zu schreibende Array. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Schreibt einen einzelnen short-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | short | Der zu schreibende Wert. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Schreibt ein Array von short-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | short | Das zu schreibende Array. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Schreibt einen einzelnen integer-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | int | Der zu schreibende Wert. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Schreibt einen einzelnen byte-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Der zu schreibende Wert. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Schreibt einen einzelnen unsigned integer-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | uint | Der zu schreibende Wert. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Schreibt ein Array von unsigned integer-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | uint | Das zu schreibende Array. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Schreibt einen einzelnen unsigned short-Wert in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | ushort | Der zu schreibende Wert. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Schreibt ein Array von unsigned short-Werten in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | ushort | Das zu schreibende Array. |

