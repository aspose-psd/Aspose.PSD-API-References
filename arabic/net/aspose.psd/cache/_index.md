---
title: Class Cache
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Cache فصل. يحتوي على إعدادات ذاكرة التخزين المؤقت .
type: docs
weight: 240
url: /ar/net/aspose.psd/cache/
---
## Cache class

يحتوي على إعدادات ذاكرة التخزين المؤقت .

```csharp
public static class Cache
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | الحصول على عدد بايتات القرص المخصصة . |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | الحصول على عدد البايت المخصص في الذاكرة. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | الحصول على مجلد ذاكرة التخزين المؤقت أو تعيينه. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | الحصول على أو تعيين مخطط التخزين المؤقت المستخدم. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة ، فيجب أن يكون الأداء أعلى. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | الحصول على أو تعيين الحد الأقصى لمساحة القرص المتوفرة لذاكرة التخزين المؤقت. القيمة المحددة هي عدد ميغا بايت. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | الحصول على أو تعيين الحد الأقصى من الذاكرة المتاحة للتخزين المؤقت في الذاكرة. القيمة المحددة هي عدد ميغا بايت. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | يعين ملف`Cache` الإعدادات الافتراضية . |

### أمثلة

يوضح هذا المثال استخدام Aspose.PSD.Cache

```csharp
[C#]

// بشكل افتراضي ، يتم تعيين مجلد ذاكرة التخزين المؤقت على دليل temp المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد ذاكرة تخزين مؤقت آخر غير الافتراضي مثل ما يلي:
// Cache.CacheFolder = @ "D: \\ MyTemp" ;

string path = "C:\\temp\\image.psd";

// الوضع التلقائي مرن وفعال
Cache.CacheType = CacheType.Auto;

// القيمة الافتراضية هي 0 ، مما يعني أنه لا يوجد حد أعلى
Cache.MaxDiskSpaceForCache = 1073741824; // 1 جيجا
Cache.MaxMemoryForCache = 1073741824; // 1 جيجا

// لا يوصى بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
Cache.ExactReallocateOnly = false;

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص 
// cache عن طريق فحص الخصائص التالية
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// قم ببعض معالجة الصور على النحو التالي
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // بعد تنفيذ الكود أعلاه ، سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كان قد تم التخلص من جميع كائنات Aspose.PSD بشكل صحيح.
// في حالة نسيان استدعاء التخلص من بعض الكائنات ، فستكون قيم ذاكرة التخزين المؤقت مختلفة عن 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


