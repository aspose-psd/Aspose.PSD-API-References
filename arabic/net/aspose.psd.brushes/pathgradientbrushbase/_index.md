---
title: Class PathGradientBrushBase
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Brushes.PathGradientBrushBase فصل. يمثل أBrush مع وظيفة تدرج المسار الأساسي.
type: docs
weight: 180
url: /ar/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

يمثل أ[`Brush`](../../aspose.psd/brush/) مع وظيفة تدرج المسار الأساسي.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | الحصول على أو تحديد النقطة المركزية لتدرج المسار. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | الحصول على أو تعيين نقطة التركيز لانخفاض التدرج اللوني. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | يحصل على المسار الرسومي الذي بنيت عليه هذه الفرشاة. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت التحولات قد تغيرت بطريقة ما. على سبيل المثال إعداد مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافق مع الإصدارات السابقة مع GDI + . |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | الحصول على نقاط المسار التي تم بناء هذه الفرشاة عليها. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | الحصول على نسخة أو تعيينها[`Matrix`](../../aspose.psd/matrix/) التي تحدد تحويلًا هندسيًا محليًا لهذا الغرض[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | يحصل أو يحدد أ[`WrapMode`](../../aspose.psd/wrapmode/) التعداد الذي يشير إلى وضع الالتفاف لهذا[`TransformBrush`](../transformbrush/) . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ استنساخًا عميقًا جديدًا للتيار[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | يضاعف[`Matrix`](../../aspose.psd/matrix/) التي تمثل التحويل الهندسي المحلي لهذا[`LinearGradientBrush`](../lineargradientbrush/) حسب المحدد[`Matrix`](../../aspose.psd/matrix/) عن طريق إضافة الملف المحدد مسبقًا[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | يضاعف[`Matrix`](../../aspose.psd/matrix/) التي تمثل التحويل الهندسي المحلي لهذا[`LinearGradientBrush`](../lineargradientbrush/) حسب المحدد[`Matrix`](../../aspose.psd/matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | يعيد تعيين ملف[`Transform`](../transformbrush/transform/) الخاصية للهوية . |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | مقياس التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | قياس التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### ملاحظات

لاحظ أنه عند إنشاء ملف`PathGradientBrushBase` فئة يجب أن تتم تهيئتها بنقطتين على الأقل. المسار الداخلي الذي تم إنشاؤه سيكون دائمًا رقمًا مغلقًا ، والنقطة الأخيرة تربط النقطة الأولى. هذا الشكل مليء بهذا`PathGradientBrushBase`. يطرح تطبيق GDI + ملفOutOfMemoryException عند المرور في مصفوفات فارغة أو مجموعة نقاط لها نفس الإحداثيات`PathGradientBrushBase` يطرح استثناء عندما تحتوي مجموعة النقاط على أقل من نقطتين ، فإنArgumentException is تم إلقاؤها بدلاً منOutOfMemoryException عندما تكون مصفوفة النقاط غير مقبولة. يتم حساب النقطة المركزية كمركز كتلة للنقاط التي تم تمريرها افتراضيًا. يمكن للمستخدم تغيير هذه النقطة لاحقًا . مقياس التركيز هو نقطة فارغة (0.0 ، 0.0) افتراضيًا .

### أنظر أيضا

* class [TransformBrush](../transformbrush/)
* مساحة الاسم [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* المجسم [Aspose.PSD](../../)


