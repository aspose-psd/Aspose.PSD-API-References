---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD لمرجع .NET API
description: ImageOptionsBase ملكية. الحصول على الخط البديل الافتراضي أو تعيينه الخط الذي سيتم استخدامه لرسم النص عند التصدير إلى خطوط المسح  إذا لم يتم تقديم خط الطبقة الموجود في ملف PSD في النظام.  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection  System.Drawing.FontFamily  Families  col.Families string افتراضي PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName
type: docs
weight: 20
url: /ar/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

الحصول على الخط البديل الافتراضي أو تعيينه (الخط الذي سيتم استخدامه لرسم النص عند التصدير إلى خطوط المسح ، إذا لم يتم تقديم خط الطبقة الموجود في ملف PSD في النظام). : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection ()؛ System.Drawing.FontFamily [] Families = col.Families؛ string افتراضي PsdLoadOptions psdLoadOptions = new PsdLoadOptions () {DefaultReplacementFont = defaultFontName})؛

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property_Value

خط الاستبدال الافتراضي .

### أمثلة

يوضح المثال التالي كيفية استخدام خاصية DefaultReplacementFont لتغيير خط الاستبدال الافتراضي.

```csharp
[C#]

// من فضلك ، لا تقم بتثبيت Konstanting Font ، لأن هذا الاختبار يجب أن يحل محل الخط غير المثبت
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // بهذه الطريقة يمكنك استخدام خطوط مختلفة لمخرجات مختلفة 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### أنظر أيضا

* class [ImageOptionsBase](../)
* مساحة الاسم [Aspose.PSD](../../imageoptionsbase/)
* المجسم [Aspose.PSD](../../../)


