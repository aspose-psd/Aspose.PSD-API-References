---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ImageExportersRegistry. تحصل على أول مُوَصِّف مدعوم تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة"
type: docs
weight: 40
url: /ar/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

يحصل على أول وصف مدعوم يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد تصديرها. |
| خيارات | ImageOptionsBase | الخيارات. |

### قيمة الإرجاع

مُوَصِّف المُصدِّر الذي يدعم الصورة المحددة وخيارات الحفظ أو null إذا لم يتم العثور على مثل هذا المُوَصِّف.

## ملاحظات

المُوَصِّف الأول للمُصدِّر سيكون في الواقع الأخير المسجَّل.

### انظر أيضًا

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


