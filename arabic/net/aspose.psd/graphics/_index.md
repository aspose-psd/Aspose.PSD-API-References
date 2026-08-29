---
title: "فئة Graphics"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Graphics. تمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي"
type: docs
weight: 4780
url: /ar/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.

```csharp
public sealed class Graphics
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Graphics](graphics/)(Image) | يُهيئ نسخة جديدة من الفئة `Graphics`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | يحصل أو يضبط منطقة القص. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | يحصل أو يضبط جودة التركيب. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | يحصل على الدقة الأفقية لهذا Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | يحصل على الدقة العمودية لهذا Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | يحصل على الصورة. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | يحصل أو يضبط وضع الاستيفاء. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | يحصل أو يضبط المقياس بين وحدات العالم ووحدات الصفحة لهذا Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهة قابلة للرسم. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | يحصل أو يعيّن وضعية التنعيم. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | يحصل أو يعيّن تلميح عرض النص. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا `Graphics`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | يبدأ تخزين عمليات الرسومات التالية مؤقتًا. لن تُطبق تأثيرات الرسومات التي تُطبق لاحقًا فورًا، بل سيؤدي End Update إلى تطبيق جميع التأثيرات مرة واحدة. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | يمسح سطح الرسومات باستخدام اللون المحدد. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة بنية [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | يرسم منحنى بيزييه محدد بأربع هياكل [`Point`](../point/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | يرسم منحنى بيزييه محدد بأربع هياكل [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | يرسم منحنى بيزييه محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | يرسم سلسلة من منحنيات بيزييه من مصفوفة هياكل [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | يرسم سلسلة من منحنيات بيزييه من مصفوفة هياكل [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | يرسم منحنى كاردينال مغلق محدد بمصفوفة هياكل [`PointF`](../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | يرسم منحنى كاردينال مغلق محدد بمصفوفة هياكل [`Point`](../point/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | يرسم منحنى كاردينال مغلق محدد بمصفوفة هياكل [`PointF`](../pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة بديل افتراضي. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | يرسم منحنى كاردينال مغلق محدد بمصفوفة هياكل [`Point`](../point/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة بديل افتراضي. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../point/). |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/) باستخدام توتر محدد. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../point/) باستخدام توتر محدد. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/). يبدأ الرسم متأخرًا عن بداية المصفوفة. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../pointf/) باستخدام توتر محدد. يبدأ الرسم متأخرًا عن بداية المصفوفة. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../point/) باستخدام توتر محدد. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | يرسم إهليلجًا محددًا بهيكل حدودي [`Rectangle`](../rectangle/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | يرسم إهليلجًا معرفًا بهيكل حدودي [`RectangleF`](../rectanglef/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | يرسم إهليلجًا معرفًا بمستطيل حدودي محدد بزوج من الإحداثيات، ارتفاع، وعرض. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | يرسم إهليلجًا معرفًا بمستطيل حدودي محدد بزوج من الإحداثيات، ارتفاع، وعرض. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | يرسم الـ[`Image`](./image/)، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | يرسم الـ[`Image`](./image/)، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | يرسم الـ[`Image`](./image/)، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد بزوج من الإحداثيات. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | يرسم الـ[`Image`](./image/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بزوج من الإحداثيات. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | يرسم الصورة المحددة دون تحجيم ويقصها، إذا لزم الأمر، لتناسب المستطيل المحدد. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | يرسم خطًا يربط بين هيكلين [`Point`](../point/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | يرسم خطًا يربط بين هيكلين [`PointF`](../pointf/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | يرسم خطًا يربط النقطتين المحددتين بأزواج الإحداثيات. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | يرسم خطًا يربط النقطتين المحددتين بأزواج الإحداثيات. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [`PointF`](../pointf/). |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [`Point`](../point/). |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | يرسم [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | يرسم شكل فطيرة يُعرّف بواسطة إهليلج محدد بهيكل [`Rectangle`](../rectangle/) وخطين شعاعيين. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | يرسم شكل فطيرة يُعرّف بواسطة إهليلج محدد بهيكل [`RectangleF`](../rectanglef/) وخطين شعاعيين. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | يرسم شكل فطيرة يُعرّف بواسطة إهليلج محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | يرسم شكل فطيرة يُعرّف بواسطة إهليلج محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | يرسم مضلعًا يُعرّف بواسطة مصفوفة من هياكل [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | يرسم مضلعًا يُعرّف بواسطة مصفوفة من هياكل [`Point`](../point/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | يرسم مستطيلًا محددًا بهيكل [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | يرسم مستطيلًا محددًا بهيكل [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | يرسم مستطيلًا محددًا بأزواج الإحداثيات، العرض، والارتفاع. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | يرسم مستطيلًا محددًا بأزواج الإحداثيات، العرض، والارتفاع. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | يرسم سلسلة من المستطيلات المحددة بهياكل [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | يرسم سلسلة من المستطيلات المحددة بهياكل [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | يرسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة وباستخدام سمات التنسيق لكائن [`StringFormat`](../stringformat/) المحدد. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | يرسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة وباستخدام سمات التنسيق لكائن [`StringFormat`](../stringformat/) المحدد. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../brush/) و[`Font`](../font/) المحددة وباستخدام سمات التنسيق لكائن [`StringFormat`](../stringformat/) المحدد. |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | ينهي تخزين عمليات الرسومات في الذاكرة المؤقتة التي بدأت بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسومات السابقة مرة واحدة عند استدعاء هذه الطريقة. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | يملأ داخل منحنى السبلين القطري المغلق المحدد بمصفوفة من هياكل [`PointF`](../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | يملأ داخل منحنى السبلين القطري المغلق المحدد بمصفوفة من هياكل [`Point`](../point/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 ووضع تعبئة بديل. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | يملأ داخل منحنى السبلين القطري المغلق المحدد بمصفوفة من هياكل [`PointF`](../pointf/) باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | يملأ داخل منحنى السبلين القطري المغلق المحدد بمصفوفة من هياكل [`Point`](../point/) باستخدام وضع التعبئة المحدد. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | يملأ داخل منحنى السبلينغ الكاردينالي المغلق المحدد بواسطة مصفوفة من هياكل [`PointF`](../pointf/) باستخدام وضع التعبئة المحدد والتوتر. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | يملأ داخل منحنى السبلينغ الكاردينالي المغلق المحدد بواسطة مصفوفة من هياكل [`Point`](../point/) باستخدام وضع التعبئة المحدد والتوتر. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | يملأ داخل إهليلج محدد بواسطة مستطيل حدودي محدد بهيكل [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | يملأ داخل إهليلج محدد بواسطة مستطيل حدودي محدد بهيكل [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | يملأ داخل إهليلج محدد بواسطة مستطيل حدودي محدد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | يملأ داخل إهليلج محدد بواسطة مستطيل حدودي محدد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | يملأ داخل [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج محدد بهيكل [`RectangleF`](../rectanglef/) وخطين شعاعيين. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج محدد بهيكل [`RectangleF`](../rectanglef/) وخطين شعاعيين. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | يملأ داخل قطاع فطيرة محدد بواسطة إهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [`PointF`](../pointf/) باستخدام وضع التعبئة Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [`Point`](../point/) باستخدام وضع التعبئة Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [`PointF`](../pointf/) باستخدام وضع التعبئة المحدد. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | يملأ داخل مضلع محدد بواسطة مصفوفة من النقاط المحددة بهياكل [`Point`](../point/) باستخدام وضع التعبئة المحدد. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | يملأ داخل مستطيل محدد بهيكل [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | يملأ داخل مستطيل محدد بهيكل [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض، وارتفاع. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | يملأ داخل مجموعة من المستطيلات المحددة بهياكل [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | يملأ داخل [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | يضرب الـ [`Matrix`](../matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `Graphics` بالـ [`Matrix`](../matrix/) المحدد عن طريق إلحاق الـ [`Matrix`](../matrix/) المحدد في البداية. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | يضرب الـ [`Matrix`](../matrix/) الذي يمثل التحويل الهندسي المحلي لهذا `Graphics` بالـ [`Matrix`](../matrix/) المحدد وفقًا للترتيب المحدد. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | يعيد تعيين الخاصية [`Transform`](./transform/) إلى الهوية. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تلحق الدوران إلى التحويل. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالمقدار المحدد بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالقيم المحددة. هذه الطريقة تلحق مصفوفة التكبير إلى التحويل. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالقيم المحددة بالترتيب المحدد. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تلحق الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

## أمثلة

يستخدم هذا المثال الفئة Graphics لإنشاء أشكال بدائية على سطح الصورة. لتوضيح العملية، ينشئ المثال صورة جديدة بتنسيق PSD ويرسم أشكالًا بدائية على سطح الصورة باستخدام طرق Draw التي توفرها الفئة Graphics ثم يصدرها بتنسيق ملف PSD.

```csharp
[C#]

//إنشاء نسخة من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء وتهيئة نسخة من فئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //ارسم قوسًا بتحديد كائن Pen ذو اللون الأسود، 
    //مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //ارسم منحنى بيزيير بتحديد كائن Pen ذو اللون الأزرق ونقاط الإحداثيات.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //ارسم منحنى بتحديد كائن Pen ذو اللون الأخضر ومصفوفة من النقاط
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //ارسم إهليلجًا باستخدام كائن Pen ومستطيل يحيطه
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //ارسم خطًا 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //ارسم قطعة فطيرة
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //ارسم مضلعًا بتحديد كائن Pen ذو اللون الأحمر ومصفوفة من النقاط
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //ارسم مستطيلًا
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //ارسم نصًا باستخدام كائن SolidBrush والخط، عند نقطة محددة
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //أنشئ نسخة من PngOptions واضبط خصائصه المتنوعة
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


