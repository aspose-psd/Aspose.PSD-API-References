---
title: Image.Create
second_title: Aspose.PSD لمرجع .NET API
description: Image طريقة. لإنشاء صورة جديدة باستخدام خيارات الإنشاء المحددة.
type: docs
weight: 10
url: /ar/net/aspose.psd/image/create/
---
## Image.Create method

لإنشاء صورة جديدة باستخدام خيارات الإنشاء المحددة.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | خيارات الصورة . |
| width | Int32 | العرض . |
| height | Int32 | الارتفاع . |

### قيمة الإرجاع

الصورة المنشأة حديثًا .

### أمثلة

يقوم هذا المثال بإنشاء ملف صورة جديد في بعض مواقع القرص كما هو محدد بواسطة خاصية المصدر لمثيل PsdOptions. يتم تعيين العديد من الخصائص لمثيل PsdOptions قبل إنشاء الصورة الفعلية. خاصة خاصية المصدر ، التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

// أنشئ مثيلاً من PsdOptions وعيّن خصائصه المختلفة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل PsdOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// قم بإنشاء مثيل للصورة وقم بتهيئته باستخدام مثيل PsdOptions عن طريق استدعاء طريقة الإنشاء
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // القيام ببعض معالجة الصور

    // احفظ جميع التغييرات
    image.Save();
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)


