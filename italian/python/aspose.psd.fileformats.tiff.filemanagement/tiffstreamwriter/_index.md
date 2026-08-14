---
title: "Classe TiffStreamWriter"
type: docs
weight: 20
url: /it/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Inizializza una nuova istanza della classe [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| position | long | r/w | Ottiene o imposta la posizione del flusso. |
| sync_root | object | r | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla risorsa sincronizzata. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [write(data)](#write_data_1) | Scrive i dati specificati. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Scrive i dati specificati. |
| [write_double(data)](#write_double_data_3) | Scrive un singolo valore double nel flusso. |
| [write_double_array(data)](#write_double_array_data_4) | Scrive un array di valori double nel flusso. |
| [write_float(data)](#write_float_data_5) | Scrive un singolo valore float nel flusso. |
| [write_float_array(data)](#write_float_array_data_6) | Scrive un array di valori float nel flusso. |
| [write_rational(data)](#write_rational_data_7) | Scrive un singolo valore di numero razionale nel flusso. |
| [write_rational_array(data)](#write_rational_array_data_8) | Scrive un array di valori razionali senza segno nel flusso. |
| [write_s_byte(data)](#write_s_byte_data_9) | Scrive un singolo valore byte con segno nello stream. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Scrive un array di valori byte con segno nello stream. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Scrive un array di valori interi nello stream. |
| [write_s_rational(data)](#write_s_rational_data_12) | Scrive un singolo valore numero razionale con segno nello stream. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Scrive un array di valori razionali con segno nello stream. |
| [write_s_short(data)](#write_s_short_data_14) | Scrive un singolo valore short nello stream. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Scrive un array di valori short nello stream. |
| [write_slong(data)](#write_slong_data_16) | Scrive un singolo valore intero nello stream. |
| [write_u_byte(data)](#write_u_byte_data_17) | Scrive un singolo valore byte nello stream. |
| [write_u_long(data)](#write_u_long_data_18) | Scrive un singolo valore intero senza segno nello stream. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Scrive un array di valori interi senza segno nello stream. |
| [write_u_short(data)](#write_u_short_data_20) | Scrive un singolo valore short senza segno nello stream. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Scrive un array di valori short senza segno nello stream. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Inizializza una nuova istanza della classe [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il writer dello stream. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Scrive i dati specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati da scrivere. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Scrive i dati specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati da scrivere. |
| offset | int | L'offset dei dati. |
| data_length | int | Lunghezza dei dati da scrivere. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Scrive un singolo valore double nel flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | double | Il valore da scrivere. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Scrive un array di valori double nel flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | double | L'array da scrivere. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Scrive un singolo valore float nel flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | float | Il valore da scrivere. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Scrive un array di valori float nel flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | float | L'array da scrivere. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Scrive un singolo valore di numero razionale nel flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Il valore da scrivere. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Scrive un array di valori razionali senza segno nel flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | L'array da scrivere. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Scrive un singolo valore byte con segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | sbyte | Il valore da scrivere. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Scrive un array di valori byte con segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | sbyte | L'array da scrivere. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Scrive un array di valori interi nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | int | L'array da scrivere. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Scrive un singolo valore numero razionale con segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Il valore da scrivere. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Scrive un array di valori razionali con segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | L'array da scrivere. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Scrive un singolo valore short nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | short | Il valore da scrivere. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Scrive un array di valori short nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | short | L'array da scrivere. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Scrive un singolo valore intero nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | int | Il valore da scrivere. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Scrive un singolo valore byte nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | Il valore da scrivere. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Scrive un singolo valore intero senza segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | uint | Il valore da scrivere. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Scrive un array di valori interi senza segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | uint | L'array da scrivere. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Scrive un singolo valore short senza segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | ushort | Il valore da scrivere. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Scrive un array di valori short senza segno nello stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | ushort | L'array da scrivere. |

