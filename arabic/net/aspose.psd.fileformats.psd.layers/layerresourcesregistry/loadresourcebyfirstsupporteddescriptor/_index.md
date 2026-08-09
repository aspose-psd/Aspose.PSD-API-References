---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerResourcesRegistry. تُحمّل LayerResource باستخدام أول مفتاح تم العثور عليه مناسب للتدفق المحدد."
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

يحمّل [`LayerResource`](../../layerresource/) باستخدام أول مفتاح تم العثور عليه مناسب لـ *stream* المحدد.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| psdVersion | Int32 | إصدار PSD. |

### قيمة الإرجاع

الـ[`LayerResource`](../../layerresource/) المحمّل أو null إذا لم يُعثر على أي مفتاح.

## ملاحظات

المفتاح الأول سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


