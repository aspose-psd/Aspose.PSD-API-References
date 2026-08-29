---
title: "الفئة LinearMulticolorGradientBrush"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.LinearMulticolorGradientBrush. تمثّل فرشاة بتدرج خطي معرف بعدة ألوان ومواقع مناسبة. لا يمكن وراثة هذه الفئة"
type: docs
weight: 160
url: /ar/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

تمثّل [`Brush`](../../aspose.psd/brush/) بتدرج خطي معرف بعدة ألوان ومواقع مناسبة. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بالمعلمات الافتراضية. اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة، والمستطيل يقع في (0,0) بحجم (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بالنقاط المحددة. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بالنقاط المحددة. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بناءً على مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بناءً على مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بناءً على مستطيل وزاوية توجيه. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | ينشئ مثلاً جديداً من الفئة `LinearMulticolorGradientBrush` بناءً على مستطيل وزاوية توجيه. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | يحصل أو يعيّن زاوية التدرج. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح غاما مفعّلاً لهذه [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | يحصل أو يعيّن [`ColorBlend`](../../aspose.psd/colorblend/) الذي يحدد تدرجاً خطياً متعدد الألوان. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [`Angle`](../lineargradientbrushbase/angle/) يتغير أثناء التحويلات مع هذه [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | يحصل أو يضبط منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | يحصل أو يضبط نسخة من [`Matrix`](../../aspose.psd/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | يحصل أو يضبط تعداد [`WrapMode`](../../aspose.psd/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [`TransformBrush`](../transformbrush/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من الـ[`Brush`](../../aspose.psd/brush/) الحالي. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | يضرب الـ[`Matrix`](../../aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [`LinearGradientBrush`](../lineargradientbrush/) بالمصفوفة المحددة [`Matrix`](../../aspose.psd/matrix/) عن طريق إلحاق المصفوفة المحددة في المقدمة. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | يضرب الـ[`Matrix`](../../aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [`LinearGradientBrush`](../lineargradientbrush/) بالمصفوفة المحددة [`Matrix`](../../aspose.psd/matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | يعيد ضبط خاصية [`Transform`](../transformbrush/transform/) إلى الهوية. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تلحق الدوران إلى التحويل. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالقيم المحددة. هذه الطريقة تلحق مصفوفة التكبير إلى التحويل. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالقيم المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تلحق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### انظر أيضًا

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


