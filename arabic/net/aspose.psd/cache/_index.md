---
title: "فئة Cache"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Cache. تحتوي على إعدادات الذاكرة المؤقتة"
type: docs
weight: 240
url: /ar/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

يحتوي على إعدادات الذاكرة المؤقتة.

```csharp
public static class Cache
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | يحصل على عدد البايتات المخصصة للقرص. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | يحصل على عدد البايتات المخصصة في الذاكرة. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | يحصل أو يضبط مجلد الذاكرة المؤقتة. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | يحصل أو يضبط مخطط الذاكرة المؤقتة المستخدم. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن تكون الأداء أعلى. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | يحصل أو يضبط الحد الأقصى للمساحة المتاحة على القرص للذاكرة المؤقتة. القيمة المحددة هي عدد الميغابايت. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | يحصل أو يضبط الحد الأقصى للذاكرة المتاحة للذاكرة المؤقتة في الذاكرة. القيمة المحددة هي عدد الميغابايت. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | يضبط إعدادات `Cache` إلى القيم الافتراضية. |

## أمثلة

هذا المثال يوضح استخدام Aspose.PSD.Cache

```csharp
[C#]

// بشكل افتراضي، يتم تعيين مجلد الذاكرة المؤقتة إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد ذاكرة مؤقتة آخر غير الافتراضي كما يلي:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// الوضع التلقائي مرن وفعال
Cache.CacheType = CacheType.Auto;

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
Cache.ExactReallocateOnly = false;

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// قم ببعض معالجة الصور كما يلي
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // بعد تنفيذ الكود أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كان جميع كائنات Aspose.PSD قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على أي كائن، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


