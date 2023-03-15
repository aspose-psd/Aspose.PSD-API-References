---
title: Class TextureBrush
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Brushes.TextureBrush فصل. كل خاصية من ممتلكاتTextureBrush الطبقة هيBrush كائن يستخدم صورة لملء الجزء الداخلي للشكل. لا يمكن توريث هذه الفئة.
type: docs
weight: 210
url: /ar/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

كل خاصية من ممتلكات`TextureBrush` الطبقة هي[`Brush`](../../aspose.psd/brush/) كائن يستخدم صورة لملء الجزء الداخلي للشكل. لا يمكن توريث هذه الفئة.

```csharp
public sealed class TextureBrush : TransformBrush
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | يقوم بتهيئة مثيل جديد لملف`TextureBrush` فئة تستخدم الصورة المحددة. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | يقوم بتهيئة مثيل جديد لملف`TextureBrush` فئة تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | يقوم بتهيئة مثيل جديد لملف`TextureBrush` فئة تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | يقوم بتهيئة مثيل جديد لملف`TextureBrush` فئة تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | يقوم بتهيئة مثيل جديد لملف`TextureBrush` فئة تستخدم سمات الصورة المحددة والمستطيل المحيط والصورة. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | يقوم بتهيئة مثيل جديد لملف`TextureBrush` فئة تستخدم سمات الصورة المحددة والمستطيل المحيط والصورة. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | يقوم بتهيئة مثيل جديد لملف`TextureBrush`فئة تستخدم الصورة المحددة ووضع الالتفاف والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | يقوم بتهيئة مثيل جديد لملف`TextureBrush`فئة تستخدم الصورة المحددة ووضع الالتفاف والمستطيل المحيط. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | يحصل على ملف[`Image`](../../aspose.psd/image/) كائن مرتبط بهذا`TextureBrush` الكائن . |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | يحصل على ملف[`ImageAttributes`](./imageattributes/) المرتبطة بهذا`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | يحصل على ملف[`Rectangle`](../../aspose.psd/rectangle/) المرتبطة بهذا`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت التحولات قد تغيرت بطريقة ما. على سبيل المثال إعداد مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية للتوافق مع الإصدارات السابقة مع GDI + . |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |
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

### أنظر أيضا

* class [TransformBrush](../transformbrush/)
* مساحة الاسم [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* المجسم [Aspose.PSD](../../)


