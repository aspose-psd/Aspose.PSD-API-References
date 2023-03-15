---
title: Class ImageLoadersRegistry
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.ImageLoadersRegistry сорт. Представляет реестр загрузчиков образов.
type: docs
weight: 4780
url: /ru/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Представляет реестр загрузчиков образов.

```csharp
public static class ImageLoadersRegistry
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Получает зарегистрированные дескрипторы. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Получает зарегистрированные форматы загрузки изображений. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Создает первый найденный загрузчик, подходящий для указанного*stream* и необязательно*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанного*stream* и необязательно*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Получает первый поддерживаемый формат файла по имени его типа. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Получает первый поддерживаемый дескриптор по имени его типа. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Регистрирует указанный дескриптор загрузчика изображения. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Регистрирует загрузчик. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Отменяет регистрацию загрузчика. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


