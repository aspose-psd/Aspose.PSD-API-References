---
title: "Clase TiffStreamWriter"
type: docs
weight: 20
url: /es/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Inicializa una nueva instancia de la clase [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| position | long | r/w | Obtiene o establece la posición del flujo. |
| sync_root | object | r | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [write(data)](#write_data_1) | Escribe los datos especificados. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Escribe los datos especificados. |
| [write_double(data)](#write_double_data_3) | Escribe un único valor double al flujo. |
| [write_double_array(data)](#write_double_array_data_4) | Escribe una matriz de valores double al flujo. |
| [write_float(data)](#write_float_data_5) | Escribe un único valor float al flujo. |
| [write_float_array(data)](#write_float_array_data_6) | Escribe una matriz de valores float al flujo. |
| [write_rational(data)](#write_rational_data_7) | Escribe un único valor de número racional al flujo. |
| [write_rational_array(data)](#write_rational_array_data_8) | Escribe una matriz de valores racionales sin signo al flujo. |
| [write_s_byte(data)](#write_s_byte_data_9) | Escribe un único valor de byte con signo en el flujo. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Escribe una matriz de valores de byte con signo en el flujo. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Escribe una matriz de valores enteros en el flujo. |
| [write_s_rational(data)](#write_s_rational_data_12) | Escribe un único valor de número racional con signo en el flujo. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Escribe una matriz de valores racionales con signo en el flujo. |
| [write_s_short(data)](#write_s_short_data_14) | Escribe un único valor short en el flujo. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Escribe una matriz de valores short en el flujo. |
| [write_slong(data)](#write_slong_data_16) | Escribe un único valor entero en el flujo. |
| [write_u_byte(data)](#write_u_byte_data_17) | Escribe un único valor de byte en el flujo. |
| [write_u_long(data)](#write_u_long_data_18) | Escribe un único valor entero sin signo en el flujo. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Escribe una matriz de valores enteros sin signo en el flujo. |
| [write_u_short(data)](#write_u_short_data_20) | Escribe un único valor short sin signo en el flujo. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Escribe una matriz de valores short sin signo en el flujo. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Inicializa una nueva instancia de la clase [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El escritor de flujo. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Escribe los datos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos a escribir. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Escribe los datos especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos a escribir. |
| offset | int | El desplazamiento de los datos. |
| data_length | int | Longitud de los datos a escribir. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Escribe un único valor double al flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | double | El valor a escribir. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Escribe una matriz de valores double al flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | double | La matriz a escribir. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Escribe un único valor float al flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | float | El valor a escribir. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Escribe una matriz de valores float al flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | float | La matriz a escribir. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Escribe un único valor de número racional al flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | El valor a escribir. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Escribe una matriz de valores racionales sin signo al flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | La matriz a escribir. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Escribe un único valor de byte con signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | sbyte | El valor a escribir. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Escribe una matriz de valores de byte con signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | sbyte | La matriz a escribir. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Escribe una matriz de valores enteros en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | int | La matriz a escribir. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Escribe un único valor de número racional con signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | El valor a escribir. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Escribe una matriz de valores racionales con signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | La matriz a escribir. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Escribe un único valor short en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | short | El valor a escribir. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Escribe una matriz de valores short en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | short | La matriz a escribir. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Escribe un único valor entero en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | int | El valor a escribir. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Escribe un único valor de byte en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | El valor a escribir. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Escribe un único valor entero sin signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | uint | El valor a escribir. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Escribe una matriz de valores enteros sin signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | uint | La matriz a escribir. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Escribe un único valor short sin signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | ushort | El valor a escribir. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Escribe una matriz de valores short sin signo en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | ushort | La matriz a escribir. |

