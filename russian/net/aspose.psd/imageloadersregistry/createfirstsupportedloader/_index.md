---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Справочник по Aspose.PSD для .NET API
description: ImageLoadersRegistry метод. Создает первый найденный загрузчик подходящий для указанногоstream и необязательноloadOptions .
type: docs
weight: 30
url: /ru/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Создает первый найденный загрузчик, подходящий для указанного*stream* и необязательно*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| loadOptions | LoadOptions | Варианты загрузки. |

### Возвращаемое значение

Загрузчик, поддерживающий указанный*stream* и*loadOptions* или null, если такой загрузчик не найден.

### Примечания

Первый загрузчик будет последним зарегистрированным.

### Смотрите также

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* пространство имен [Aspose.PSD](../../imageloadersregistry/)
* сборка [Aspose.PSD](../../../)


