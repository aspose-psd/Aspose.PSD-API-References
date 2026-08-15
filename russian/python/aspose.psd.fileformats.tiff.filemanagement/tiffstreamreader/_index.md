---
title: "Класс TiffStreamReader"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| длина | long | r | Получает длину читателя. |
| throw_exceptions | bool | r/w | Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Считывает массив байтовых значений из потока. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Считывает массив беззнаковых байтовых значений из потока. |
| [read_double(position)](#read_double_position_3) | Считывает одно значение double из потока. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Считывает массив значений double из потока. |
| [read_float(position)](#read_float_position_5) | Считывает одно значение float из потока. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Считывает массив значений float из потока. |
| [read_rational(position)](#read_rational_position_7) | Считывает одно значение рационального числа из потока. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Считывает массив рациональных значений из потока. |
| [read_s_byte(position)](#read_s_byte_position_9) | Считывает данные знакового байта из потока. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Считывает массив значений знакового байта из потока. |
| [read_s_long(position)](#read_s_long_position_11) | Считывает значение знакового целого числа из потока. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Считывает массив значений знаковых целых чисел из потока. |
| [read_s_rational(position)](#read_s_rational_position_13) | Считывает одно значение знакового рационального числа из потока. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Считывает массив знаковых рациональных значений из потока. |
| [read_s_short(position)](#read_s_short_position_15) | Считывает значение знакового short из потока. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Считывает массив значений знакового short из потока. |
| [read_u_long(position)](#read_u_long_position_17) | Считывает значение беззнакового целого числа из потока. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Считывает массив значений беззнаковых целых чисел из потока. |
| [read_u_short(position)](#read_u_short_position_19) | Считывает значение беззнакового short из потока. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Считывает массив значений беззнаковых целых чисел из потока. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Преобразует базовые данные в контейнер потока. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Байтовый массив данных. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Байтовый массив данных. |
| start_index | int | Начальный индекс в <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Байтовый массив данных. |
| start_index | int | Начальный индекс в <paramref name="data" />. |
| data_length | int | Длина данных. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Инициализирует новый экземпляр класса [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Считывает массив байтовых значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| массив | байт | Массив для заполнения. |
| array_index | int | Индекс массива, с которого начинать помещать значения. |
| position | long | Позиция потока, из которой читать. |
| количество | long | Количество элементов для чтения. |

**Returns**

| Тип | Описание |
| :- | :- |
| long | Массив байтовых значений. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Считывает массив беззнаковых байтовых значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Массив беззнаковых байтовых значений. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Считывает одно значение double из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Одно значение double. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Считывает массив значений double из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Массив значений double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Считывает одно значение float из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| float | Одно значение float. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Считывает массив значений float из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| float | Массив значений float. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Считывает одно значение рационального числа из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Рациональное число. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Считывает массив рациональных значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Массив рациональных значений. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Считывает данные знакового байта из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| sbyte | Значение знакового байта. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Считывает массив значений знакового байта из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| sbyte | Массив значений знаковых байтов. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Считывает значение знакового целого числа из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение знакового целого. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Считывает массив значений знаковых целых чисел из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив значений знаковых целых. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Считывает одно значение знакового рационального числа из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Знаковое рациональное число. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Считывает массив знаковых рациональных значений из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Массив знаковых рациональных значений. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Считывает значение знакового short из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| short | Значение знакового short. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Считывает массив значений знакового short из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| short | Массив значений знаковых short. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Считывает значение беззнакового целого числа из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| uint | Значение беззнакового целого. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Считывает массив значений беззнаковых целых чисел из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| uint | Массив значений беззнаковых целых. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Считывает значение беззнакового short из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |

**Returns**

| Тип | Описание |
| :- | :- |
| ushort | Значение беззнакового short. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Считывает массив значений беззнаковых целых чисел из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| position | long | Позиция, из которой читать. |
| количество | long | Количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| ushort | Массив значений беззнаковых целых. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Преобразует базовые данные в контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_position | long | Начальная позиция, с которой начинается преобразование. |

**Returns**

| Тип | Описание |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Объект [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) с преобразованными данными. |


