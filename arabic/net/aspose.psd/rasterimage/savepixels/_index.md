---
title: "RasterImage.SavePixels"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة RasterImage. تحفظ البكسلات."
type: docs
weight: 540
url: /ar/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

يحفظ البكسلات.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مستطيل | Rectangle | المستطيل لحفظ البكسلات إليه. |
| بكسلات | Color[] | مصفوفة البكسلات. |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


