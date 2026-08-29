---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageExportersRegistry. Создаёт первый найденный экспортер, подходящий для указанных параметров сохранения и изображения"
type: docs
weight: 30
url: /ru/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

Создаёт первый найденный экспортёр, подходящий для указанных параметров сохранения и изображения.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Изображение для экспорта. |
| опции | ImageOptionsBase | Параметры сохранения, используемые для экспорта. |

### Возвращаемое значение

Экспортер, который поддерживает указанное изображение и параметры сохранения, или null, если такой экспортер не найден.

## Примечания

Первый экспортер на самом деле будет последним зарегистрированным.

### См. также

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


