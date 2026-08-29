---
title: "الفئة PathGradientBrush"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.PathGradientBrush. تغلف كائن Brush مع تدرج. لا يمكن وراثة هذه الفئة."
type: docs
weight: 170
url: /ar/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

تغلف كائن [`Brush`](../../aspose.psd/brush/) مع تدرج. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالمسار المحدد. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | يُهيئ نسخة جديدة من الفئة `PathGradientBrush` بالنقاط المحددة ووضع الالتفاف. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | يحصل أو يضبط [`Blend`](../../aspose.psd/blend/) الذي يحدد المواقع والعوامل التي تعرف انخفاضًا مخصصًا للتدرج. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | يحصل أو يعيّن اللون في مركز تدرج المسار. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | يحصل أو يضبط نقطة التركيز لتلاشي التدرج. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | يحصل على مسار الرسومات الذي بُنيت عليه هذه الفرشاة. |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | يحصل أو يعيّن [`ColorBlend`](../../aspose.psd/colorblend/) الذي يحدد تدرجاً خطياً متعدد الألوان. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | يحصل أو يعيّن مصفوفة من الألوان التي تتطابق مع النقاط في المسار الذي يملأه هذا `PathGradientBrush`. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | ينشئ تدرجًا بلون مركزي وتلاشيًا خطيًا إلى لون محيط واحد. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | ينشئ تدرجًا بلون مركزي وتلاشيًا خطيًا إلى كل لون محيط. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدود المسار. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | ينشئ فرشاة تدرج تغير اللون بدءًا من مركز المسار إلى حدود المسار. الانتقال من لون إلى آخر يعتمد على منحنى على شكل جرس. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تلحق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

## ملاحظات

اللون المركزي هو أبيض بشكل افتراضي. يمكن للمستخدم تغيير هذه القيمة في أي وقت لاحق.

يتم تهيئة مصفوفة ألوان المحيط بعنصر واحد يحتوي على اللون الأبيض بشكل افتراضي. يمكن تغيير ألوان المحيط لاحقًا، ولكن يلزم وجود عنصر واحد على الأقل عند إعداد ألوان المحيط.

انظر إلى [`Blend`](./blend/) لمزيد من التفاصيل حول تهيئتها.

### انظر أيضًا

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


