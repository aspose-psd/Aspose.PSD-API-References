---
title: "Класс TiffDataType"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Возвращает дополнительный размер данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега). |
| количество | uint | r | Возвращает количество элементов. |
| data_size | uint | r | Возвращает дополнительный размер данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега). |
| id | ushort | r | Возвращает целочисленное представление идентификатора тега. |
| is_valid | bool | r | Возвращает значение, указывающее, являются ли данные тега действительными. Действительный тег содержит данные, которые могут быть сохранены. Недействительный тег не может быть сохранён. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Возвращает идентификатор тега. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Возвращает тип тега. |
| значение | object | r/w | Получает или задает значение, содержащееся в этом типе данных. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект. |
| [deep_clone()](#deep_clone__2) | Выполняет глубокое клонирование этого экземпляра. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Читает данные тега. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Записывает дополнительные данные тега. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Записывает данные тега. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| obj | object | Объект для сравнения с этим экземпляром. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | 32-битное знаковое целое, указывающее относительный порядок сравниваемых объектов. Возвращаемое значение имеет следующие значения:<br/>            Значение<br/>            Смысл<br/>            Меньше нуля<br/>            Этот экземпляр меньше, чем <paramref name=\"obj\" />.<br/>            Ноль<br/>            Этот экземпляр равен <paramref name=\"obj\" />.<br/>            Больше нуля<br/>            Этот экземпляр больше, чем <paramref name=\"obj\" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Выполняет глубокое клонирование этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Глубокая копия текущего экземпляра. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Читает данные тега.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Поток данных. |
| position | long | Позиция тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Прочитанный тег. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Записывает дополнительные данные тега.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Поток данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| long | Фактическое количество записанных байтов. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Записывает данные тега.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Поток данных. |
| additional_data_offset | long | Смещение, в которое записываются дополнительные данные. |

