---
title: "الفئة PathGradientBrushBase"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.PathGradientBrushBase. تمثل فرشاة ذات وظيفة تدرج مسار أساسي."
type: docs
weight: 180
url: /ar/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

تمثل [`Brush`](../../aspose.psd/brush/) ذات وظيفة تدرج مسار أساسي.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | يحصل أو يضبط نقطة المركز لتدرج المسار. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | يحصل أو يضبط نقطة التركيز لتلاشي التدرج. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | يحصل على مسار الرسومات الذي بُنيت عليه هذه الفرشاة. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | يحصل على نقاط المسار التي بُنيت عليها هذه الفرشاة. |
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

## ملاحظات

لاحظ أنه عند إنشاء الفئة `PathGradientBrushBase` يجب تهيئتها بما لا يقل عن نقطتين. المسار الداخلي الذي يتم إنشاؤه سيكون دائمًا شكلًا مغلقًا، النقطة الأخيرة تربط النقطة الأولى. يتم ملء هذا الشكل بـ `PathGradientBrushBase`. يطرح تنفيذ GDI+ استثناء OutOfMemoryException عند تمرير مصفوفات فارغة أو مجموعة نقاط لها نفس الإحداثيات. يطرح `PathGradientBrushBase` استثناءً عندما تحتوي مصفوفة النقاط على أقل من نقطتين، يتم طرح ArgumentException بدلاً من OutOfMemoryException عندما تكون مصفوفة النقاط غير مقبولة. يتم حساب نقطة المركز كقوة مركزية للنقاط الممررة بشكل افتراضي. يمكن للمستخدم تغيير هذه النقطة لاحقًا. مقياس التركيز هو نقطة فارغة (0.0, 0.0) بشكل افتراضي.

### انظر أيضًا

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


