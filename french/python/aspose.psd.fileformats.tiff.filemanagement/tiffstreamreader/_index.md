---
title: "Classe TiffStreamReader"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| longueur | long | r | Obtient la longueur du lecteur. |
| throw_exceptions | bool | r/w | Obtient ou définit une valeur indiquant si des exceptions sont levées lors d'un traitement de données incorrect (lecture ou écriture du flux). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Lit un tableau de valeurs d'octet depuis le flux. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Lit un tableau de valeurs d'octet non signé depuis le flux. |
| [read_double(position)](#read_double_position_3) | Lit une seule valeur double depuis le flux. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Lit un tableau de valeurs double depuis le flux. |
| [read_float(position)](#read_float_position_5) | Lit une seule valeur flottante depuis le flux. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Lit un tableau de valeurs flottantes depuis le flux. |
| [read_rational(position)](#read_rational_position_7) | Lit une seule valeur de nombre rationnel depuis le flux. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Lit un tableau de valeurs rationnelles depuis le flux. |
| [read_s_byte(position)](#read_s_byte_position_9) | Lit des données d'octet signé depuis le flux. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Lit un tableau de valeurs d'octet signé depuis le flux. |
| [read_s_long(position)](#read_s_long_position_11) | Lit une valeur d'entier signé depuis le flux. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Lit un tableau de valeurs d'entier signé depuis le flux. |
| [read_s_rational(position)](#read_s_rational_position_13) | Lit une seule valeur de nombre rationnel signé depuis le flux. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Lit un tableau de valeurs rationnelles signées depuis le flux. |
| [read_s_short(position)](#read_s_short_position_15) | Lit une valeur short signé depuis le flux. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Lit un tableau de valeurs short signées depuis le flux. |
| [read_u_long(position)](#read_u_long_position_17) | Lit une valeur d'entier non signé depuis le flux. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Lit un tableau de valeurs d'entier non signé depuis le flux. |
| [read_u_short(position)](#read_u_short_position_19) | Lit une valeur short non signé depuis le flux. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Lit un tableau de valeurs d'entier non signé depuis le flux. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Convertit les données sous-jacentes en conteneur de flux. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données du tableau d'octets. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données du tableau d'octets. |
| start_index | int | L'index de départ dans <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données du tableau d'octets. |
| start_index | int | L'index de départ dans <paramref name="data" />. |
| data_length | int | Longueur des données. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Initialise une nouvelle instance de la classe [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Lit un tableau de valeurs d'octet depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tableau | byte | Le tableau à remplir. |
| array_index | int | L'index du tableau où commencer à placer les valeurs. |
| position | long | La position du flux à lire. |
| count | long | Le nombre d'éléments à lire. |

**Returns**

| Type | Description |
| :- | :- |
| long | Le tableau de valeurs d'octets. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Lit un tableau de valeurs d'octet non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Le tableau de valeurs d'octets non signés. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Lit une seule valeur double depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| double | La valeur double unique. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Lit un tableau de valeurs double depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| double | Le tableau de valeurs doubles. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Lit une seule valeur flottante depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| float | La valeur flottante unique. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Lit un tableau de valeurs flottantes depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| float | Le tableau de valeurs flottantes. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Lit une seule valeur de nombre rationnel depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Le nombre rationnel. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Lit un tableau de valeurs rationnelles depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Le tableau de valeurs rationnelles. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Lit des données d'octet signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| sbyte | La valeur d'octet signé. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Lit un tableau de valeurs d'octet signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| sbyte | Le tableau de valeurs d'octets signés. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Lit une valeur d'entier signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| int | Une valeur d'entier signé. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Lit un tableau de valeurs d'entier signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le tableau de valeurs d'entiers signés. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Lit une seule valeur de nombre rationnel signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Le nombre rationnel signé. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Lit un tableau de valeurs rationnelles signées depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Le tableau de valeurs rationnelles signées. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Lit une valeur short signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| short | Une valeur short signée. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Lit un tableau de valeurs short signées depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| short | Le tableau de valeurs short signées. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Lit une valeur d'entier non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| uint | Une valeur d'entier non signé. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Lit un tableau de valeurs d'entier non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| uint | Le tableau de valeurs d'entiers non signés. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Lit une valeur short non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |

**Returns**

| Type | Description |
| :- | :- |
| ushort | Une valeur short non signée. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Lit un tableau de valeurs d'entier non signé depuis le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à lire. |
| count | long | Le nombre d'éléments. |

**Returns**

| Type | Description |
| :- | :- |
| ushort | Le tableau de valeurs d'entiers non signés. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Convertit les données sous-jacentes en conteneur de flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_position | long | La position de départ pour commencer la conversion. |

**Returns**

| Type | Description |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) avec les données converties. |


