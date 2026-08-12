---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод IImageLoaderDescriptor. Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и, при необходимости, используя *loadOptions*"
type: docs
weight: 10
url: /ru/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

Определяет, может ли загрузчик изображений прочитать новое изображение из указанного потока и при необходимости используя *loadOptions*.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | StreamContainer | Контейнер потока. |
| loadOptions | LoadOptions | Подробности формата файла, указанные в *loadOptions*. *loadOptions* может быть null. |

### Возвращаемое значение

`true`, если загрузчик изображений, созданный этим дескриптором, может читать изображение из потока; иначе `false`.

### См. также

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


