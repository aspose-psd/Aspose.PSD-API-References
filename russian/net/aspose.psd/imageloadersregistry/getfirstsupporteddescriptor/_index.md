---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageLoadersRegistry. Получает первый найденный поддерживаемый дескриптор, подходящий для указанного *stream* и, при необходимости, *loadOptions*"
type: docs
weight: 40
url: /ru/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Получает первый найденный поддерживаемый дескриптор, подходящий для указанного *stream* и, при необходимости, *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| loadOptions | LoadOptions | Параметры загрузки. |

### Возвращаемое значение

Дескриптор загрузчика, поддерживающий указанные *stream* и *loadOptions*, или null, если такой дескриптор не найден.

## Примечания

Первый дескриптор загрузчика на самом деле будет последним зарегистрированным.

### См. также

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


