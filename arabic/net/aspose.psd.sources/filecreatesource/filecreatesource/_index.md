---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ FileCreateSource. يهيئ نسخة جديدة من الفئة FileCreateSource"
type: docs
weight: 10
url: /ar/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

تهيئ نسخة جديدة من الفئة [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لإنشائه. |

## أمثلة

هذا المثال ينشئ ملف Image جديد في موقع على القرص كما هو محدد بواسطة خاصية Source في كائن BmpOptions. إذا لم يتم تمرير المعامل الثاني إلى منشئ FileCreateSource، فسيكون الملف الذي سيتم إنشاؤه افتراضيًا لديه الخاصية IsTemporal مضبوطة على True. عندما تكون IsTemporal مضبوطة على True، لن يتم حفظ أي ملف على القرص في نهاية التنفيذ.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//ينشئ مثيلاً من PsdOptions ويضبط خصائصه المتنوعة.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//إنشاء مثال من FileCreateSource وتعيينه كـ Source لكائن PsdOptions
//إذا لم يتم تمرير المعامل الثاني، فسيكون الملف افتراضيًا لديه IsTemporal مضبوطة على True.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//ينشئ نسخة من Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

### انظر أيضًا

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

تهيئ نسخة جديدة من الفئة [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لإنشائه. |
| isTemporal | Boolean | إذا تم ضبطه على `true` فإن الملف الذي تم إنشاؤه سيكون مؤقتًا. |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


