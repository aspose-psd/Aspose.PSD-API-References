---
title: "Класс IPartialRawDataLoader"
type: docs
weight: 1940
url: /ru/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Обрабатывает загруженные данные. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Обрабатывает загруженные данные. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Обрабатывает загруженные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник данных. |
| данные | байт | Необработанные данные. |
| start | [Point](/psd/python-net/aspose.psd/point) | Начальная точка данных. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/psd/python-net/aspose.psd/point) | Конечная точка данных. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Обрабатывает загруженные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник данных. |
| данные | байт | Необработанные данные. |
| start | [Point](/psd/python-net/aspose.psd/point) | Начальная точка данных. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/psd/python-net/aspose.psd/point) | Конечная точка данных. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

