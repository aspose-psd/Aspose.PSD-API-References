---
title: Class FileCreateSource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Sources.FileCreateSource فصل. يمثل مصدر ملف للإنشاء .
type: docs
weight: 5590
url: /ar/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

يمثل مصدر ملف للإنشاء .

```csharp
public sealed class FileCreateSource : FileSource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | يقوم بتهيئة مثيل جديد لملف`FileCreateSource` فئة . |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | يقوم بتهيئة مثيل جديد لملف`FileCreateSource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | يحصل على مسار الملف المراد إنشاؤه . |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الملف سيكون مؤقتًا. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | يحصل على حاوية التدفق . |

### أمثلة

يوضح هذا المثال استخدام فئة Font و SolidBrush لرسم سلاسل على سطح الصورة. يقوم المثال بإنشاء صورة جديدة ورسم الأشكال باستخدام Figures و GraphicsPath

```csharp
[C#]

// ينشئ مثيلاً للصورة
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // يقوم بإنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // ينشئ مثيلاً للخط
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // أنشئ مثيلاً من SolidBrush باللون الأحمر
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // ارسم سلسلة
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // إنشاء خيارات التصدير.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // احفظ جميع التغييرات
    image.Save("C:\\temp\\output.gif", options);
}
```

### أنظر أيضا

* class [FileSource](../filesource/)
* مساحة الاسم [Aspose.PSD.Sources](../../aspose.psd.sources/)
* المجسم [Aspose.PSD](../../)


