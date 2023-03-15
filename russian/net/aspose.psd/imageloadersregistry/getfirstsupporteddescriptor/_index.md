---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Справочник по Aspose.PSD для .NET API
description: ImageLoadersRegistry метод. Получает первый найденный поддерживаемый дескриптор подходящий для указанногоstream и необязательноloadOptions .
type: docs
weight: 40
url: /ru/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Получает первый найденный поддерживаемый дескриптор, подходящий для указанного*stream* и необязательно*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| loadOptions | LoadOptions | Варианты загрузки. |

### Возвращаемое значение

Дескриптор загрузчика, который поддерживает указанный*stream* и*loadOptions* или null, если такой дескриптор не найден.

### Примечания

Первый дескриптор загрузчика фактически будет последним зарегистрированным.

### Смотрите также

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* пространство имен [Aspose.PSD](../../imageloadersregistry/)
* сборка [Aspose.PSD](../../../)


