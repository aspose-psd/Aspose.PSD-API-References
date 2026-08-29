---
title: "Класс DataStreamSupporter"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.DataStreamSupporter. Контейнер потока данных"
type: docs
weight: 750
url: /ru/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Контейнер потока данных.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Сохраняет данные объекта в текущий `DataStreamSupporter`. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |

### См. также

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


