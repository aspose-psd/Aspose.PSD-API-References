---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD لمرجع .NET API
description: LayerResourcesRegistry طريقة. يحصل على أول واصف افتتاحية مدعوم.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

يحصل على أول واصف افتتاحية مدعوم.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق. |
| psdVersion | Int32 | إصدار PSD. |

### قيمة الإرجاع

واصف محمل مورد الطبقة أو خالٍ إذا لم يتم دعم واصف محمل لهذا التدفق.

### ملاحظات

سيكون المحمل الأول هو آخر محمل مسجل.

### أنظر أيضا

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* المجسم [Aspose.PSD](../../../)


