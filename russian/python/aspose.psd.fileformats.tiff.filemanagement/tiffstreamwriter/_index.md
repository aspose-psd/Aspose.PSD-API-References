---
title: "Класс TiffStreamWriter"
type: docs
weight: 20
url: /ru/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Инициализирует новый экземпляр класса [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| position | long | r/w | Получает или задает позицию потока. |
| sync_root | object | r | Получает объект, который можно использовать для синхронизации доступа к синхронизированному ресурсу. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [write(data)](#write_data_1) | Записывает указанные данные. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Записывает указанные данные. |
| [write_double(data)](#write_double_data_3) | Записывает одно значение double в поток. |
| [write_double_array(data)](#write_double_array_data_4) | Записывает массив значений double в поток. |
| [write_float(data)](#write_float_data_5) | Записывает одно значение float в поток. |
| [write_float_array(data)](#write_float_array_data_6) | Записывает массив значений float в поток. |
| [write_rational(data)](#write_rational_data_7) | Записывает одно значение рационального числа в поток. |
| [write_rational_array(data)](#write_rational_array_data_8) | Записывает массив беззнаковых рациональных значений в поток. |
| [write_s_byte(data)](#write_s_byte_data_9) | Записывает одно знаковое байтовое значение в поток. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Записывает массив знаковых байтовых значений в поток. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Записывает массив целочисленных значений в поток. |
| [write_s_rational(data)](#write_s_rational_data_12) | Записывает одно знаковое рациональное число в поток. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Записывает массив знаковых рациональных значений в поток. |
| [write_s_short(data)](#write_s_short_data_14) | Записывает одно значение short в поток. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Записывает массив значений short в поток. |
| [write_slong(data)](#write_slong_data_16) | Записывает одно целочисленное значение в поток. |
| [write_u_byte(data)](#write_u_byte_data_17) | Записывает одно байтовое значение в поток. |
| [write_u_long(data)](#write_u_long_data_18) | Записывает одно беззнаковое целочисленное значение в поток. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Записывает массив беззнаковых целочисленных значений в поток. |
| [write_u_short(data)](#write_u_short_data_20) | Записывает одно беззнаковое значение short в поток. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Записывает массив беззнаковых значений short в поток. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Инициализирует новый экземпляр класса [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Записыватель потока. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Записывает указанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные для записи. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Записывает указанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные для записи. |
| offset | int | Смещение данных. |
| data_length | int | Длина данных для записи. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Записывает одно значение double в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | double | Значение для записи. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Записывает массив значений double в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | double | Массив для записи. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Записывает одно значение float в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | float | Значение для записи. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Записывает массив значений float в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | float | Массив для записи. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Записывает одно значение рационального числа в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Значение для записи. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Записывает массив беззнаковых рациональных значений в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Массив для записи. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Записывает одно знаковое байтовое значение в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | sbyte | Значение для записи. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Записывает массив знаковых байтовых значений в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | sbyte | Массив для записи. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Записывает массив целочисленных значений в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | int | Массив для записи. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Записывает одно знаковое рациональное число в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Значение для записи. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Записывает массив знаковых рациональных значений в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Массив для записи. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Записывает одно значение short в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | short | Значение для записи. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Записывает массив значений short в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | short | Массив для записи. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Записывает одно целочисленное значение в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | int | Значение для записи. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Записывает одно байтовое значение в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Значение для записи. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Записывает одно беззнаковое целочисленное значение в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | uint | Значение для записи. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Записывает массив беззнаковых целочисленных значений в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | uint | Массив для записи. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Записывает одно беззнаковое значение short в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | ushort | Значение для записи. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Записывает массив беззнаковых значений short в поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | ushort | Массив для записи. |

