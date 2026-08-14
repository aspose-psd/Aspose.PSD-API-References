---
title: "Classe TiffStreamReader"
type: docs
weight: 10
url: /it/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| lunghezza | long | r | Ottiene la lunghezza del lettore. |
| throw_exceptions | bool | r/w | Ottiene o imposta un valore che indica se le eccezioni vengono generate durante l'elaborazione errata dei dati (lettura o scrittura nello stream). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Legge un array di valori byte dal flusso. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Legge un array di valori byte senza segno dal flusso. |
| [read_double(position)](#read_double_position_3) | Legge un singolo valore double dal flusso. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Legge un array di valori double dal flusso. |
| [read_float(position)](#read_float_position_5) | Legge un singolo valore float dal flusso. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Legge un array di valori float dal flusso. |
| [read_rational(position)](#read_rational_position_7) | Legge un singolo valore di numero razionale dal flusso. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Legge un array di valori razionali dal flusso. |
| [read_s_byte(position)](#read_s_byte_position_9) | Legge dati byte con segno dal flusso. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Legge un array di valori byte con segno dal flusso. |
| [read_s_long(position)](#read_s_long_position_11) | Legge un valore intero con segno dal flusso. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Legge un array di valori interi con segno dal flusso. |
| [read_s_rational(position)](#read_s_rational_position_13) | Legge un singolo valore di numero razionale con segno dal flusso. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Legge un array di valori razionali con segno dal flusso. |
| [read_s_short(position)](#read_s_short_position_15) | Legge un valore short con segno dal flusso. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Legge un array di valori short con segno dal flusso. |
| [read_u_long(position)](#read_u_long_position_17) | Legge un valore intero senza segno dal flusso. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Legge un array di valori interi senza segno dal flusso. |
| [read_u_short(position)](#read_u_short_position_19) | Legge un valore short senza segno dal flusso. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Legge un array di valori interi senza segno dal flusso. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Converte i dati sottostanti nel contenitore del flusso. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati dell'array di byte. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati dell'array di byte. |
| start_index | int | L'indice di inizio in <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati dell'array di byte. |
| start_index | int | L'indice di inizio in <paramref name="data" />. |
| data_length | int | Lunghezza dei dati. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Inizializza una nuova istanza della classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Legge un array di valori byte dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| array | byte | L'array da riempire. |
| array_index | int | L'indice dell'array a cui iniziare a inserire i valori. |
| position | long | La posizione del flusso da cui leggere. |
| conteggio | long | Il conteggio degli elementi da leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| long | L'array di valori byte. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Legge un array di valori byte senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | L'array di valori byte senza segno. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Legge un singolo valore double dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Il singolo valore double. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Legge un array di valori double dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | L'array di valori double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Legge un singolo valore float dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | Il singolo valore float. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Legge un array di valori float dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | L'array di valori float. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Legge un singolo valore di numero razionale dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Il numero razionale. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Legge un array di valori razionali dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | L'array di valori razionali. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Legge dati byte con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| sbyte | Il valore byte con segno. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Legge un array di valori byte con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| sbyte | L'array di valori byte con segno. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Legge un valore intero con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un valore intero con segno. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Legge un array di valori interi con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'array di valori interi con segno. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Legge un singolo valore di numero razionale con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Il numero razionale con segno. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Legge un array di valori razionali con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | L'array di valori razionali con segno. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Legge un valore short con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| short | Un valore short con segno. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Legge un array di valori short con segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| short | L'array di valori short con segno. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Legge un valore intero senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| uint | Un valore intero senza segno. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Legge un array di valori interi senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| uint | L'array di valori interi senza segno. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Legge un valore short senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| ushort | Un valore short senza segno. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Legge un array di valori interi senza segno dal flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| position | long | La posizione da cui leggere. |
| conteggio | long | Il conteggio degli elementi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| ushort | L'array di valori interi senza segno. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Converte i dati sottostanti nel contenitore del flusso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_position | long | La posizione di inizio da cui avviare la conversione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) con i dati convertiti. |


