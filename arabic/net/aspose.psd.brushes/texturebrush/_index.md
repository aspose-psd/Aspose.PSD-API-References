---
title: "الفئة TextureBrush"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.TextureBrush. كل خاصية من خصائص فئة TextureBrush هي كائن Brush يستخدم صورة لملء داخل الشكل. لا يمكن وراثة هذه الفئة."
type: docs
weight: 210
url: /ar/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

كل خاصية من خصائص الفئة `TextureBrush` هي كائن [`Brush`](../../aspose.psd/brush/) يستخدم صورة لملء داخل الشكل. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class TextureBrush : TransformBrush
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة ووضع الالتفاف. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة، المستطيل المحيط، وخصائص الصورة. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | يُهيئ نسخة جديدة من الفئة `TextureBrush` التي تستخدم الصورة المحددة، وضع الالتفاف، والمستطيل المحيط. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | يحصل على كائن [`Image`](../../aspose.psd/image/) المرتبط بهذا الكائن `TextureBrush`. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | يحصل على [`ImageAttributes`](./imageattributes/) المرتبط بهذا `TextureBrush`. |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | يحصل على [`Rectangle`](../../aspose.psd/rectangle/) المرتبط بهذا `TextureBrush`. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | يحصل على قيمة تشير إلى ما إذا تم تغيير التحويلات بطريقة ما. على سبيل المثال ضبط مصفوفة التحويل أو استدعاء أي من الطرق التي تغير مصفوفة التحويل. تم تقديم الخاصية لضمان التوافق العكسي مع GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


