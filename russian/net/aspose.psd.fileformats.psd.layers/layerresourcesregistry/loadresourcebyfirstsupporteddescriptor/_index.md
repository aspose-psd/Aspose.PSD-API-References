---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод LayerResourcesRegistry. Загружает LayerResource, используя первый найденный открыватель, подходящий для указанного потока"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Загружает [`LayerResource`](../../layerresource/) используя первый найденный открыватель, подходящий для указанного *stream*.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| psdVersion | Int32 | Версия PSD. |

### Возвращаемое значение

Загруженный [`LayerResource`](../../layerresource/) или null, если открыватель не найден.

## Примечания

Первый открыватель на самом деле будет последним зарегистрированным.

### См. также

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


