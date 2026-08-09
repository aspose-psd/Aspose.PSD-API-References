---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ImageExportersRegistry. تُنشئ أول مُصدِّر تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة"
type: docs
weight: 30
url: /ar/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

ينشئ أول مُصدِّر يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد تصديرها. |
| خيارات | ImageOptionsBase | خيارات الحفظ المستخدمة للتصدير. |

### قيمة الإرجاع

المُصدِّر الذي يدعم الصورة المحددة وخيارات الحفظ أو null إذا لم يتم العثور على مثل هذا المُصدِّر.

## ملاحظات

المُصدِّر الأول سيكون في الواقع الأخير المسجَّل.

### انظر أيضًا

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


