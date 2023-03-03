---
title: LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor
second_title: Справочник по Aspose.PSD для .NET API
description: LayerResourcesRegistry метод. ЗагрузкиLayerResource с помощью первого найденного открывателя подходящего для указанногоstream .
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Загрузки[`LayerResource`](../../layerresource/) с помощью первого найденного открывателя, подходящего для указанного*stream* .

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| psdVersion | Int32 | Версия PSD. |

### Возвращаемое значение

Загруженный[`LayerResource`](../../layerresource/) или null, если открыватель не найден.

### Примечания

Первый открыватель будет последним зарегистрированным.

### Смотрите также

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* сборка [Aspose.PSD](../../../)


