---
title: Interface IImageLoaderDescriptor
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.IImageLoaderDescriptor интерфейс. Дескриптор загрузчика изображения определяющий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности.
type: docs
weight: 4460
url: /ru/net/aspose.psd/iimageloaderdescriptor/
---
## IImageLoaderDescriptor interface

Дескриптор загрузчика изображения, определяющий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности.

```csharp
public interface IImageLoaderDescriptor : IImageDescriptor
```

## Методы

| Имя | Описание |
| --- | --- |
| [CanLoad](../../aspose.psd/iimageloaderdescriptor/canload/)(StreamContainer, LoadOptions) | Определяет, может ли загрузчик изображений читать новое изображение из указанного потока и, при необходимости, с помощью*loadOptions* . |
| [CreateInstance](../../aspose.psd/iimageloaderdescriptor/createinstance/)() | Создает новый экземпляр загрузчика. |

### Смотрите также

* interface [IImageDescriptor](../iimagedescriptor/)
* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


