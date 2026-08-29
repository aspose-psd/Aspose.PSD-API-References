---
title: "IPartialRawDataLoader.Process"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод IPartialRawDataLoader. Обрабатывает загруженные данные"
type: docs
weight: 10
url: /ru/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

Обрабатывает загруженные данные.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| прямоугольник | Rectangle | Прямоугольник данных. |
| данные | Byte[] | Сырые данные. |
| start | Point | Начальная точка данных. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| конец | Point | Конечная точка данных. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

### См. также

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Обрабатывает загруженные данные.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| прямоугольник | Rectangle | Прямоугольник данных. |
| данные | Byte[] | Сырые данные. |
| start | Point | Начальная точка данных. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| конец | Point | Конечная точка данных. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |
| loadOptions | LoadOptions | Параметры загрузки. |

### См. также

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


