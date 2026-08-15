---
title: "Clase SplitStreamContainer"
type: docs
weight: 4220
url: /es/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Inicializa una nueva instancia de la clase [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Inicializa una nueva instancia de la clase [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Inicializa una nueva instancia de la clase [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [estático] | int | r | Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente. |
| can_read | bool | r | Obtiene un valor que indica si la secuencia admite lectura. |
| can_seek | bool | r | Obtiene un valor que indica si la secuencia admite búsqueda. |
| can_write | bool | r | Obtiene un valor que indica si la secuencia admite escritura. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| is_stream_disposed_on_close | bool | r | Obtiene un valor que indica si esta secuencia se libera al cerrarse. |
| longitud | long | r/w | Obtiene o establece la longitud de la secuencia en bytes. Este valor es menor que el  por la posición inicial de la secuencia pasada en el constructor de StreamContainer. |
| position | long | r/w | Obtiene o establece la posición actual dentro de la secuencia. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor de StreamContainer. |
| flujo | _io.BufferedRandom | r | Obtiene la secuencia de datos. |
| sync_root | object | r | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| flush() | Borra todos los búferes de esta secuencia y hace que cualquier dato almacenado se escriba en el dispositivo subyacente. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | Inserta el contenedor de secuencia en la posición especificada. |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia en la cantidad de bytes leídos. |
| [read(bytes)](#read_bytes_3) | Lee bytes para llenar el búfer de bytes especificado. |
| [read_byte()](#read_byte__4) | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| [save(destination_stream)](#save_destination_stream_5) | Guarda (copia) los datos de la secuencia al flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) y el valor de la secuencia [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | Guarda (copia) todos los datos de la secuencia al flujo especificado. Utiliza el valor de la secuencia [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(file_path)](#save_file_path_8) | Guarda (copia) los datos de la secuencia al flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) y el valor de la secuencia [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [seek(offset, origin)](#seek_offset_origin_11) | Establece la posición dentro del flujo actual. |
| seek_begin() | Establece la posición del flujo al comienzo del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| [to_bytes()](#to_bytes__12) | Convierte los datos del flujo a una matriz de enteros. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | Convierte los datos del flujo a una matriz de enteros. |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| [write(bytes)](#write_bytes_15) | Escribe todos los bytes especificados en el flujo. |
| [write_byte(value)](#write_byte_value_16) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| [write_to(stream_container)](#write_to_stream_container_17) | Copia los datos contenidos a otro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | Copia los datos contenidos a otro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Inicializa una nueva instancia de la clase [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Inicializa una nueva instancia de la clase [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de datos. |
| dispose_stream | bool | si se establece en <c>true</c> el flujo se eliminará cuando se elimine el contenedor. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Inicializa una nueva instancia de la clase [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El flujo de datos. |
| dispose_stream | bool | si se establece en <c>true</c> el flujo se eliminará cuando se elimine el contenedor. |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

Inserta el contenedor de secuencia en la posición especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | int | La posición a la que insertar. |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo a insertar. |
| dispose_stream | bool | si se establece en <c>true</c> elimina el flujo. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia en la cantidad de bytes leídos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| búfer | byte | Una matriz de bytes. Cuando este método devuelve, el búfer contiene la matriz de bytes especificada con los valores entre <paramref name=\"offset\" /> y (<paramref name=\"offset\" /> + <paramref name=\"count\" /> - 1) reemplazados por los bytes leídos de la fuente actual. |
| offset | int | El desplazamiento de byte basado en cero en <paramref name=\"buffer\" /> en el que comenzar a almacenar los datos leídos del flujo actual. |
| count | int | El número máximo de bytes a leer del flujo actual. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El número total de bytes leídos en el búfer. Esto puede ser menor que el número de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se ha alcanzado el final del flujo. |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

Lee bytes para llenar el búfer de bytes especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | byte | Los bytes a rellenar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El número de bytes leídos. Este valor puede ser menor que el número de bytes en el búfer si no hay suficientes bytes en el flujo. |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El byte sin signo convertido a Int32, o -1 si está al final del flujo. |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

Guarda (copia) los datos de la secuencia al flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) y el valor de la secuencia [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo al que guardar los datos. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

Guarda (copia) todos los datos de la secuencia al flujo especificado. Utiliza el valor de la secuencia [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo al que guardar los datos. |
| buffer_size | int | El búfer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

Guarda (copia) los datos de la secuencia al flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | El flujo al que guardar los datos. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor ReadWriteBytesCount. |
| length | long | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece al valor de [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/). |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

Guarda (copia) los datos de la secuencia al flujo especificado. Utiliza el tamaño de búfer predeterminado [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) y el valor de la secuencia [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor del flujo [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

Guarda (copia) los datos de la secuencia al flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del flujo. |
| buffer_size | int | El tamaño del búfer. Por defecto se usa el valor de [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | La longitud de los datos del flujo a copiar. Por defecto, la longitud se establece al valor de [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

Establece la posición dentro del flujo actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| offset | long | Un desplazamiento de bytes relativo al parámetro <paramref name="origin" />. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Un valor del tipo SeekOrigin que indica el punto de referencia utilizado para obtener la nueva posición. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | La nueva posición dentro del flujo actual. |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

Convierte los datos del flujo a una matriz de enteros.

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Los datos del flujo convertidos al arreglo de enteros. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

Convierte los datos del flujo a una matriz de enteros.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| position | long | La posición desde la cual comenzar a leer bytes. |
| bytes_count | long | La cantidad de bytes a leer. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Los datos del flujo convertidos al arreglo de enteros. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| búfer | byte | Una matriz de bytes. Este método copia <paramref name="count" /> bytes de <paramref name="buffer" /> al flujo actual. |
| offset | int | El desplazamiento de bytes basado en cero en <paramref name="buffer" /> donde comenzar a copiar bytes al flujo actual. |
| count | int | El número de bytes que se escribirán en el flujo actual. |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

Escribe todos los bytes especificados en el flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | byte | Los bytes a escribir. |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | byte | El byte a escribir en el flujo. |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

Copia los datos contenidos a otro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo al que copiar. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

Copia los datos contenidos a otro [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo al que copiar. |
| longitud | long | La cantidad de bytes a escribir. |

