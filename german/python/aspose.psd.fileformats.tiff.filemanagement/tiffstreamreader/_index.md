---
title: "TiffStreamReader Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Länge | long | r | Ruft die Länge des Lesers ab. |
| throw_exceptions | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob Ausnahmen bei falscher Datenverarbeitung (Lesen oder Schreiben in den Stream) ausgelöst werden. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Liest ein Array von Byte-Werten aus dem Stream. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream. |
| [read_double(position)](#read_double_position_3) | Liest einen einzelnen Double-Wert aus dem Stream. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Liest ein Array von Double-Werten aus dem Stream. |
| [read_float(position)](#read_float_position_5) | Liest einen einzelnen Float-Wert aus dem Stream. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Liest ein Array von Float-Werten aus dem Stream. |
| [read_rational(position)](#read_rational_position_7) | Liest einen einzelnen rationalen Zahlenwert aus dem Stream. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Liest ein Array von rationalen Zahlenwerten aus dem Stream. |
| [read_s_byte(position)](#read_s_byte_position_9) | Liest vorzeichenbehaftete Byte-Daten aus dem Stream. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Liest ein Array von vorzeichenbehafteten Byte-Werten aus dem Stream. |
| [read_s_long(position)](#read_s_long_position_11) | Liest einen vorzeichenbehafteten Ganzzahlwert aus dem Stream. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Liest ein Array von vorzeichenbehafteten Ganzzahlwerten aus dem Stream. |
| [read_s_rational(position)](#read_s_rational_position_13) | Liest einen einzelnen vorzeichenbehafteten rationalen Zahlenwert aus dem Stream. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Liest ein Array von vorzeichenbehafteten rationalen Zahlenwerten aus dem Stream. |
| [read_s_short(position)](#read_s_short_position_15) | Liest einen vorzeichenbehafteten Short-Wert aus dem Stream. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Liest ein Array von vorzeichenbehafteten Short-Werten aus dem Stream. |
| [read_u_long(position)](#read_u_long_position_17) | Liest einen vorzeichenlosen Ganzzahlwert aus dem Stream. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream. |
| [read_u_short(position)](#read_u_short_position_19) | Liest einen vorzeichenlosen Short-Wert aus dem Stream. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Konvertiert die zugrunde liegenden Daten in den Stream-Container. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Byte-Array-Daten. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Byte-Array-Daten. |
| start_index | int | Der Startindex in <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Byte-Array-Daten. |
| start_index | int | Der Startindex in <paramref name="data" />. |
| data_length | int | Länge der Daten. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Initialisiert eine neue Instanz der [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Liest ein Array von Byte-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Array | byte | Das Array zum Füllen. |
| array_index | int | Der Array-Index, ab dem Werte eingefügt werden sollen. |
| Position | long | Die Stream-Position, von der gelesen werden soll. |
| Anzahl | long | Die Anzahl der zu lesenden Elemente. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long | Das Array von Byte-Werten. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Liest ein Array von vorzeichenlosen Byte-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Das Array von vorzeichenlosen Byte-Werten. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Liest einen einzelnen Double-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Der einzelne Double-Wert. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Liest ein Array von Double-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Das Array von Double-Werten. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Liest einen einzelnen Float-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Der einzelne Float-Wert. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Liest ein Array von Float-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float | Das Array von Float-Werten. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Liest einen einzelnen rationalen Zahlenwert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Die rationale Zahl. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Liest ein Array von rationalen Zahlenwerten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Das Array von rationalen Werten. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Liest vorzeichenbehaftete Byte-Daten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| sbyte | Der vorzeichenbehaftete Byte-Wert. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten Byte-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| sbyte | Das Array von vorzeichenbehafteten Byte-Werten. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Liest einen vorzeichenbehafteten Ganzzahlwert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein vorzeichenbehafteter Integer-Wert. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten Ganzzahlwerten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das Array von vorzeichenbehafteten Integer-Werten. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Liest einen einzelnen vorzeichenbehafteten rationalen Zahlenwert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Die vorzeichenbehaftete rationale Zahl. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten rationalen Zahlenwerten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Das Array von vorzeichenbehafteten rationalen Werten. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Liest einen vorzeichenbehafteten Short-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| short | Ein vorzeichenbehafteter Short-Wert. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Liest ein Array von vorzeichenbehafteten Short-Werten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| short | Das Array vorzeichenbehafteter Short-Werte. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Liest einen vorzeichenlosen Ganzzahlwert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| uint | Ein vorzeichenloser Ganzzahlwert. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| uint | Das Array vorzeichenloser Ganzzahlwerte. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Liest einen vorzeichenlosen Short-Wert aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| ushort | Ein vorzeichenloser Short-Wert. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Liest ein Array von vorzeichenlosen Ganzzahlwerten aus dem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, von der gelesen wird. |
| Anzahl | long | Die Elementanzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| ushort | Das Array vorzeichenloser Ganzzahlwerte. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Konvertiert die zugrunde liegenden Daten in den Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_position | long | Die Startposition, von der die Konvertierung beginnen soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) mit konvertierten Daten. |


