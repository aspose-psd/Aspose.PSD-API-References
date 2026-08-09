---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ StreamSource. يهيئ مثيلًا جديدًا من الفئة StreamSource"
type: docs
weight: 10
url: /ar/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

يهيئ مثيلًا جديدًا من الفئة [`StreamSource`](../) .

```csharp
public StreamSource(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق للفتح. |

## أمثلة

هذا المثال يوضح كيفية تحميل معلومات البكسل في مصفوفة من نوع Color، تعديل المصفوفة وإعادتها إلى الصورة. لتنفيذ هذه العمليات، ينشئ هذا المثال ملف Image جديد (بتنسيق PSD) باستخدام كائن MemoryStream.

```csharp
[C#]

//إنشاء مثال من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //إنشاء مثال من PsdOptions وتعيين خصائصه المتنوعة بما في ذلك خاصية Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //إنشاء مثال من Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //احصل على بكسلات الصورة عن طريق تحديد المنطقة كحدود الصورة
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //تكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //تعيين لون البكسل المفهرس إلى الأصفر
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //تعيين لون البكسل المفهرس إلى الأزرق
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //تطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    //اكتب MemoryStream إلى ملف
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### انظر أيضًا

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

يهيئ مثيلًا جديدًا من الفئة [`StreamSource`](../) .

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق للفتح. |
| disposeStream | Boolean | إذا تم تعيينه إلى `true` سيتم التخلص من الدفق. |

## أمثلة

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد.

```csharp
[C#]

//ينشئ مثيلاً من PsdOptions ويضبط خصائصه المتنوعة.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//إنشاء مثيل من System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//تحديد خاصية المصدر للمثيل من PsdOptions.
//المعامل البولياني الثاني يحدد ما إذا كان سيتم التخلص من الـ Stream بمجرد الخروج من النطاق.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//ينشئ مثيلاً من Image ويستدعي طريقة Create مع PsdOptions كمعامل لتهيئة كائن Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

### انظر أيضًا

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


