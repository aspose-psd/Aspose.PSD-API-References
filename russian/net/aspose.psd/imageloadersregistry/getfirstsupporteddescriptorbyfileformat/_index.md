---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageLoadersRegistry. Получает первый поддерживаемый формат файла по его имени типа"
type: docs
weight: 50
url: /ru/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

Получает первый поддерживаемый файловый формат по его имени типа.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileFormat | FileFormat | Поддерживаемый формат файла дескриптора. |

### Возвращаемое значение

Первый найденный дескриптор загрузчика или null, если такой дескриптор не найден.

## Примечания

Первый дескриптор загрузчика на самом деле будет последним зарегистрированным.

### См. также

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


