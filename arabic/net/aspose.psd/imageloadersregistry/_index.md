---
title: "الفئة ImageLoadersRegistry"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.ImageLoadersRegistry. تمثل سجل محملات الصور"
type: docs
weight: 5270
url: /ar/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

يمثل سجل محملي الصور.

```csharp
public static class ImageLoadersRegistry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | يحصل على المُوَصِّفات المسجلة. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | يحصل على صيغ تحميل الصور المسجلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | ينشئ أول محمل يتم العثور عليه المناسب لـ *stream* المحدد وبشكل اختياري *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | يحصل على أول وصف مدعوم يتم العثور عليه المناسب لـ *stream* المحدد وبشكل اختياري *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | يحصل على أول صيغة ملف مدعومة حسب اسم النوع. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | يحصل على أول مُوَصِّف مدعوم حسب اسم النوع الخاص به. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | يسجل وصف محمل الصورة المحدد. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | يسجل المحمل. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | يلغي تسجيل المحمل. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


