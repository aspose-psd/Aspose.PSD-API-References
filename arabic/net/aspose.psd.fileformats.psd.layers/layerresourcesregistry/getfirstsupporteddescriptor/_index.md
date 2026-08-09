---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerResourcesRegistry. يحصل على أول وصف مفتاح مدعوم."
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

يحصل على أول مُوَصِّف للفتح المدعوم.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق. |
| psdVersion | Int32 | إصدار PSD. |

### قيمة الإرجاع

وصف محمل مورد الطبقة أو null إذا لم يكن هناك وصف محمل مدعوم لهذا التدفق.

## ملاحظات

المحمّل الأول سيكون في الواقع الأخير المسجل.

### انظر أيضًا

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


