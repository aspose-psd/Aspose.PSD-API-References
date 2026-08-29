---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ImageOptionsBase. تحصل أو تعيين الخط البديل الافتراضي الذي سيُستخدم لرسم النص عند التصدير إلى نقطية إذا لم يكن خط الطبقة الموجودة في ملف PSD موجودًا في النظام. للحصول على الاسم الصحيح للخط الافتراضي يمكن استخدام مقتطف الشيفرة التالي System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /ar/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

يحصل أو يعيّن الخط البديل الافتراضي (الخط الذي سيُستخدم لرسم النص عند التصدير إلى نقطية، إذا لم يكن خط الطبقة الموجود في ملف PSD موجودًا في النظام). للحصول على اسم الخط الافتراضي الصحيح يمكن استخدام المقتطف البرمجي التالي: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

الخط البديل الافتراضي.

## أمثلة

المثال التالي يوضح كيفية استخدام خاصية DefaultReplacementFont لتغيير الخط البديل الافتراضي.

```csharp
[C#]

// يرجى عدم تثبيت خط Konstanting، لأن هذا الاختبار يجب أن يستبدل خطًا غير مثبت.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // بهذه الطريقة يمكنك استخدام خطوط مختلفة لمخرجات مختلفة.
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### انظر أيضًا

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


