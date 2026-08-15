---
title: "Clase TiffStreamReader"
type: docs
weight: 10
url: /es/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| longitud | long | r | Obtiene la longitud del lector. |
| throw_exceptions | bool | r/w | Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Lee una matriz de valores byte del flujo. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Lee una matriz de valores byte sin signo del flujo. |
| [read_double(position)](#read_double_position_3) | Lee un único valor double del flujo. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Lee una matriz de valores double del flujo. |
| [read_float(position)](#read_float_position_5) | Lee un único valor float del flujo. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Lee una matriz de valores float del flujo. |
| [read_rational(position)](#read_rational_position_7) | Lee un único valor de número racional del flujo. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Lee una matriz de valores racionales del flujo. |
| [read_s_byte(position)](#read_s_byte_position_9) | Lee datos de byte con signo del flujo. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Lee una matriz de valores de byte con signo del flujo. |
| [read_s_long(position)](#read_s_long_position_11) | Lee un valor entero con signo del flujo. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Lee una matriz de valores enteros con signo del flujo. |
| [read_s_rational(position)](#read_s_rational_position_13) | Lee un único valor de número racional con signo del flujo. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Lee una matriz de valores racionales con signo del flujo. |
| [read_s_short(position)](#read_s_short_position_15) | Lee un valor short con signo del flujo. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Lee una matriz de valores short con signo del flujo. |
| [read_u_long(position)](#read_u_long_position_17) | Lee un valor entero sin signo del flujo. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Lee una matriz de valores enteros sin signo del flujo. |
| [read_u_short(position)](#read_u_short_position_19) | Lee un valor short sin signo del flujo. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Lee una matriz de valores enteros sin signo del flujo. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Convierte los datos subyacentes al contenedor de flujo. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos de la matriz de bytes. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos de la matriz de bytes. |
| start_index | int | El índice inicial en <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos de la matriz de bytes. |
| start_index | int | El índice inicial en <paramref name="data" />. |
| data_length | int | Longitud de los datos. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Inicializa una nueva instancia de la clase [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Lee una matriz de valores byte del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matriz | byte | La matriz a rellenar. |
| array_index | int | El índice del arreglo donde comenzar a colocar valores. |
| position | long | La posición del flujo desde donde leer. |
| count | long | El recuento de elementos a leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | El arreglo de valores byte. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Lee una matriz de valores byte sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | El arreglo de valores byte sin signo. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Lee un único valor double del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | El valor doble único. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Lee una matriz de valores double del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | El arreglo de valores dobles. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Lee un único valor float del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El valor flotante único. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Lee una matriz de valores float del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El arreglo de valores flotantes. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Lee un único valor de número racional del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | El número racional. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Lee una matriz de valores racionales del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | El arreglo de valores racionales. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Lee datos de byte con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| sbyte | El valor byte con signo. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Lee una matriz de valores de byte con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| sbyte | El arreglo de valores byte con signo. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Lee un valor entero con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un valor entero con signo. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Lee una matriz de valores enteros con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El arreglo de valores enteros con signo. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Lee un único valor de número racional con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | El número racional con signo. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Lee una matriz de valores racionales con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | El arreglo de valores racionales con signo. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Lee un valor short con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| short | Un valor corto con signo. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Lee una matriz de valores short con signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| short | El arreglo de valores cortos con signo. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Lee un valor entero sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| uint | Un valor entero sin signo. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| uint | El arreglo de valores enteros sin signo. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Lee un valor short sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| ushort | Un valor corto sin signo. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde donde leer. |
| count | long | El recuento de elementos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| ushort | El arreglo de valores enteros sin signo. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Convierte los datos subyacentes al contenedor de flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_position | long | La posición inicial desde la cual iniciar la conversión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) con datos convertidos. |


