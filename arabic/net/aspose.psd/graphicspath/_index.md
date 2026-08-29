---
title: "الفئة GraphicsPath"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.GraphicsPath. تمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن وراثة هذه الفئة"
type: docs
weight: 4790
url: /ar/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن توريث هذه الفئة.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | يقوم بتهيئة نسخة جديدة من فئة `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | يقوم بتهيئة نسخة جديدة من فئة `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | يقوم بتهيئة نسخة جديدة من فئة `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | يقوم بتهيئة نسخة جديدة من فئة `GraphicsPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | يحصل أو يعيّن حدود الكائن. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | يحصل على أشكال المسار. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | يحصل أو يعيّن تعداد [`FillMode`](../fillmode/) الذي يحدد كيفية تعبئة داخل الأشكال في هذا `GraphicsPath`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | يضيف شكلاً جديدًا. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | يضيف أشكالًا جديدة. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | يضيف `GraphicsPath` المحدد إلى هذا المسار. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | يضيف `GraphicsPath` المحدد إلى هذا المسار. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المسار الرسومي. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا `GraphicsPath` إلى سلسلة من القطع الخطية المتصلة. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | يحوّل كل منحنى في هذا `GraphicsPath` إلى سلسلة من القطع الخطية المتصلة. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `GraphicsPath` عند رسمه باستخدام [`Pen`](../pen/) المحدد وباستخدام [`Graphics`](../graphics/) المحدد. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath` في منطقة القص المرئية لـ [`Graphics`](../graphics/) المحددة. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `GraphicsPath`، باستخدام [`Graphics`](../graphics/) المحدد. |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | يزيل شكلاً. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | يزيل أشكالًا. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | يفرغ مسار الرسوم ويعيّن [`FillMode`](../fillmode/) إلى Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | يعكس ترتيب الأشكال، والرسومات، والنقاط في كل شكل من هذا `GraphicsPath`. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | يضيف مخططًا إضافيًا إلى المسار. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | يضيف مخططًا إضافيًا إلى `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | يستبدل هذا `GraphicsPath` بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد. |

## أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لرسم المسارات على السطح. أخيرًا يتم تصدير الصورة إلى تنسيق ملف Tiff.

```csharp
[C#]

//إنشاء نسخة من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء وتهيئة نسخة من فئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //إنشاء نسخة من فئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //إضافة أشكال إلى كائن Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.AddFigure(figure);

    //رسم المسار باستخدام كائن Pen بلون أسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //إنشاء نسخة من TiffOptions وضبط خصائصه المتنوعة
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### انظر أيضًا

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


