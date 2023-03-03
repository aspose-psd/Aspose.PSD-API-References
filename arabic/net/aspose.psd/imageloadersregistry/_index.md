---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageLoadersRegistry فصل. يمثل سجل برامج تحميل الصور.
type: docs
weight: 4780
url: /ar/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

يمثل سجل برامج تحميل الصور.

```csharp
public static class ImageLoadersRegistry
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | يحصل على الواصفات المسجلة . |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | الحصول على تنسيقات تحميل الصور المسجلة. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | إنشاء أول محمل يتم العثور عليه مناسبًا لما هو محدد*stream* واختياريا*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | الحصول على القبضة التي تم العثور عليها واصفًا مدعومًا مناسبًا لما هو محدد*stream* واختياريا*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | يحصل على أول تنسيق ملف مدعوم حسب نوعه. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | يحصل على أول واصف مدعوم حسب نوعه. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | يسجل واصف أداة تحميل الصور المحدد. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | تسجيل المحمل. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | إلغاء تسجيل المحمل. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


