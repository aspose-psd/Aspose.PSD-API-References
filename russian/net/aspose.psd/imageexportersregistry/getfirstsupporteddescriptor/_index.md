---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Справочник по Aspose.PSD для .NET API
description: ImageExportersRegistry метод. Получает первый найденный поддерживаемый дескриптор подходящий для указанных параметров сохранения и изображения.
type: docs
weight: 40
url: /ru/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Получает первый найденный поддерживаемый дескриптор, подходящий для указанных параметров сохранения и изображения.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Image | Изображение для экспорта. |
| options | ImageOptionsBase | Варианты. |

### Возвращаемое значение

Дескриптор экспортера, который поддерживает указанное изображение и параметры сохранения, или null, если такой дескриптор не найден.

### Примечания

Первый дескриптор экспортера фактически будет последним зарегистрированным.

### Смотрите также

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* пространство имен [Aspose.PSD](../../imageexportersregistry/)
* сборка [Aspose.PSD](../../../)


