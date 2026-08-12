---
title: "Класс ImageExportersRegistry"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ImageExportersRegistry. Представляет реестр экспортёров изображений"
type: docs
weight: 5100
url: /ru/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Представляет реестр экспортёров изображений.

```csharp
public static class ImageExportersRegistry
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Получает зарегистрированные дескрипторы экспортёров. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Получает зарегистрированные форматы экспорта. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Создаёт первый найденный экспортёр, подходящий для указанных параметров сохранения и изображения. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Регистрирует указанный дескриптор экспортёра изображений. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Регистрирует экспортёр. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Отменяет регистрацию экспортёра. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


