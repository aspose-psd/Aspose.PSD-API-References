---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageExportersRegistry. Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения"
type: docs
weight: 40
url: /ru/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для экспорта. |
| опции | ImageOptionsBase | Опции. |

### Возвращаемое значение

Дескриптор экспортера, который поддерживает указанное изображение и параметры сохранения, или null, если такой дескриптор не найден.

## Примечания

Первый дескриптор экспортера на самом деле будет последним зарегистрированным.

### См. также

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


