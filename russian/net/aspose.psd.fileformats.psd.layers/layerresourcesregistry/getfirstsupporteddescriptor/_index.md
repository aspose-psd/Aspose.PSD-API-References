---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Справочник по Aspose.PSD для .NET API
description: LayerResourcesRegistry метод. Получает первый поддерживаемый дескриптор открывателя.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Получает первый поддерживаемый дескриптор открывателя.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| psdVersion | Int32 | Версия PSD. |

### Возвращаемое значение

Дескриптор загрузчика ресурсов слоя или null, если для такого потока не поддерживается дескриптор загрузчика.

### Примечания

Первый загрузчик будет последним зарегистрированным.

### Смотрите также

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* сборка [Aspose.PSD](../../../)


