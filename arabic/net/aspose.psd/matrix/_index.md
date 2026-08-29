---
title: "فئة Matrix"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Matrix. تستبدل فئة GDI Matrix"
type: docs
weight: 5580
url: /ar/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

يستبدل مصفوفة GDI+.

```csharp
public class Matrix
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Matrix](matrix/#constructor)() | يُنشئ مثيلاً جديدًا لفئة Matrix كمصفوفة هوية. |
| [Matrix](matrix/#constructor_1)(Matrix) | ينشئ نسخة من فئة `Matrix`. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | يُنشئ مثيلاً جديدًا لفئة `Matrix` للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | يُنشئ مثيلاً جديدًا لفئة `Matrix` للتحويل الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | يُنشئ مثيلاً جديدًا لفئة `Matrix`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | يحصل على مصفوفة من القيم العائمة التي تمثل عناصر هذه `Matrix`. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | يحصل على عنصر المصفوفة في الصف الأول والعمود الأول. يمثل المقياس على المحور X. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | يحصل على عنصر المصفوفة في الصف الأول والعمود الثاني. يمثل القص على المحور Y. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | يحصل على عنصر المصفوفة في الصف الثاني والعمود الأول. يمثل القص على المحور X. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | يحصل على عنصر المصفوفة في الصف الثاني والعمود الثاني. يمثل المقياس على المحور Y. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور X. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | يحصل على عنصر المصفوفة في الصف الثالث والعمود الأول. يمثل الإزاحة على المحور Y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي هذه المثيلة. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | يحصل على نسخة من عناصر المصفوفة. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | يرجع رمز تجزئة لهذه المثيلة. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | يضرب هذه Matrix بالمصفوفة المحددة في معامل matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | يضرب هذه Matrix بالمصفوفة المحددة في معامل matrix، وبالترتيب المحدد في معامل order. |
| [Reset](../../aspose.psd/matrix/reset/)() | يعيد تعيين هذه Matrix لتحتوي على عناصر مصفوفة الهوية. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y الصفرية) لهذه Matrix بالترتيب الافتراضي (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | يطبق دورانًا باتجاه عقارب الساعة بمقدار محدد في معامل angle، حول الأصل (إحداثيات x و y الصفرية) لهذه Matrix بالترتيب المحدد. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب الافتراضي (Prepend). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | يطبق دورانًا باتجاه عقارب الساعة حول النقطة المحددة على هذه Matrix بالترتيب المحدد. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه Matrix باستخدام ترتيب (Prepend) الافتراضي. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | يطبق متجه التحجيم المحدد (scaleX و scaleY) على هذه `Matrix` باستخدام الترتيب المحدد. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | إرجاع String تمثل هذا المثيل. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | يطبق التحويل الهندسي الممثل بواسطة هذه `Matrix` على مصفوفة محددة من النقاط. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | يطبق متجه الإزاحة المحدد على هذه `Matrix` باستخدام ترتيب (Prepend) الافتراضي. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | يطبق متجه الإزاحة المحدد على هذه Matrix بالترتيب المحدد. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | يحدد ما إذا كان مصفوفتان متساويتان. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | تشير هذه flag bit إلى أن التحويل المعرّف بواسطة هذا الكائن يقوم بعكس صورة مرآة حول محور ما، مما يغيّر نظام الإحداثيات الأيمن إلى نظام إحداثيات أيسر بالإضافة إلى التحويلات التي تشير إليها flag bits الأخرى. نظام الإحداثيات الأيمن هو ذلك الذي يدور فيه المحور X الموجب عكس اتجاه عقارب الساعة ليطابق المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليمنى عندما تنظر إلى إبهامك من الطرف. نظام الإحداثيات الأيسر هو ذلك الذي يدور فيه المحور X الموجب باتجاه عقارب الساعة ليطابق المحور Y الموجب، مشابهًا لاتجاه انحناء أصابع يدك اليسرى. لا توجد طريقة رياضية لتحديد زاوية التحويل الأصلي للانعكاس أو المرآة لأن جميع زوايا الانقلاب متطابقة عند تطبيق دوران تعديل مناسب. ملاحظة: TypeFlip أُضيف بعد أن كان GENERAL_TRANSFORM متاحًا للجمهور ولم يعد من الممكن إعادة ترقيم flag bits بسهولة دون إدخال عدم توافق ثنائي في الشيفرة الخارجية. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | تشير هذه flag bit إلى أن التحويل المعرّف بواسطة هذا الكائن يقوم بدوران بزاوية عشوائية بالإضافة إلى التحويلات التي تشير إليها flag bits الأخرى. يغيّر الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه flag bit لا يمكن أن تتواجد مع الـ |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | يقوم مقياس عام بضرب طول المتجهات بمقادير مختلفة في اتجاهي x و y دون تغيير الزاوية بين المتجهات المتعامدة. هذه flag bit لا يمكن أن تتواجد مع علم TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | تشير هذه الثابت إلى أن التحويل المعرّف بواسطة هذا الكائن يقوم بتحويل عشوائي لإحداثيات الإدخال. إذا كان يمكن تصنيف هذا التحويل بأحد الثوابت المذكورة أعلاه، فسيكون النوع إما الثابت TypeIdentity أو مزيجًا من بتات flag المناسبة لمختلف تحويلات الإحداثيات التي يقوم بها هذا التحويل. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | التحويل الهوية هو التحويل الذي تكون فيه إحداثيات الخرج دائمًا هي نفسها إحداثيات الإدخال. إذا كان هذا التحويل غير التحويل الهوية، فسيكون النوع إما الثابت GENERAL_TRANSFORM أو مزيجًا من بتات flag المناسبة لمختلف تحويلات الإحداثيات التي يقوم بها هذا التحويل. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | هذه الثابت هي قناع بت لأي من بتات flag الدوران. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | هذه الثابت هي قناع بت لأي من بتات flag التحجيم. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | تشير هذه البتة flag إلى أن التحويل المحدد بواسطة هذا الكائن يقوم بدوران ربعي بضعف من 90 درجة بالإضافة إلى التحويلات المشار إليها بواسطة بتات flag الأخرى. يغير الدوران زوايا المتجهات بنفس المقدار بغض النظر عن الاتجاه الأصلي للمتجه ودون تغيير طول المتجه. هذه البتة flag لا يمكن استخدامها مع علم TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | التحويل يحرّك الإحداثيات بمقدار ثابت في x و y دون تغيير طول أو زاوية المتجهات. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | التحجيم المتساوي يضاعف طول المتجهات بنفس المقدار في اتجاهي x و y دون تغيير الزاوية بين المتجهات. هذه البتة flag لا يمكن استخدامها مع علم TypeGeneralScale. |

## ملاحظات

معظم الخوارزميات مأخوذة من AffineTransform.java الخاص بـ Sun. أسماء Java لعناصر المصفوفة المستخدمة داخليًا. خريطة من أسماء Java إلى ما يعادلها في .net مع الوصف: m00 M11 مقياس X m10 M12 قص Y m01 M21 قص X m11 M22 مقياس Y m02 M31 إزاحة X m12 M32 إزاحة Y

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


