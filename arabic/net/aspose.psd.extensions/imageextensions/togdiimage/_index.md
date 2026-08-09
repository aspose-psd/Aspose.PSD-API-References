---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ImageExtensions. يحول الـ Image إلى الـ Image"
type: docs
weight: 10
url: /ar/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

يقوم بتحويل الـ Image إلى الـ Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة للتحويل. |

### قيمة الإرجاع

الصورة المحوّلة.

## ملاحظات

تحذير، قد يحصل صورة GDI على حدود أقل مما تمتلكه *image*. للحصول على جميع أجزاء الصورة استخدم طريقة الامتداد الأكثر أمانًا ToGdiImageFull.

### انظر أيضًا

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


