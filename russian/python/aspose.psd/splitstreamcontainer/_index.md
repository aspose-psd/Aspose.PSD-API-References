---
title: "Класс SplitStreamContainer"
type: docs
weight: 4220
url: /ru/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Инициализирует новый экземпляр класса [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Инициализирует новый экземпляр класса [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Инициализирует новый экземпляр класса [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Указывает количество байтов чтения и записи при последовательном чтении. |
| can_read | bool | r | Возвращает значение, указывающее, поддерживает ли поток чтение. |
| can_seek | bool | r | Возвращает значение, указывающее, поддерживает ли поток поиск. |
| can_write | bool | r | Возвращает значение, указывающее, поддерживает ли поток запись. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| is_stream_disposed_on_close | bool | r | Возвращает значение, указывающее, будет ли этот поток освобождён при закрытии. |
| длина | long | r/w | Получает или задаёт длину потока в байтах. Это значение меньше чем  по начальной позиции потока, переданной в конструктор StreamContainer. |
| position | long | r/w | Получает или задаёт текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструктор StreamContainer. |
| поток | _io.BufferedRandom | r | Получает поток данных. |
| sync_root | object | r | Получает объект, который можно использовать для синхронизации доступа к синхронизированному ресурсу. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| flush() | Очищает все буферы этого потока и заставляет любые буферизованные данные быть записанными в базовое устройство. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | Вставляет контейнер потока в указанную позицию. |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [read(bytes)](#read_bytes_3) | Читает байты для заполнения указанного буфера байтов. |
| [read_byte()](#read_byte__4) | Читает байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока. |
| [save(destination_stream)](#save_destination_stream_5) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) и значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(file_path)](#save_file_path_8) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) и значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | Сохраняет (копирует) данные потока в указанный поток. |
| [seek(offset, origin)](#seek_offset_origin_11) | Устанавливает позицию в текущем потоке. |
| seek_begin() | Устанавливает позицию потока в начало потока. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| [to_bytes()](#to_bytes__12) | Преобразует данные потока в массив int. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | Преобразует данные потока в массив int. |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [write(bytes)](#write_bytes_15) | Записывает все указанные байты в поток. |
| [write_byte(value)](#write_byte_value_16) | Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт. |
| [write_to(stream_container)](#write_to_stream_container_17) | Копирует содержащиеся данные в другой [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | Копирует содержащиеся данные в другой [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Инициализирует новый экземпляр класса [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Инициализирует новый экземпляр класса [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток данных. |
| dispose_stream | bool | если установлено в <c>true</c>, поток будет освобождён при освобождении контейнера. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Инициализирует новый экземпляр класса [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Поток данных. |
| dispose_stream | bool | если установлено в <c>true</c>, поток будет освобождён при освобождении контейнера. |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

Вставляет контейнер потока в указанную позицию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | int | Позиция для вставки. |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для вставки. |
| dispose_stream | bool | если установлено в <c>true</c>, освобождает поток. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| buffer | байт | Массив байтов. После возврата этого метода буфер содержит указанный массив байтов, где значения между <paramref name="offset" /> и (<paramref name="offset" /> + <paramref name="count" /> - 1) заменены байтами, считанными из текущего источника. |
| offset | int | Нулевой байтовый смещение в <paramref name="buffer" />, с которого начинать сохранять данные, считанные из текущего потока. |
| количество | int | Максимальное количество байтов, которое будет считано из текущего потока. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Общее количество байтов, считанных в буфер. Оно может быть меньше запрошенного количества байтов, если столько байтов в данный момент недоступно, или равно нулю (0), если достигнут конец потока. |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

Читает байты для заполнения указанного буфера байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты для заполнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество считанных байтов. Это значение может быть меньше количества байтов в буфере, если в потоке недостаточно байтов. |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

Читает байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Беззнаковый байт, преобразованный в Int32, или -1, если достигнут конец потока. |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) и значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |
| buffer_size | int | Буфер. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Поток, в который сохраняются данные. |
| buffer_size | int | Размер буфера. По умолчанию используется значение ReadWriteBytesCount. |
| length | long | Длина данных потока для копирования. По умолчанию длина устанавливается в значение [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/). |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) и значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, в который сохраняются данные потока. |
| buffer_size | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | Длина данных потока для копирования. По умолчанию длина устанавливается в значение [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

Устанавливает позицию в текущем потоке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| offset | long | Смещение в байтах относительно параметра <paramref name="origin" />. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Значение типа SeekOrigin, указывающее точку отсчёта, используемую для получения новой позиции. |

**Returns**

| Тип | Описание |
| :- | :- |
| long | Новая позиция в текущем потоке. |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

Преобразует данные потока в массив int.

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Данные потока, преобразованные в массив int. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

Преобразует данные потока в массив int.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, с которой начинать чтение байтов. |
| bytes_count | long | Количество байтов для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Данные потока, преобразованные в массив int. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| buffer | байт | Массив байтов. Этот метод копирует <paramref name="count" /> байтов из <paramref name="buffer" /> в текущий поток. |
| offset | int | Нулевое смещение в байтах в <paramref name="buffer" />, с которого начинать копировать байты в текущий поток. |
| количество | int | Количество байтов, которое будет записано в текущий поток. |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

Записывает все указанные байты в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты для записи. |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

Записывает байт в текущую позицию потока и перемещает позицию в потоке на один байт.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | байт | Байт для записи в поток. |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

Копирует содержащиеся данные в другой [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока, в который копировать. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

Копирует содержащиеся данные в другой [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока, в который копировать. |
| длина | long | Количество байтов для записи. |

