---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод LayerResourcesRegistry. Получает первый поддерживаемый дескриптор открывателя"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
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

## Примечания

Первый загрузчик на самом деле будет последним зарегистрированным.

### См. также

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


