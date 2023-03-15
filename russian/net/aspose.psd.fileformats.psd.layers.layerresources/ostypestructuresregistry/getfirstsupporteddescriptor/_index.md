---
title: OSTypeStructuresRegistry.GetFirstSupportedDescriptor
second_title: Справочник по Aspose.PSD для .NET API
description: OSTypeStructuresRegistry метод. Получает первый поддерживаемый дескриптор открывателя.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
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

### Примечания

Первый загрузчик будет последним зарегистрированным.

### Смотрите также

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ostypestructuresregistry/)
* сборка [Aspose.PSD](../../../)


