---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry فصل. تحديد سجل موارد الطبقة لتحميل ملفات PSD.
type: docs
weight: 3390
url: /ar/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

تحديد سجل موارد الطبقة لتحميل ملفات PSD.

```csharp
public static class LayerResourcesRegistry
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | يحصل على الواصفات المسجلة . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | يحصل على أول واصف افتتاحية مدعوم. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | يحصل على أول واصف مدعوم حسب نوعه. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | الأحمال[`LayerResource`](../layerresource/) باستخدام أول فتاحة تم العثور عليها مناسبة لملف*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | تسجيل الفتح. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | إلغاء تسجيل الفتاحة. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* المجسم [Aspose.PSD](../../)


