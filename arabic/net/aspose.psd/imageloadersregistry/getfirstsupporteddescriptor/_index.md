---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ImageLoadersRegistry. يحصل على أول وصف مدعوم تم العثور عليه مناسب للمجرى المحدد واختياريًا loadOptions"
type: docs
weight: 40
url: /ar/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

يحصل على أول وصف مدعوم يتم العثور عليه المناسب لـ *stream* المحدد وبشكل اختياري *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

وصف التحميل الذي يدعم *stream* و*loadOptions* المحددين أو null إذا لم يتم العثور على مثل هذا الوصف.

## ملاحظات

وصف التحميل الأول سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


