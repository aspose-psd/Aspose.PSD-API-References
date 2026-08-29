---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageLoadersRegistry. Создает первый найденный загрузчик, подходящий для указанного stream и, при необходимости, loadOptions"
type: docs
weight: 30
url: /ru/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Создаёт первый найденный загрузчик, подходящий для указанного *stream* и, при необходимости, *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| loadOptions | LoadOptions | Параметры загрузки. |

### Возвращаемое значение

Загрузчик, который поддерживает указанные *stream* и *loadOptions*, или null, если такой загрузчик не найден.

## Примечания

Первый загрузчик на самом деле будет последним зарегистрированным.

### См. также

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


