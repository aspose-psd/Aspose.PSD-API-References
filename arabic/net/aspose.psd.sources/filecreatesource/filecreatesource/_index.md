---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD لمرجع .NET API
description: FileCreateSource البناء. يقوم بتهيئة مثيل جديد لملفFileCreateSource فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`FileCreateSource`](../) فئة .

```csharp
public FileCreateSource(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف المراد إنشاؤه. |

### أمثلة

يقوم هذا المثال بإنشاء ملف صورة جديد في موقع ما على القرص كما هو محدد بواسطة خاصية المصدر لمثيل BmpOptions. إذا لم يتم تمرير المعلمة الثانية إلى مُنشئ FileCreateSource ، فسيتم تعيين الخاصية IsTemporal بشكل افتراضي على True. مع ضبط IsTemporal على True ، لن يتم حفظ أي ملف على القرص في نهاية التنفيذ.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
// ينشئ مثيلاً من PsdOptions ويضبط خصائصه المختلفة
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل PsdOptions
// إذا لم يتم تمرير المعلمة الثانية ، فسيتم تعيين الملف بشكل افتراضي على IsTemporal إلى True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

// ينشئ مثيلاً للصورة 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // القيام ببعض معالجة الصور
}
```

### أنظر أيضا

* class [FileCreateSource](../)
* مساحة الاسم [Aspose.PSD.Sources](../../filecreatesource/)
* المجسم [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`FileCreateSource`](../) فئة .

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف المراد إنشاؤه. |
| isTemporal | Boolean | إذا تم التعيين على`حقيقي` سيكون الملف الذي تم إنشاؤه مؤقتًا. |

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

* class [FileCreateSource](../)
* مساحة الاسم [Aspose.PSD.Sources](../../filecreatesource/)
* المجسم [Aspose.PSD](../../../)


