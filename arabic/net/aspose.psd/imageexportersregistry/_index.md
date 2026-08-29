---
title: "الفئة ImageExportersRegistry"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.ImageExportersRegistry. تمثل سجل مُصدِّري الصور"
type: docs
weight: 5100
url: /ar/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

يمثل سجل مصدري الصور.

```csharp
public static class ImageExportersRegistry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | يحصل على أوصاف المُصدِّرين المسجلين. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | يحصل على صيغ التصدير المسجلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | ينشئ أول مُصدِّر يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | يحصل على أول وصف مدعوم يتم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | يسجِّل وصف مُصدِّر الصورة المحدد. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | يسجِّل المُصدِّر. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | يلغي تسجيل المُصدِّر. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


