---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Загрузчик частичных данных."
type: docs
weight: 133
url: /ru/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Загрузчик частичных данных.
## Методы

| Метод | Описание |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Обрабатывает загруженные данные. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Обрабатывает загруженные данные. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Обрабатывает загруженные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник данных. |
| данные | byte[] | Сырые данные. |
| start | [Point](../../com.aspose.psd/point) | Начальная точка данных. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.psd/point) | Конечная точка данных. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Обрабатывает загруженные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник данных. |
| данные | byte[] | Сырые данные. |
| start | [Point](../../com.aspose.psd/point) | Начальная точка данных. Если не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.psd/point) | Конечная точка данных. Если не равна (right,bottom), это означает, что у нас не полный прямоугольник. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

