---
title: "ImageExtensions.ToGdiImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageExtensions. Преобразует Image в Image."
type: docs
weight: 10
url: /ru/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Преобразует Image в Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | Image | Image для преобразования. |

### Возвращаемое значение

Преобразованный Image.

## Примечания

Предупреждение, GDI‑изображение может иметь меньшие границы, чем у *image*. Чтобы получить все части изображения, используйте более безопасный метод расширения ToGdiImageFull.

### См. также

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


