---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "ImageLoadersRegistry method. تُنشئ أول محمل تم العثور عليه مناسب للمسار المحدد و اختياريًا loadOptions"
type: docs
weight: 30
url: /ar/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

ينشئ أول محمل يتم العثور عليه المناسب لـ *stream* المحدد وبشكل اختياري *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

المحمل الذي يدعم *stream* و *loadOptions* المحددين أو null إذا لم يُعثر على محمل من هذا النوع.

## ملاحظات

المحمّل الأول سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


