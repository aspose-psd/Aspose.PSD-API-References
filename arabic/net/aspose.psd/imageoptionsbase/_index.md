---
title: "الفئة ImageOptionsBase"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.ImageOptionsBase. خيارات الصورة الأساسية."
type: docs
weight: 5480
url: /ar/net/aspose.psd/imageoptionsbase/
---
{{< psd/tize >}}
## ImageOptionsBase class

خيارات الصورة الأساسية.

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [الإطار الكامل]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يعيّن معالج حدث التقدم. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يعيّن إعدادات الدقة. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | يحصل أو يعيّن المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يعيّن خيارات تحويل المتجه إلى نقطية. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات التعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | ينسخ هذه المثيل. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


