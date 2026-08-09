---
title: "Image.Create"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Image. تنشئ صورة جديدة باستخدام خيارات الإنشاء المحددة"
type: docs
weight: 10
url: /ar/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | خيارات الصورة. |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

### قيمة الإرجاع

الصورة التي تم إنشاؤها حديثًا.

## أمثلة

هذا المثال ينشئ ملف Image جديد في موقع على القرص كما هو محدد بخصية Source لكائن PsdOptions. يتم تعيين عدة خصائص لكائن PsdOptions قبل إنشاء الصورة الفعلية. خاصة خاصية Source التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

//إنشاء مثال من PsdOptions وتعيين خصائصه المتنوعة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//إنشاء مثال من FileCreateSource وتعيينه كـ Source لكائن PsdOptions
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//إنشاء مثال من Image وتهيئته بمثال من PsdOptions عن طريق استدعاء طريقة Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات
    image.Save();
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


