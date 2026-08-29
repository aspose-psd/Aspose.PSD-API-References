---
title: "فئة Font"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Font. تُعرّف تنسيقًا معينًا للنص بما في ذلك حجم الخط ونمطه. لا يمكن وراثة هذه الفئة."
type: docs
weight: 4750
url: /ar/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط. لا يمكن توريث هذه الفئة.

```csharp
public sealed class Font
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | يُنشئ كائن `Font` جديد يستخدم الـ `Font` الموجود المحدد و تعداد [`FontStyle`](../fontstyle/). |
| [Font](font/#constructor_1)(string, float) | يُنشئ كائن `Font` جديد باستخدام حجم محدد. مجموعة الأحرف تُضبط إلى Default، ووحدة الرسومات إلى Point، ونمط الخط إلى Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | يُنشئ كائن `Font` جديد باستخدام حجم ونمط محددين. مجموعة الأحرف تُضبط إلى Default، ووحدة الرسومات إلى Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | يُنشئ كائن `Font` جديد باستخدام حجم ووحدة محددين. مجموعة الأحرف تُضبط إلى Default، والنمط يُضبط إلى Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | يُنشئ كائن `Font` جديد باستخدام حجم ونمط ووحدة محددين. مجموعة الأحرف تُضبط إلى Default، والنمط يُضبط إلى Regular. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | يُهيئ كائن `Font` جديد باستخدام حجم محدد، نمط، وحدة، ومجموعة أحرف. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` غامقًا. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | يحصل على قيمة بايت تحدد مجموعة الأحرف التي يستخدمها هذا `Font`. |
| [Italic](../../aspose.psd/font/italic/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` مائلًا. |
| [Name](../../aspose.psd/font/name/) { get; } | يحصل على اسم الوجه لهذا `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | يحصل على حجم الـ em لهذا `Font` مقاسًا بالوحدات المحددة بواسطة خاصية [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` يحدد خطًا أفقيًا عبر الخط. |
| [Style](../../aspose.psd/font/style/) { get; } | يحصل على معلومات النمط لهذا `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Font` مسطرًا. |
| [Unit](../../aspose.psd/font/unit/) { get; } | يحصل على وحدة القياس لهذا `Font`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | ينشئ نسخة عميقة مطابقة تمامًا من هذا `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | يشير إلى ما إذا كان الكائن المحدد هو `Font` ويملك نفس قيم الخصائص مثل هذا `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | يحصل على رمز التجزئة لهذا `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا `Font`. |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


