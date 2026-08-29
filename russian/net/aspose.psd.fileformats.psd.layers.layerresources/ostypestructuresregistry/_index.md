---
title: "Класс OSTypeStructuresRegistry"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry class. Представляет реестр ресурсов OSTypeStructure"
type: docs
weight: 3200
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

Представляет реестр ресурсов [`OSTypeStructure`](../ostypestructure/).

```csharp
public static class OSTypeStructuresRegistry
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | Получает зарегистрированные дескрипторы. |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | Получает первый поддерживаемый дескриптор открывателя. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | Получает первый поддерживаемый дескриптор по его имени типа. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | Загружает [`OSTypeStructure`](../ostypestructure/) с использованием первого найденного открывателя, подходящего для указанного *потока*. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | Регистрирует открыватель. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | Отменяет регистрацию открывателя. |

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


