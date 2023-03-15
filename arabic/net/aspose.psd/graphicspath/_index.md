---
title: Class GraphicsPath
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.GraphicsPath فصل. يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن توريث هذه الفئة.
type: docs
weight: 4320
url: /ar/net/aspose.psd/graphicspath/
---
## GraphicsPath class

يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن توريث هذه الفئة.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | يقوم بتهيئة مثيل جديد لملف`GraphicsPath` فئة . |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | يقوم بتهيئة مثيل جديد لملف`GraphicsPath` فئة . |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | يقوم بتهيئة مثيل جديد لملف`GraphicsPath` فئة . |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | يقوم بتهيئة مثيل جديد لملف`GraphicsPath` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | الحصول على أو تعيين حدود الكائن. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | يحصل على أرقام المسار . |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | يحصل أو يحدد أ[`FillMode`](../fillmode/) التعداد الذي يحدد كيفية الأشكال الداخلية للأشكال في هذا`GraphicsPath` ممتلئة . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | يضيف رقمًا جديدًا . |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | إضافة أرقام جديدة . |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | لإلحاق المحدد`GraphicsPath` إلى هذا المسار. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | لإلحاق المحدد`GraphicsPath` إلى هذا المسار. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | يقوم بإجراء استنساخ عميق لمسار الرسومات هذا. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | يحول كل منحنى في هذا المسار إلى سلسلة من مقاطع الخط المتصلة. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | يطبق التحويل المحدد ثم يحول كل منحنى في هذا`GraphicsPath` في تسلسل مقاطع الخط المتصلة. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | تحويل كل منحنى في هذا`GraphicsPath` في تسلسل مقاطع الخط المتصلة. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن . |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) وباستخدام المحدد[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) وباستخدام المحدد[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) وباستخدام المحدد[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة (أسفل) المخطط التفصيلي لهذا`GraphicsPath` عند رسمها مع المحدد[`Pen`](../pen/) وباستخدام المحدد[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` في منطقة المقطع المرئية للملف[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | يشير إلى ما إذا كانت النقطة المحددة متضمنة في هذا`GraphicsPath` ، باستخدام المحدد[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | يزيل شكل . |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | يزيل الأشكال . |
| [Reset](../../aspose.psd/graphicspath/reset/)() | يفرغ مسار الرسومات ويعين ملف[`FillMode`](../fillmode/) لAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | عكس ترتيب الأشكال والأشكال والنقاط في كل شكل من أشكال هذا`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | يضيف مخططًا تفصيليًا إضافيًا إلى المسار . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | يضيف مخططًا إضافيًا إلى ملف`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | يستبدل هذا`GraphicsPath` بمنحنيات تحيط بالمساحة المملوءة عندما يتم رسم هذا المسار بواسطة القلم المحدد. |

### أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. مثال ينشئ صورة جديدة ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح. أخيرًا يتم تصدير الصورة إلى تنسيق ملف Tiff.

```csharp
[C#]

// إنشاء مثيل للصورة 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // إنشاء مثيل لفئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // إنشاء مثيل لفئة الشكل
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // إضافة أشكال إلى كائن الشكل
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // إضافة كائن الشكل إلى GraphicsPath
    graphicspath.AddFigure(figure);

    // رسم المسار باستخدام كائن القلم من اللون الأسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### أنظر أيضا

* class [ObjectWithBounds](../objectwithbounds/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


