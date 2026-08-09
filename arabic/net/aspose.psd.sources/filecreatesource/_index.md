---
title: "الفئة FileCreateSource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Sources.FileCreateSource. تمثل مصدر ملف للإنشاء"
type: docs
weight: 6090
url: /ar/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

يمثّل مصدر ملف للإنشاء.

```csharp
public sealed class FileCreateSource : FileSource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | ينشئ مثيلاً جديداً للفئة `FileCreateSource`. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | ينشئ مثيلاً جديداً للفئة `FileCreateSource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | يحصل على مسار الملف للإنشاء. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الملف سيكون مؤقتاً. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | يحصل على حاوية الدفق. |

## أمثلة

يوضح هذا المثال استخدام فئة Font وفئة SolidBrush لرسم سلاسل نصية على سطح Image. ينشئ المثال صورة جديدة ويرسم أشكالاً باستخدام Figures و GraphicsPath.

```csharp
[C#]

//ينشئ مثيلاً من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //ينشئ ويُهيئ مثيلاً من الفئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //يمسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //ينشئ مثيلاً من Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //أنشئ مثيلاً من SolidBrush بلون أحمر
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //ارسم سلسلة نصية
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // إنشاء خيارات التصدير.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // احفظ جميع التغييرات
    image.Save("C:\\temp\\output.gif", options);
}
```

### انظر أيضًا

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


