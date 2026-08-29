---
title: "Класс LayerResourcesRegistry"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry. Определяет реестр ресурсов слоёв для загрузки PSD‑файлов"
type: docs
weight: 3790
url: /ru/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

Определяет реестр ресурсов слоёв для загрузки файлов PSD.

```csharp
public static class LayerResourcesRegistry
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Получает зарегистрированные дескрипторы. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Получает первый поддерживаемый дескриптор открывателя. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Получает первый поддерживаемый дескриптор по его имени типа. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Загружает [`LayerResource`](../layerresource/) используя первый найденный открыватель, подходящий для указанного *потока*. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Регистрирует открыватель. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Отменяет регистрацию открывателя. |

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


