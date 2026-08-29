---
title: "Classe TiffStreamWriter"
type: docs
weight: 20
url: /fr/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Initialise une nouvelle instance de la classe [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| position | long | r/w | Obtient ou définit la position du flux. |
| sync_root | object | r | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la ressource synchronisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [write(data)](#write_data_1) | Écrit les données spécifiées. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Écrit les données spécifiées. |
| [write_double(data)](#write_double_data_3) | Écrit une seule valeur double dans le flux. |
| [write_double_array(data)](#write_double_array_data_4) | Écrit un tableau de valeurs double dans le flux. |
| [write_float(data)](#write_float_data_5) | Écrit une seule valeur float dans le flux. |
| [write_float_array(data)](#write_float_array_data_6) | Écrit un tableau de valeurs float dans le flux. |
| [write_rational(data)](#write_rational_data_7) | Écrit une seule valeur de nombre rationnel dans le flux. |
| [write_rational_array(data)](#write_rational_array_data_8) | Écrit un tableau de valeurs rationnelles non signées dans le flux. |
| [write_s_byte(data)](#write_s_byte_data_9) | Écrit une seule valeur d'octet signé dans le flux. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Écrit un tableau de valeurs d'octets signés dans le flux. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Écrit un tableau de valeurs entières dans le flux. |
| [write_s_rational(data)](#write_s_rational_data_12) | Écrit une seule valeur de nombre rationnel signé dans le flux. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Écrit un tableau de valeurs rationnelles signées dans le flux. |
| [write_s_short(data)](#write_s_short_data_14) | Écrit une seule valeur short dans le flux. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Écrit un tableau de valeurs short dans le flux. |
| [write_slong(data)](#write_slong_data_16) | Écrit une seule valeur entière dans le flux. |
| [write_u_byte(data)](#write_u_byte_data_17) | Écrit une seule valeur d'octet dans le flux. |
| [write_u_long(data)](#write_u_long_data_18) | Écrit une seule valeur d'entier non signé dans le flux. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Écrit un tableau de valeurs d'entiers non signés dans le flux. |
| [write_u_short(data)](#write_u_short_data_20) | Écrit une seule valeur short non signé dans le flux. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Écrit un tableau de valeurs short non signées dans le flux. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Initialise une nouvelle instance de la classe [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le rédacteur de flux. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Écrit les données spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données à écrire. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Écrit les données spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données à écrire. |
| offset | int | Le décalage des données. |
| data_length | int | Longueur des données à écrire. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Écrit une seule valeur double dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | double | La valeur à écrire. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Écrit un tableau de valeurs double dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | double | Le tableau à écrire. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Écrit une seule valeur float dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | float | La valeur à écrire. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Écrit un tableau de valeurs float dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | float | Le tableau à écrire. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Écrit une seule valeur de nombre rationnel dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | La valeur à écrire. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Écrit un tableau de valeurs rationnelles non signées dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Le tableau à écrire. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Écrit une seule valeur d'octet signé dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | sbyte | La valeur à écrire. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Écrit un tableau de valeurs d'octets signés dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | sbyte | Le tableau à écrire. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Écrit un tableau de valeurs entières dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | int | Le tableau à écrire. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Écrit une seule valeur de nombre rationnel signé dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | La valeur à écrire. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Écrit un tableau de valeurs rationnelles signées dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Le tableau à écrire. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Écrit une seule valeur short dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | short | La valeur à écrire. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Écrit un tableau de valeurs short dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | short | Le tableau à écrire. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Écrit une seule valeur entière dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | int | La valeur à écrire. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Écrit une seule valeur d'octet dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | La valeur à écrire. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Écrit une seule valeur d'entier non signé dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | uint | La valeur à écrire. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Écrit un tableau de valeurs d'entiers non signés dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | uint | Le tableau à écrire. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Écrit une seule valeur short non signé dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | ushort | La valeur à écrire. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Écrit un tableau de valeurs short non signées dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | ushort | Le tableau à écrire. |

