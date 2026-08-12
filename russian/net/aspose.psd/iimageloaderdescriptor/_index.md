---
title: "Интерфейс IImageLoaderDescriptor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Интерфейс Aspose.PSD.IImageLoaderDescriptor. Дескриптор загрузчика изображений, определяющий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности."
type: docs
weight: 4930
url: /ru/net/aspose.psd/iimageloaderdescriptor/
---
{{< psd/tize >}}
## IImageLoaderDescriptor interface

Дескриптор загрузчика изображения, указывающий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости держать каждый экземпляр загрузчика изображения в памяти и проблем многопоточности.

```csharp
public interface IImageLoaderDescriptor : IImageDescriptor
```

## Методы

| Имя | Описание |
| --- | --- |
| [CanLoad](../../aspose.psd/iimageloaderdescriptor/canload/)(StreamContainer, LoadOptions) | Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и при необходимости используя *loadOptions*. |
| [CreateInstance](../../aspose.psd/iimageloaderdescriptor/createinstance/)() | Создаёт новый экземпляр загрузчика. |

### См. также

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


