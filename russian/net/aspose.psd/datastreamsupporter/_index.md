---
title: Class DataStreamSupporter
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.DataStreamSupporter сорт. Контейнер потока данных.
type: docs
weight: 740
url: /ru/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

Контейнер потока данных.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные объекта и чтение данных не требуется. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Удаляет текущий экземпляр. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Сохраняет данные объекта в текущий`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Сохраняет данные объекта в указанном месте файла. |

### Смотрите также

* class [DisposableObject](../disposableobject/)
* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


