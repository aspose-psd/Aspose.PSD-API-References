---
title: RasterImage.SavePixels
second_title: Aspose.PSD لمرجع .NET API
description: RasterImage طريقة. يحفظ البكسل .
type: docs
weight: 520
url: /ar/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

يحفظ البكسل .

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rectangle | Rectangle | المستطيل الذي سيتم حفظ البكسل فيه. |
| pixels | Color[] | صفيف البكسل. |

### أمثلة

يوضح هذا المثال كيفية تحميل معلومات البكسل في مصفوفة من نوع اللون ، ومعالجة المصفوفة وإعادة تعيينها إلى الصورة. لإجراء هذه العمليات ، يقوم هذا المثال بإنشاء ملف صورة جديد (بتنسيق PSD) باستخدام كائن MemoryStream.

```csharp
[C#]

// إنشاء مثيل لـ MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // أنشئ مثيلاً من PsdOptions وعيّن خصائصه المتنوعة بما في ذلك خاصية المصدر
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // احصل على وحدات البكسل في الصورة عن طريق تحديد المنطقة كحدود للصورة
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // حلقة فوق المصفوفة وتعيين لون البكسل المفهرس
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // اضبط لون البكسل المفهرس على اللون الأصفر
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                // اضبط لون البكسل المفهرس على اللون الأزرق
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // قم بتطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    // اكتب MemoryStream إلى ملف
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### أنظر أيضا

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* مساحة الاسم [Aspose.PSD](../../rasterimage/)
* المجسم [Aspose.PSD](../../../)


