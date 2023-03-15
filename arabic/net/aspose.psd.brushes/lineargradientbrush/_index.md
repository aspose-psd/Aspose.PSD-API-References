---
title: Class LinearGradientBrush
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Brushes.LinearGradientBrush فصل. يغلف أBrush مع تدرج خطي. لا يمكن توريث هذه الفئة.
type: docs
weight: 140
url: /ar/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

يغلف أ[`Brush`](../../aspose.psd/brush/) مع تدرج خطي. لا يمكن توريث هذه الفئة.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة مع المعلمات الافتراضية. لون البداية أسود ولون النهاية أبيض والزاوية 45 درجة والمستطيل يقع في (0،0) بحجم (1،1) . |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة بالنقاط والألوان المحددة. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة بالنقاط والألوان المحددة. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | يقوم بتهيئة مثيل جديد لملف`LinearGradientBrush` فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | الحصول على زاوية التدرج أو تعيينها . |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | يحصل أو يحدد أ[`Blend`](../../aspose.psd/blend/) التي تحدد المواضع والعوامل التي تحدد تراجعًا مخصصًا للتدرج اللوني. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | الحصول على أو تعيين لون التدرج النهائي. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان تصحيح جاما ممكّنًا لذلك[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان[`Angle`](../lineargradientbrushbase/angle/) تم تغييره أثناء التحويل مع هذا[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت التحولات قد تغيرت بطريقة ما. على سبيل المثال إعداد مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافق مع الإصدارات السابقة مع GDI + . |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | الحصول على أو تعيين منطقة مستطيلة تحدد نقطتي البداية والنهاية للتدرج. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | الحصول على أو تعيين لون تدرج البداية. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | الحصول على نسخة أو تعيينها[`Matrix`](../../aspose.psd/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا الغرض[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | يحصل أو يحدد أ[`WrapMode`](../../aspose.psd/wrapmode/) التعداد الذي يشير إلى وضع الالتفاف لهذا[`TransformBrush`](../transformbrush/) . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ استنساخًا عميقًا جديدًا للتيار[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | يضاعف[`Matrix`](../../aspose.psd/matrix/) التي تمثل التحويل الهندسي المحلي لهذا`LinearGradientBrush` حسب المحدد[`Matrix`](../../aspose.psd/matrix/) عن طريق إضافة الملف المحدد مسبقًا[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | يضاعف[`Matrix`](../../aspose.psd/matrix/) التي تمثل التحويل الهندسي المحلي لهذا`LinearGradientBrush` حسب المحدد[`Matrix`](../../aspose.psd/matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | يعيد تعيين ملف[`Transform`](../transformbrush/transform/) الخاصية للهوية . |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | مقياس التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | قياس التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | ينشئ تدرجًا خطيًا بلون مركزي وانحدار خطي إلى لون واحد على كلا الطرفين. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | ينشئ تدرجًا خطيًا بلون مركزي وانحدار خطي إلى لون واحد على كلا الطرفين. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | إنشاء انخفاض في التدرج بناءً على منحنى على شكل جرس . |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | إنشاء انخفاض في التدرج بناءً على منحنى على شكل جرس . |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### أنظر أيضا

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* مساحة الاسم [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* المجسم [Aspose.PSD](../../)


