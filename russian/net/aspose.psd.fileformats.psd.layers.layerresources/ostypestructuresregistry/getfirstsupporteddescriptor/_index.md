---
title: "OSTypeStructuresRegistry.GetFirstSupportedDescriptor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод OSTypeStructuresRegistry. Получает первый поддерживаемый дескриптор открывателя"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry.GetFirstSupportedDescriptor method

Получает первый поддерживаемый дескриптор открывателя.

```csharp
public static IOSTypeStructureLoader GetFirstSupportedDescriptor(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |

### Возвращаемое значение

Дескриптор загрузчика ресурсов слоя или null, если для такого потока не поддерживается дескриптор загрузчика.

## Примечания

Первый загрузчик на самом деле будет последним зарегистрированным.

### См. также

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


