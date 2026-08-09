---
title: "الفئة LinearGradientBrush"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.LinearGradientBrush. تغلف فرشاة مع تدرج خطي. لا يمكن وراثة هذه الفئة."
type: docs
weight: 140
url: /ar/net/aspose.psd.brushes/lineargradientbrush/
---
{{< psd/tize >}}
## LinearGradientBrush class

تغلف [`Brush`](../../aspose.psd/brush/) مع تدرج خطي. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` بالمعلمات الافتراضية. اللون الابتدائي هو الأسود، اللون النهائي هو الأبيض، الزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` بالنقاط والألوان المحددة. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` بالنقاط والألوان المحددة. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` استنادًا إلى مستطيل، ألوان البداية والنهاية، وزاوية الاتجاه. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` استنادًا إلى مستطيل، ألوان البداية والنهاية، وزاوية الاتجاه. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` استنادًا إلى مستطيل، ألوان البداية والنهاية، وزاوية الاتجاه. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | يُهيئ مثيلًا جديدًا من الفئة `LinearGradientBrush` استنادًا إلى مستطيل، ألوان البداية والنهاية، وزاوية الاتجاه. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | يحصل أو يعيّن زاوية التدرج. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | يحصل أو يضبط [`Blend`](../../aspose.psd/blend/) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | يحصل أو يضبط لون التدرج النهائي. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح غاما مفعّلاً لهذه [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [InterpolationColors](../../aspose.psd.brushes/lineargradientbrush/interpolationcolors/) { get; set; } | يحصل أو يعيّن [`ColorBlend`](../../aspose.psd/colorblend/) الذي يحدد تدرجاً خطياً متعدد الألوان. |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [`Angle`](../lineargradientbrushbase/angle/) يتغير أثناء التحويلات مع هذه [`LinearGradientBrushBase`](../lineargradientbrushbase/). |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| [LinearColors](../../aspose.psd.brushes/lineargradientbrush/linearcolors/) { get; set; } | يحصل أو يضبط ألوان البداية والنهاية للتدرج. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | يحصل أو يضبط منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | يحصل أو يضبط لون التدرج الابتدائي. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | يحصل أو يضبط نسخة من [`Matrix`](../../aspose.psd/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا [`TransformBrush`](../transformbrush/). |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | يحصل أو يضبط تعداد [`WrapMode`](../../aspose.psd/wrapmode/) الذي يشير إلى وضع الالتفاف لهذا [`TransformBrush`](../transformbrush/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من الـ[`Brush`](../../aspose.psd/brush/) الحالي. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | يضرب [`Matrix`](../../aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة المحددة [`Matrix`](../../aspose.psd/matrix/) عن طريق إلحاق المصفوفة المحددة [`Matrix`](../../aspose.psd/matrix/) في البداية. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | يضرب [`Matrix`](../../aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `LinearGradientBrush` بالمصفوفة المحددة [`Matrix`](../../aspose.psd/matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | يعيد ضبط خاصية [`Transform`](../transformbrush/transform/) إلى الهوية. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تلحق الدوران إلى التحويل. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالقيم المحددة. هذه الطريقة تلحق مصفوفة التكبير إلى التحويل. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالقيم المحددة بالترتيب المحدد. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | ينشئ تدرجًا خطيًا بلون مركزي وتلاشيًا خطيًا إلى لون واحد في كلا الطرفين. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | ينشئ تدرجًا خطيًا بلون مركزي وتلاشيًا خطيًا إلى لون واحد في كلا الطرفين. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | ينشئ تلاشيًا للتدرج يعتمد على منحنى على شكل جرس. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | ينشئ تلاشيًا للتدرج يعتمد على منحنى على شكل جرس. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تلحق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### انظر أيضًا

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


