---
title: StreamSource.StreamSource
second_title: Aspose.PSD لمرجع .NET API
description: StreamSource البناء. يقوم بتهيئة مثيل جديد لملفStreamSource فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`StreamSource`](../) فئة .

```csharp
public StreamSource(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لفتح. |

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

* class [StreamSource](../)
* مساحة الاسم [Aspose.PSD.Sources](../../streamsource/)
* المجسم [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`StreamSource`](../) فئة .

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لفتح. |
| disposeStream | Boolean | إذا تم التعيين على`حقيقي` سيتم التخلص من الدفق. |

### أمثلة

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد

```csharp
[C#]

// ينشئ مثيلاً من PsdOptions ويضبط خصائصه المختلفة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// إنشاء مثيل System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

// حدد خاصية المصدر لمثيل PsdOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان سيتم التخلص من الدفق بمجرد الخروج من النطاق
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// ينشئ مثيلًا للصورة واستدعاء طريقة الإنشاء مع PsdOptions كمعامل لتهيئة كائن الصورة   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // القيام ببعض معالجة الصور
}
```

### أنظر أيضا

* class [StreamSource](../)
* مساحة الاسم [Aspose.PSD.Sources](../../streamsource/)
* المجسم [Aspose.PSD](../../../)


