---
title: "Класс ImageLoadersRegistry"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ImageLoadersRegistry. Представляет реестр загрузчиков изображений"
type: docs
weight: 5270
url: /ru/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Представляет реестр загрузчиков изображений.

```csharp
public static class ImageLoadersRegistry
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Получает зарегистрированные дескрипторы. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Получает зарегистрированные форматы загрузки изображений. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Создаёт первый найденный загрузчик, подходящий для указанного *stream* и, при необходимости, *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного *stream* и, при необходимости, *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Получает первый поддерживаемый файловый формат по его имени типа. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Получает первый поддерживаемый дескриптор по его имени типа. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Регистрирует указанный дескриптор загрузчика изображений. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Регистрирует загрузчик. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Отменяет регистрацию загрузчика. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


