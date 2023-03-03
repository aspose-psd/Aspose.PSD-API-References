---
title: Class Graphics
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Graphics فصل. يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.
type: docs
weight: 4310
url: /ar/net/aspose.psd/graphics/
---
## Graphics class

يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.

```csharp
public sealed class Graphics
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Graphics](graphics/)(Image) | يقوم بتهيئة مثيل جديد لملف`Graphics` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | الحصول على منطقة المقطع أو تعيينها . |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | الحصول على جودة التركيب أو تعيينها. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | يحصل على الدقة الأفقية لهذا الغرض. PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | يحصل على الدقة الرأسية لهذا Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | يحصل على الصورة . |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | الحصول على أو تحديد وضع الاستيفاء. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء بدء التحديث. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | الحصول على أو تعيين القياس بين وحدات العالم ووحدات الصفحة لهذا الغرض. PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | الحصول على أو تعيين وحدة القياس المستخدمة لإحداثيات الصفحة في Aspose.PSD.Graphics. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | الحصول على أو تحديد وضع التجانس . |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | الحصول على تلميح عرض النص أو تعيينه. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | الحصول على أو تعيين نسخة من تحويل العالم الهندسي لهذا الغرض`Graphics` . |

## طُرق

| اسم | وصف |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | يبدأ التخزين المؤقت لعمليات الرسومات التالية. لن يتم تطبيق تأثيرات الرسومات المطبقة بعد ذلك على الفور بدلاً من أن يتسبب EndUpdate في تطبيق جميع التأثيرات مرة واحدة. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | مسح سطح الرسومات باستخدام اللون المحدد. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة أ[`Rectangle`](../rectangle/)هيكل . |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة أ[`RectangleF`](../rectanglef/)هيكل . |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | يرسم قوسًا يمثل جزءًا من القطع الناقص المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | يرسم شريحة بيزير محددة بأربعة[`Point`](../point/) الهياكل . |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | يرسم شريحة بيزير محددة بأربعة[`PointF`](../pointf/) الهياكل . |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | يرسم شريحة بيزير محددة بأربعة أزواج مرتبة من الإحداثيات التي تمثل النقاط. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | رسم سلسلة من شرائح بيزيير من مصفوفة[`PointF`](../pointf/) الهياكل . |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | رسم سلسلة من شرائح بيزيير من مصفوفة[`Point`](../point/) الهياكل . |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`PointF`](../pointf/) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`Point`](../point/) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`PointF`](../pointf/) الهياكل التي تستخدم توترًا محددًا. تستخدم هذه الطريقة افتراضيًاAlternate وضع الملء . |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | يرسم شريحة أساسية مغلقة محددة بمجموعة من[`Point`](../point/) الهياكل التي تستخدم توترًا محددًا. تستخدم هذه الطريقة افتراضيًاAlternate وضع الملء . |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf/) الهياكل. تستخدم هذه الطريقة توتر افتراضي 0.5 . |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../point/) الهياكل . |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf/) الهياكل باستخدام التوتر المحدد. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../point/) الهياكل باستخدام التوتر المحدد. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf/) الهياكل. يبدأ الرسم في الإزاحة من بداية المصفوفة . تستخدم هذه الطريقة شد افتراضي 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../pointf/) الهياكل التي تستخدم توترًا محددًا. يبدأ الرسم في الإزاحة من بداية المصفوفة. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../point/) الهياكل باستخدام التوتر المحدد. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | رسم قطع ناقص محدد بإحاطة[`Rectangle`](../rectangle/)هيكل . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | رسم قطع ناقص معرّف بحدود[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | رسم شكل بيضاوي محدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات وارتفاع وعرض . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | رسم شكل بيضاوي محدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات وارتفاع وعرض . |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | رسم ملف[`Image`](./image/) ، باستخدام حجمه الفعلي الأصلي ، في الموقع المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | رسم ملف[`Image`](./image/) ، باستخدام حجمه الفعلي الأصلي ، في الموقع المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | رسم ملف[`Image`](./image/) ، باستخدام حجمه الفعلي الأصلي ، في الموقع المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | يرسم الصورة المحددة ، باستخدام حجمها المادي الأصلي ، في الموقع المحدد بواسطة زوج إحداثيات . |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | رسم الجزء المحدد من*image* في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | رسم ملف[`Image`](./image/) في الموقع المحدد وبالحجم المحدد. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | رسم صورة محددة باستخدام حجمها الفعلي الأصلي في مكان محدد. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | رسم صورة محددة باستخدام حجمها الفعلي الأصلي في مكان محدد. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | يرسم الصورة المحددة باستخدام حجمها المادي الأصلي في الموقع المحدد بواسطة زوج إحداثيات . |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | رسم صورة محددة باستخدام حجمها الفعلي الأصلي في مكان محدد. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | يرسم الصورة المحددة دون تغيير الحجم ويقطعها ، إذا لزم الأمر ، لتلائم المستطيل المحدد. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | يرسم خطًا يربط بين اثنين[`Point`](../point/) الهياكل . |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | يرسم خطًا يربط بين اثنين[`PointF`](../pointf/) الهياكل . |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | يرسم خطًا يربط بين النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | يرسم خطًا يربط بين النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | يرسم سلسلة من مقاطع الخطوط التي تربط صفيفًا من ملفات[`PointF`](../pointf/) الهياكل . |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | يرسم سلسلة من مقاطع الخطوط التي تربط صفيفًا من ملفات[`Point`](../point/) الهياكل . |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | رسم أ[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | يرسم شكل دائري معرف بقطع ناقص محدد بواسطة[`Rectangle`](../rectangle/) هيكل وخطين شعاعي. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | يرسم شكل دائري معرف بقطع ناقص محدد بواسطة[`RectangleF`](../rectanglef/) هيكل وخطين شعاعي. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | يرسم شكل دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج إحداثيات ، وعرض ، وارتفاع ، وخطين نصف قطريين. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | يرسم شكل دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج إحداثيات ، وعرض ، وارتفاع ، وخطين نصف قطريين. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | يرسم مضلعًا محددًا بمصفوفة من[`PointF`](../pointf/) الهياكل . |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | يرسم مضلعًا محددًا بمصفوفة من[`Point`](../point/) الهياكل . |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | يرسم مستطيلاً محدداً ب[`Rectangle`](../rectangle/)هيكل . |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | يرسم مستطيلاً محدداً ب[`RectangleF`](../rectanglef/)هيكل . |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | رسم مستطيل محدد بواسطة زوج إحداثيات وعرض وارتفاع. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | رسم مستطيل محدد بواسطة زوج إحداثيات وعرض وارتفاع. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | يرسم سلسلة من المستطيلات المحددة بواسطة[`RectangleF`](../rectanglef/) الهياكل . |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | يرسم سلسلة من المستطيلات المحددة بواسطة[`Rectangle`](../rectangle/) الهياكل . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush/) و[`Font`](../font/) الكائنات . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../brush/) و[`Font`](../font/) الكائنات . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush/) و[`Font`](../font/) الكائنات . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush/) و[`Font`](../font/) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../brush/) و[`Font`](../font/) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../brush/) و[`Font`](../font/) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | إنهاء التخزين المؤقت لعمليات الرسومات التي بدأت بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسومات السابقة مرة واحدة عند استدعاء هذه الطريقة. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`PointF`](../pointf/) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`Point`](../point/) الهياكل. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 وAlternate وضع الملء . |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`PointF`](../pointf/) الهياكل باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة توتر افتراضي 0.5 . |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`Point`](../point/) الهياكل باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة توتر افتراضي 0.5 . |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`PointF`](../pointf/) الهياكل باستخدام وضع التعبئة والتوتر المحدد. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | يملأ الجزء الداخلي لمنحنى العمود الفقري الأساسي المحدد بواسطة مصفوفة من[`Point`](../point/) الهياكل باستخدام وضع التعبئة والتوتر المحدد. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة[`Rectangle`](../rectangle/)هيكل . |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة[`RectangleF`](../rectanglef/)هيكل . |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | يملأ الجزء الداخلي من القطع الناقص المحدد بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات والعرض والارتفاع. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | يملأ الجزء الداخلي من أ[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة[`RectangleF`](../rectanglef/) هيكل وخطين شعاعي. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة[`RectangleF`](../rectanglef/) هيكل وخطين شعاعي. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج من الإحداثيات والعرض والارتفاع وخطين نصف قطريين. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | يملأ الجزء الداخلي لقسم دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج من الإحداثيات والعرض والارتفاع وخطين نصف قطريين. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`PointF`](../pointf/) الهياكل وAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`Point`](../point/) الهياكل وAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`PointF`](../pointf/) الهياكل باستخدام وضع التعبئة المحدد. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | يملأ الجزء الداخلي من المضلع المحدد بواسطة مصفوفة من النقاط المحددة بواسطة[`Point`](../point/) الهياكل باستخدام وضع التعبئة المحدد. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة أ[`Rectangle`](../rectangle/)هيكل . |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة أ[`RectangleF`](../rectanglef/)هيكل . |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع . |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | يملأ الجزء الداخلي من المستطيل المحدد بواسطة زوج من الإحداثيات والعرض والارتفاع . |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | يملأ الأجزاء الداخلية لسلسلة من المستطيلات المحددة بواسطة[`RectangleF`](../rectanglef/) الهياكل . |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | يملأ الأجزاء الداخلية لسلسلة من المستطيلات المحددة بواسطة[`Rectangle`](../rectangle/) الهياكل . |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | يملأ الجزء الداخلي من أ[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | يضاعف[`Matrix`](../matrix/) التي تمثل التحويل الهندسي المحلي لهذا`Graphics` حسب المحدد[`Matrix`](../matrix/) عن طريق إضافة الملف المحدد مسبقًا[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | يضاعف[`Matrix`](../matrix/) التي تمثل التحويل الهندسي المحلي لهذا`Graphics` حسب المحدد[`Matrix`](../matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | يعيد تعيين ملف[`Transform`](./transform/) الخاصية للهوية . |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | مقياس التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | قياس التحويل الهندسي المحلي بالمقادير المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

### أمثلة

يستخدم هذا المثال فئة الرسومات لإنشاء أشكال بدائية على سطح الصورة. لتوضيح العملية ، يقوم المثال بإنشاء صورة جديدة بتنسيق PSD ورسم أشكال بدائية على سطح الصورة باستخدام طرق الرسم التي تعرضها فئة الرسومات ثم تصديرها إلى تنسيق ملف PSD.

```csharp
[C#]

// إنشاء مثيل للصورة 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // ارسم قوسًا بتحديد كائن القلم ذي اللون الأسود ، 
    // أ مستطيل يحيط بالقوس وزاوية البدء وزاوية المسح
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // ارسم بيزير عن طريق تحديد كائن القلم ذي اللون الأزرق ونقاط التنسيق.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // ارسم منحنى عن طريق تحديد كائن القلم ذي اللون الأخضر ومجموعة من النقاط
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // ارسم شكلًا ناقصًا باستخدام كائن القلم والمستطيل المحيط
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //ارسم خطا 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // ارسم مقطع دائري
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // ارسم مضلعًا بتحديد كائن القلم ذي اللون الأحمر ومجموعة من النقاط
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // ارسم مستطيلاً
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    // إنشاء كائن SolidBrush وضبط خصائصه المختلفة
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // ارسم سلسلة باستخدام SolidBrush الكائن والخط ، في نقطة معينة
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    // قم بإنشاء مثيل لـ PngOptions وقم بتعيين خصائصه المختلفة
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


