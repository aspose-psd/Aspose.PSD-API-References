---
title: Class LayerResourcesRegistry
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry сорт. Определить реестр ресурсов слоя для загрузки файлов PSD.
type: docs
weight: 3390
url: /ru/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Определить реестр ресурсов слоя для загрузки файлов PSD.

```csharp
public static class LayerResourcesRegistry
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Получает зарегистрированные дескрипторы. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Получает первый поддерживаемый дескриптор открывателя. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Получает первый поддерживаемый дескриптор по имени его типа. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Загрузки[`LayerResource`](../layerresource/) с помощью первого найденного открывателя, подходящего для указанного*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Регистрирует открывалку. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Отменяет регистрацию открывателя. |

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* сборка [Aspose.PSD](../../)


