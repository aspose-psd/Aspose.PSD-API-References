---
title: "فئة LayerResourcesRegistry"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry فئة. تعريف سجل موارد الطبقة لتحميل ملفات PSD"
type: docs
weight: 3790
url: /ar/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

حدد سجل موارد الطبقة لتحميل ملفات PSD.

```csharp
public static class LayerResourcesRegistry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | يحصل على المُوَصِّفات المسجلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | يحصل على أول مُوَصِّف للفتح المدعوم. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | يحصل على أول مُوَصِّف مدعوم حسب اسم النوع الخاص به. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | يقوم بتحميل [`LayerResource`](../layerresource/) باستخدام أول مفتاح تم العثور عليه مناسب للـ *stream* المحدد. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | يسجل المفتاح. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | يلغي تسجيل المفتاح. |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


