---
title: "Graphics"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي."
type: docs
weight: 49
url: /ar/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | ينشئ مثيلًا جديدًا لفئة  Graphics  . |
## الحقول

| حقل | الوصف |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | يحصل على معامل حجم نمط النص الغامق |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | يحصل على معامل حجم نمط النص المائل |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | يطبق التأثير. |
| [beginUpdate()](#beginUpdate--) | يبدأ التخزين المؤقت للعمليات الرسومية التالية. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | يمسح سطح الرسومات باستخدام اللون المحدد. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية  Rectangle  . |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية  RectangleF  . |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | يرسم منحنى بيزيير محدد بأربع بنى  Point  . |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | يرسم منحنى بيزيير محدد بأربع بنى  PointF  . |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | يرسم منحنى بيزيير محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | يرسم سلسلة من منحنيات بيزيير من مصفوفة بنى  PointF  . |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | يرسم سلسلة من منحنيات بيزيير من مصفوفة بنى  Point  . |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | يرسم منحنى كاردينال مغلق محدد بمصفوفة بنى  PointF  . |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل PointF باستخدام توتر محدد. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل Point. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل Point باستخدام توتر محدد. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF باستخدام توتر محدد. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF باستخدام توتر محدد. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل Point. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل Point باستخدام توتر محدد. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل Point باستخدام توتر محدد. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | يرسم قطعًا ناقصًا محددًا بهيكل Rectangle كحدود. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | يرسم قطعًا ناقصًا معرفًا بهيكل RectangleF كحدود. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | يرسم قطعًا ناقصًا معرفًا بمستطيل حدود يحدده زوج من الإحداثيات، والارتفاع، والعرض. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | يرسم قطعًا ناقصًا معرفًا بمستطيل حدود يحدده زوج من الإحداثيات، والارتفاع، والعرض. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد بواسطة زوج من الإحداثيات. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | يرسم الصورة المحددة دون تحجيم ويقصها إذا لزم الأمر لتناسب المستطيل المحدد. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | يرسم خطًا يربط بين هيكلين Point. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | يرسم خطًا يربط بين هيكلين PointF. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل PointF. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل Point. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | يرسم كائن com.aspose.psd.graphicsPath. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | يرسم شكل فطيرة معرفًا بقطع ناقص محدد بهيكل Rectangle وخطين شعاعيين. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | يرسم شكل فطيرة معرفًا بقطع ناقص محدد بهيكل RectangleF وخطين شعاعيين. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | يرسم شكل فطيرة معرفًا بواسطة إهليلج محدد بواسطة زوج إحداثيات، وعرض، وارتفاع، وخطين شعاعيين. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | يرسم شكل فطيرة معرفًا بواسطة إهليلج محدد بواسطة زوج إحداثيات، وعرض، وارتفاع، وخطين شعاعيين. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | يرسم مضلعًا معرفًا بمصفوفة من هياكل  PointF . |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | يرسم مضلعًا معرفًا بمصفوفة من هياكل  Point . |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | يرسم مستطيلًا محددًا بهيكل  Rectangle . |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | يرسم مستطيلًا محددًا بهيكل  RectangleF . |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | يرسم مستطيلًا محددًا بواسطة زوج إحداثيات، وعرض، وارتفاع. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | يرسم مستطيلًا محددًا بواسطة زوج إحداثيات، وعرض، وارتفاع. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | يرسم سلسلة من المستطيلات المحددة بهياكل  RectangleF . |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | يرسم سلسلة من المستطيلات المحددة بهياكل  Rectangle . |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  المحددة. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  المحددة. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | يرسم سلسلة النص المحددة بطريقة متوافقة مع Adobe في المستطيل المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | يرسم سلسلة النص المحددة بطريقة متوافقة مع Adobe في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font . |
| [endUpdate()](#endUpdate--) | ينهي تخزين عمليات الرسومات في الذاكرة المؤقتة التي بدأت بعد استدعاء BeginUpdate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.PointF . |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.PointF  باستخدام وضع التعبئة المحدد. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.PointF  باستخدام وضع التعبئة المحدد والتوتر. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.Point . |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.Point  باستخدام وضع التعبئة المحدد. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.Point  باستخدام وضع التعبئة المحدد والتوتر. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | يملأ داخل إهليلج معرف بمستطيل حد يحدده هيكل  com.aspose.psd.Rectangle . |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | يملأ داخل إهليلج معرف بمستطيل حد يحدده هيكل  com.aspose.psd.RectangleF . |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | يملأ داخل إهليلج معرف بمستطيل حد يحدده زوج من الإحداثيات، وعرض، وارتفاع. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | يملأ داخل إهليلج معرف بمستطيل حد يحدده زوج من الإحداثيات، وعرض، وارتفاع. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | يملأ داخل  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة بنية  com.aspose.psd.RectangleF  وخطين شعاعيين. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة بنية  com.aspose.psd.RectangleF  وخطين شعاعيين. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.PointF  و  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.PointF  باستخدام وضع التعبئة المحدد. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.Point  و  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.Point  باستخدام وضع التعبئة المحدد. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | يملأ داخل مستطيل محدد بواسطة بنية  Rectangle . |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | يملأ داخل مستطيل محدد بواسطة بنية  RectangleF . |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | يملأ داخل سلسلة من المستطيلات المحددة بواسطة هياكل  RectangleF . |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | يملأ داخل سلسلة من المستطيلات المحددة بواسطة هياكل  Rectangle . |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | يملأ داخل  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | يحصل أو يضبط منطقة القص. |
| [getCompositingQuality()](#getCompositingQuality--) | يحصل أو يضبط جودة التركيب. |
| [getDpiX()](#getDpiX--) | يحصل على الدقة الأفقية لهذا  com.aspose.psd.graphics . |
| [getDpiY()](#getDpiY--) | يحصل على الدقة العمودية لهذا  com.aspose.psd.graphics . |
| [getImage()](#getImage--) | يحصل على الصورة. |
| [getInterpolationMode()](#getInterpolationMode--) | يحصل أو يضبط وضع الاستيفاء. |
| [getPageScale()](#getPageScale--) | يحصل أو يضبط التحجيم بين وحدات العالم ووحدات الصفحة لهذا  com.aspose.psd.graphics . |
| [getPageUnit()](#getPageUnit--) | يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا  com.aspose.psd.graphics . |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهية قابلة للرسم. |
| [getSmoothingMode()](#getSmoothingMode--) | يحصل أو يضبط وضع التنعيم. |
| [getTextRenderingHint()](#getTextRenderingHint--) | يحصل أو يضبط تلميح عرض النص. |
| [getTransform()](#getTransform--) | يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | يقيس السلسلة باستخدام الفئة [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | يقيس السلسلة. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | يقيس سلسلة النص المحددة باستخدام المعلمات المحددة |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | يضرب الـ com.aspose.psd.Matrix الذي يمثل التحويل الهندسي المحلي لهذا com.aspose.psd.Graphics بالمصفوفة com.aspose.psd.Matrix المحددة عن طريق إلحاق المصفوفة com.aspose.psd.matrix المحددة في البداية. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | يضرب الـ com.aspose.psd.Matrix الذي يمثل التحويل الهندسي المحلي لهذا com.aspose.psd.Graphics بالمصفوفة com.aspose.psd.Matrix المحددة وفقًا للترتيب المحدد. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | يعيد تعيين خاصية com.aspose.psd.graphics.Transform إلى الهوية. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالمقدار المحدد. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفق الترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتحجيم التحويل الهندسي المحلي بالمقاسات المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتحجيم التحويل الهندسي المحلي بالمقاسات المحددة وفق الترتيب المحدد. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | يحصل أو يضبط منطقة القص. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | يحصل أو يضبط جودة التركيب. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | يحصل أو يضبط وضع الاستيفاء. |
| [setPageScale(float value)](#setPageScale-float-) | يحصل أو يضبط التحجيم بين وحدات العالم ووحدات الصفحة لهذا  com.aspose.psd.graphics . |
| [setPageUnit(int value)](#setPageUnit-int-) | يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا  com.aspose.psd.graphics . |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهية قابلة للرسم. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | يحصل أو يضبط وضع التنعيم. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | يحصل أو يضبط تلميح عرض النص. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


ينشئ مثيلًا جديدًا لفئة  Graphics  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | صورة المصدر. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


يحصل على معامل حجم نمط النص الغامق

استخدام أرقام سحرية لأن GDI يوفر القياس دائمًا فقط للنمط العادي.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


يحصل على معامل حجم نمط النص المائل

استخدام أرقام سحرية لأن GDI يوفر القياس دائمًا فقط للنمط العادي.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


يطبق التأثير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تأثير | com.aspose.internal.IEffect | التأثير المراد تطبيقه. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


يبدأ تخزين عمليات الرسوميات التالية في الذاكرة المؤقتة. لن يتم تطبيق تأثيرات الرسوميات التي تُطبق بعد ذلك فورًا، بل سيتسبب EndUpdate في تطبيق جميع التأثيرات مرة واحدة.

لاحظ أن التأثيرات بعد استدعاء BeginUpdate لن تُطبق إذا لم يتم استدعاء EndUpdate.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


يمسح سطح الرسومات باستخدام اللون المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | اللون المستخدم لمسح سطح الرسوميات. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية  Rectangle  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للقوس. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية RectangleF التي تحدد حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweepAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى نقطة النهاية للقوس. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية  RectangleF  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للقوس. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية RectangleF التي تحدد حدود القطع الناقص. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweepAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى نقطة النهاية للقوس. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للقوس. |
| س | float | الإحداثي x للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص. |
| ص | float | الإحداثي y للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص. |
| العرض | float | عرض المستطيل الذي يحدد القطع الناقص. |
| الارتفاع | float | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweepAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى نقطة النهاية للقوس. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للقوس. |
| س | int | الإحداثي x للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص. |
| ص | int | الإحداثي y للزاوية العليا اليسرى للمستطيل الذي يحدد القطع الناقص. |
| العرض | int | عرض المستطيل الذي يحدد القطع الناقص. |
| الارتفاع | int | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| startAngle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweepAngle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى نقطة النهاية للقوس. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


يرسم منحنى بيزيير محدد بأربع بنى  Point  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | بنية Pen التي تحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [Point](../../com.aspose.psd/point) | Point  structure التي تمثل نقطة البداية للمنحنى. |
| pt2 | [Point](../../com.aspose.psd/point) | Point  structure التي تمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [Point](../../com.aspose.psd/point) | Point  structure التي تمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [Point](../../com.aspose.psd/point) | Point  structure التي تمثل نقطة النهاية للمنحنى. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


يرسم منحنى بيزيير محدد بأربع بنى  PointF  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  التي تحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  structure التي تمثل نقطة البداية للمنحنى. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  structure التي تمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  structure التي تمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  structure التي تمثل نقطة النهاية للمنحنى. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


يرسم منحنى بيزيير محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  التي تحدد اللون والعرض والنمط للمنحنى. |
| x1 | float | الإحداثي السيني لنقطة البداية للمنحنى. |
| y1 | float | الإحداثي الصادي لنقطة البداية للمنحنى. |
| x2 | float | الإحداثي السيني لنقطة التحكم الأولى للمنحنى. |
| y2 | float | الإحداثي الصادي لنقطة التحكم الأولى للمنحنى. |
| x3 | float | الإحداثي السيني لنقطة التحكم الثانية للمنحنى. |
| y3 | float | الإحداثي الصادي لنقطة التحكم الثانية للمنحنى. |
| x4 | float | الإحداثي السيني لنقطة النهاية للمنحنى. |
| y4 | float | الإحداثي الصادي لنقطة النهاية للمنحنى. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


يرسم سلسلة من منحنيات بيزيير من مصفوفة بنى  PointF  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  التي تحدد اللون والعرض والنمط للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تمثل النقاط التي تحدد المنحنى. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


يرسم سلسلة من منحنيات بيزيير من مصفوفة بنى  Point  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  التي تحدد اللون والعرض والنمط للمنحنى. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل  Point  التي تمثل النقاط التي تحدد المنحنى. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل  PointF . تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 و وضع تعبئة  FillMode.Alternate .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تحدد المنحنى. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل  PointF  باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي  FillMode.Alternate .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تحدد المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل  Point . تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 و وضع تعبئة  FillMode.Alternate .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل  Point  التي تحدد المنحنى. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل  Point  باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي  FillMode.Alternate .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل  Point  التي تحدد المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل  PointF . تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تحدد المنحنى. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF باستخدام توتر محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تمثل النقاط التي تحدد المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل  PointF . يبدأ الرسم بإزاحة من بداية المصفوفة. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تحدد المنحنى. |
| الإزاحة | int | إزاحة من العنصر الأول في مصفوفة المعامل  points  إلى نقطة البداية في المنحنى. |
| numberOfSegments | int | عدد القطاعات بعد نقطة البداية لتضمينها في المنحنى. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل  PointF  باستخدام توتر محدد. يبدأ الرسم بإزاحة من بداية المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل  PointF  التي تحدد المنحنى. |
| الإزاحة | int | إزاحة من العنصر الأول في مصفوفة المعامل  points  إلى نقطة البداية في المنحنى. |
| numberOfSegments | int | عدد القطاعات بعد نقطة البداية لتضمينها في المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل Point.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل  Point  التي تحدد المنحنى. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل Point باستخدام توتر محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل  Point  التي تحدد المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل Point باستخدام توتر محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل  Point  التي تحدد المنحنى. |
| الإزاحة | int | إزاحة من العنصر الأول في مصفوفة المعامل  points  إلى نقطة البداية في المنحنى. |
| numberOfSegments | int | عدد القطاعات بعد نقطة البداية لتضمينها في المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


يرسم قطعًا ناقصًا محددًا بهيكل Rectangle كحدود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والنمط للبيضاوية. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل  Rectangle  الذي يحدد حدود البيضاوية. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


يرسم قطعًا ناقصًا معرفًا بهيكل RectangleF كحدود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والنمط للبيضاوية. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية RectangleF التي تحدد حدود القطع الناقص. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


يرسم قطعًا ناقصًا معرفًا بمستطيل حدود يحدده زوج من الإحداثيات، والارتفاع، والعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والنمط للبيضاوية. |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| العرض | float | عرض المستطيل المحيط الذي يحدد البيضاوية. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد البيضاوية. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


يرسم قطعًا ناقصًا معرفًا بمستطيل حدود يحدده زوج من الإحداثيات، والارتفاع، والعرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  يحدد اللون والعرض والنمط للبيضاوية. |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| العرض | int | عرض المستطيل المحيط الذي يحدد البيضاوية. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد البيضاوية. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| point | [Point](../../com.aspose.psd/point) | بنية Point التي تمثل موقع الزاوية العلوية اليسرى للصورة المرسومة. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| point | [PointF](../../com.aspose.psd/pointf) | بنية PointF التي تمثل الزاوية العلوية اليسرى للصورة المرسومة. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل المصدر. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل المصدر. |
| srcUnit | int | وحدات القياس. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل المصدر. |
| srcUnit | int | وحدات القياس. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | سمات الصورة. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المصدر. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المصدر. |
| srcUnit | int | وحدات القياس. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


يرسم الجزء المحدد من الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة التي سيتم رسمها. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من ثلاث بنى PointF تُحدد متوازي أضلاع. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المصدر. |
| srcUnit | int | وحدات القياس. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | سمات الصورة. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية Rectangle التي تحدد موقع وحجم الصورة المرسومة. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المصدر. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل المصدر. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | سمات الصورة. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | سمات الصورة. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية RectangleF التي تحدد موقع وحجم الصورة المرسومة. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل المصدر. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل المصدر. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات المستخدمة. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | سمات الصورة المستخدمة. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الوجهة. |
| graphicsUnit | int | وحدة الرسومات. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الوجهة الذي سيتم الرسم فيه. |
| graphicsUnit | int | وحدة الرسومات. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | سمات الصورة. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| س | float | الإحداثي السيني للزاوية العلوية اليسرى للصورة المرسومة. |
| ص | float | الإحداثي الصادي للزاوية العلوية اليسرى للصورة المرسومة. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| س | float | الإحداثي السيني للزاوية العلوية اليسرى للصورة المرسومة. |
| ص | float | الإحداثي الصادي للزاوية العلوية اليسرى للصورة المرسومة. |
| العرض | float | عرض الصورة المرسومة. |
| الارتفاع | float | ارتفاع الصورة المرسومة. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد بواسطة زوج من الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| س | int | الإحداثي السيني للزاوية العلوية اليسرى للصورة المرسومة. |
| ص | int | الإحداثي الصادي للزاوية العلوية اليسرى للصورة المرسومة. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


يرسم الصورة المحددة في الموقع المحدد وبالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| س | int | الإحداثي السيني للزاوية العلوية اليسرى للصورة المرسومة. |
| ص | int | الإحداثي الصادي للزاوية العلوية اليسرى للصورة المرسومة. |
| العرض | int | عرض الصورة المرسومة. |
| الارتفاع | int | ارتفاع الصورة المرسومة. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| point | [Point](../../com.aspose.psd/point) | بنية Point التي تحدد الزاوية العلوية اليسرى للصورة المرسومة. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle التي تحدد الزاوية العلوية اليسرى للصورة المرسومة. خصائص X و Y للـ Rectangle تحدد الزاوية العلوية اليسرى. خصائص Width و Height يتم تجاهلها. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| س | int | الإحداثي السيني للزاوية العلوية اليسرى للصورة المرسومة. |
| ص | int | الإحداثي الصادي للزاوية العلوية اليسرى للصورة المرسومة. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| س | int | الإحداثي السيني للزاوية العلوية اليسرى للصورة المرسومة. |
| ص | int | الإحداثي الصادي للزاوية العلوية اليسرى للصورة المرسومة. |
| العرض | int | المعامل غير مستخدم. |
| الارتفاع | int | المعامل غير مستخدم. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


يرسم الصورة المحددة دون تحجيم ويقصها إذا لزم الأمر لتناسب المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الذي تُرسم فيه الصورة. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


يرسم خطًا يربط بين هيكلين Point.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للخط. |
| point1 | [Point](../../com.aspose.psd/point) | بنية Point التي تمثل النقطة الأولى للاتصال. |
| point2 | [Point](../../com.aspose.psd/point) | بنية Point التي تمثل النقطة الثانية للاتصال. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


يرسم خطًا يربط بين هيكلين PointF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للخط. |
| point1 | [PointF](../../com.aspose.psd/pointf) | بنية PointF التي تمثل النقطة الأولى للاتصال. |
| point2 | [PointF](../../com.aspose.psd/pointf) | بنية PointF التي تمثل النقطة الثانية للاتصال. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للخط. |
| x1 | float | الإحداثي السيني للنقطة الأولى. |
| y1 | float | الإحداثي الصادي للنقطة الأولى. |
| x2 | float | الإحداثي السيني للنقطة الثانية. |
| y2 | float | الإحداثي الصادي للنقطة الثانية. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للخط. |
| x1 | int | الإحداثي السيني للنقطة الأولى. |
| y1 | int | الإحداثي الصادي للنقطة الأولى. |
| x2 | int | الإحداثي السيني للنقطة الثانية. |
| y2 | int | الإحداثي الصادي للنقطة الثانية. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل PointF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من بنى PointF التي تمثل النقاط التي يجب ربطها. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل Point.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من بنى Point التي تمثل النقاط التي يجب ربطها. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


يرسم كائن com.aspose.psd.graphicsPath.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen الذي يحدد اللون والعرض والنمط للمسار. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath للرسم. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


يرسم شكل فطيرة معرفًا بقطع ناقص محدد بهيكل Rectangle وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية Rectangle التي تمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | float | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | float | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لشكل الفطيرة. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


يرسم شكل فطيرة معرفًا بقطع ناقص محدد بهيكل RectangleF وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية RectangleF التي تمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | float | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | float | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لشكل الفطيرة. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


يرسم شكل فطيرة معرفًا بواسطة إهليلج محدد بواسطة زوج إحداثيات، وعرض، وارتفاع، وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط لشكل الفطيرة. |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| العرض | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | float | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | float | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لشكل الفطيرة. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


يرسم شكل فطيرة معرفًا بواسطة إهليلج محدد بواسطة زوج إحداثيات، وعرض، وارتفاع، وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط لشكل الفطيرة. |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| العرض | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | int | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | int | زاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لشكل الفطيرة. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


يرسم مضلعًا معرفًا بمصفوفة من هياكل  PointF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للمضلع. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من  PointF  الهياكل التي تمثل رؤوس المضلع. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


يرسم مضلعًا معرفًا بمصفوفة من هياكل  Point .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم يحدد اللون والعرض والنمط للمضلع. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من  Point  الهياكل التي تمثل رؤوس المضلع. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


يرسم مستطيلًا محددًا بهيكل  Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  Pen  يحدد اللون والعرض والنمط للمستطيل. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل  Rectangle  يمثل المستطيل المراد رسمه. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


يرسم مستطيلًا محددًا بهيكل  RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  Pen  يحدد اللون والعرض والنمط للمستطيل. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل  RectangleF  يمثل المستطيل المراد رسمه. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


يرسم مستطيلًا محددًا بواسطة زوج إحداثيات، وعرض، وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  Pen  يحدد اللون والعرض والنمط للمستطيل. |
| س | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| ص | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| العرض | float | عرض المستطيل المراد رسمه. |
| الارتفاع | float | ارتفاع المستطيل المراد رسمه. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


يرسم مستطيلًا محددًا بواسطة زوج إحداثيات، وعرض، وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  Pen  يحدد اللون والعرض والنمط للمستطيل. |
| س | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| ص | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المراد رسمه. |
| العرض | int | عرض المستطيل المراد رسمه. |
| الارتفاع | int | ارتفاع المستطيل المراد رسمه. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


يرسم سلسلة من المستطيلات المحددة بهياكل  RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  Pen  يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | مصفوفة من  RectangleF  الهياكل التي تمثل المستطيلات المراد رسمها. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


يرسم سلسلة من المستطيلات المحددة بهياكل  Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | قلم  Pen  يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | مصفوفة من  Rectangle  الهياكل التي تمثل المستطيلات المراد رسمها. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  هيكل يحدد الزاوية العلوية اليسرى للنص المرسوم. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  هيكل يحدد الزاوية العلوية اليسرى للنص المرسوم. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  هيكل يحدد موقع النص المرسوم. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  هيكل يحدد موقع النص المرسوم. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| س | float | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| ص | float | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| س | float | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| ص | float | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


يرسم سلسلة النص المحددة بطريقة متوافقة مع Adobe في المستطيل المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font  مع استخدام سمات التنسيق لكائن  com.aspose.psd.stringFormat .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  هيكل يحدد موقع النص المرسوم. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  الذي يحدد سمات التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


يرسم سلسلة النص المحددة بطريقة متوافقة مع Adobe في الموقع المحدد باستخدام كائنات  com.aspose.psd.Brush  و  com.aspose.psd.Font .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | String للرسم. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  الذي يحدد اللون والملمس للنص المرسوم. |
| س | float | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| ص | float | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


ينهي تخزين عمليات الرسوميات في الذاكرة التي بدأت بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسوميات السابقة مرة واحدة عند استدعاء هذه الطريقة.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل com.aspose.psd.PointF. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 و وضع تعبئة FillMode.Alternate.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد المنحنى. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل com.aspose.psd.PointF باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد المنحنى. |
| وضع التعبئة | int | عضو في تعداد com.aspose.psd.FillMode الذي يحدد كيفية تعبئة المنحنى. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.PointF  باستخدام وضع التعبئة المحدد والتوتر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة com.aspose.psd.Brush التي تحدد خصائص التعبئة. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تحدد المنحنى. |
| وضع التعبئة | int | عضو في تعداد com.aspose.psd.FillMode الذي يحدد كيفية تعبئة المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل com.aspose.psd.Point. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 ووضع تعبئة FillMode.Alternate.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل com.aspose.psd.Point التي تحدد المنحنى. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل com.aspose.psd.Point باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل com.aspose.psd.Point التي تحدد المنحنى. |
| وضع التعبئة | int | عضو في تعداد com.aspose.psd.FillMode الذي يحدد كيفية تعبئة المنحنى. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل  com.aspose.psd.Point  باستخدام وضع التعبئة المحدد والتوتر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل com.aspose.psd.Point التي تحدد المنحنى. |
| وضع التعبئة | int | عضو في تعداد com.aspose.psd.FillMode الذي يحدد كيفية تعبئة المنحنى. |
| التوتر | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


يملأ داخل إهليلج معرف بمستطيل حد يحدده هيكل  com.aspose.psd.Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل com.aspose.psd.Rectangle الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


يملأ داخل إهليلج معرف بمستطيل حد يحدده هيكل  com.aspose.psd.RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل com.aspose.psd.RectangleF الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


يملأ داخل إهليلج معرف بمستطيل حد يحدده زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| العرض | float | عرض المستطيل المحيط الذي يحدد البيضاوية. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد البيضاوية. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


يملأ داخل إهليلج معرف بمستطيل حد يحدده زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد البيضاوية. |
| العرض | int | عرض المستطيل المحيط الذي يحدد البيضاوية. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد البيضاوية. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


يملأ داخل  com.aspose.psd.graphicsPath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath الذي يمثل المسار للتعبئة. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة بنية  com.aspose.psd.RectangleF  وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل com.aspose.psd.Rectangle الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لقطاع الفطيرة. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة بنية  com.aspose.psd.RectangleF  وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل com.aspose.psd.RectangleF الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لقطاع الفطيرة. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| العرض | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لقطاع الفطيرة. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| العرض | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل startAngle إلى الجانب الثاني لقطاع الفطيرة. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.PointF  و  FillMode.Alternate .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تمثل رؤوس المضلع للتعبئة. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.PointF  باستخدام وضع التعبئة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة من هياكل com.aspose.psd.PointF التي تمثل رؤوس المضلع للتعبئة. |
| fillMode | int | عضو في تعداد com.aspose.psd.FillMode الذي يحدد نمط التعبئة. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.Point  و  FillMode.Alternate .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل com.aspose.psd.Point التي تمثل رؤوس المضلع للتعبئة. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


يملأ داخل مضلع معرف بواسطة مصفوفة من النقاط المحددة بواسطة هياكل  com.aspose.psd.Point  باستخدام وضع التعبئة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| points | [Point\[\]](../../com.aspose.psd/point) | مصفوفة من هياكل com.aspose.psd.Point التي تمثل رؤوس المضلع للتعبئة. |
| fillMode | int | عضو في تعداد com.aspose.psd.FillMode الذي يحدد نمط التعبئة. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


يملأ داخل مستطيل محدد بواسطة بنية  Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة التي تحدد خصائص التعبئة. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية Rectangle التي تمثل المستطيل المراد ملؤه. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


يملأ داخل مستطيل محدد بواسطة بنية  RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة التي تحدد خصائص التعبئة. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية RectangleF التي تمثل المستطيل المراد ملؤه. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة التي تحدد خصائص التعبئة. |
| س | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل المراد ملؤه. |
| ص | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل المراد ملؤه. |
| العرض | float | عرض المستطيل المراد ملؤه. |
| الارتفاع | float | ارتفاع المستطيل المراد ملؤه. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، عرض وارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة التي تحدد خصائص التعبئة. |
| س | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل المراد ملؤه. |
| ص | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل المراد ملؤه. |
| العرض | int | عرض المستطيل المراد ملؤه. |
| الارتفاع | int | ارتفاع المستطيل المراد ملؤه. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


يملأ داخل سلسلة من المستطيلات المحددة بواسطة هياكل  RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة التي تحدد خصائص التعبئة. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | مصفوفة من هياكل Rectangle التي تمثل المستطيلات المراد ملؤها. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


يملأ داخل سلسلة من المستطيلات المحددة بواسطة هياكل  Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | فرشاة التي تحدد خصائص التعبئة. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | مصفوفة من هياكل Rectangle التي تمثل المستطيلات المراد ملؤها. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


يملأ داخل  com.aspose.psd.region .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush الذي يحدد خصائص التعبئة. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region التي تمثل المنطقة المراد ملؤها. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


يحصل أو يضبط منطقة القص.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


يحصل أو يضبط جودة التركيب.

**Returns:**
int - جودة التركيب.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


يحصل على الدقة الأفقية لهذا  com.aspose.psd.graphics .

**Returns:**
float - القيمة، بوحدة النقاط في البوصة، للدقة الأفقية المدعومة من قبل com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


يحصل على الدقة العمودية لهذا  com.aspose.psd.graphics .

**Returns:**
float - القيمة، بوحدة النقاط في البوصة، للدقة العمودية المدعومة من قبل com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


يحصل على الصورة.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


يحصل أو يضبط وضع الاستيفاء.

**Returns:**
int - وضع الاستيفاء.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


يحصل أو يضبط التحجيم بين وحدات العالم ووحدات الصفحة لهذا  com.aspose.psd.graphics .

**Returns:**
float - مقياس التحويل بين وحدات العالم ووحدات الصفحة لهذا com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا  com.aspose.psd.graphics .

**Returns:**
int - وحدة القياس المستخدمة لإحداثيات الصفحة في هذا com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهية قابلة للرسم.

القيمة: خيارات الصورة، المستخدمة لإنشاء صور vactor قابلة للطلاء للرسم.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


يحصل أو يضبط وضع التنعيم.

**Returns:**
int - وضع التنعيم.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


يحصل أو يضبط تلميح عرض النص.

**Returns:**
int - تلميح عرض النص.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا  com.aspose.psd.graphics .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء BeginUpdate.

**Returns:**
boolean -  True  إذا كان graphics في حالة استدعاء BeginUpdate؛ وإلا،  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


يقيس السلسلة باستخدام الفئة [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | الخط. |
| text | java.lang.String | النص. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


يقيس السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | الخط. |
|  | text | java.lang.String | النص. |

--------------------

نتيجة GDI غالبًا ما تكون غير صالحة للخط المائل Italic وغالبًا ما تكون غير صالحة للخط العريض Bold. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


يقيس سلسلة النص المحددة باستخدام المعلمات المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص للقياس. |
| font | [Font](../../com.aspose.psd/font) | الخط للقياس. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | منطقة التخطيط. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | تنسيق السلسلة. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | الحصول على ذاكرة التخزين المؤقت للخط الخاص. |
| useMagicNumbersForStyles | boolean | إذا تم تعيينه إلى true [استخدام أرقام سحرية للأنماط]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب الـ com.aspose.psd.Matrix الذي يمثل التحويل الهندسي المحلي لهذا com.aspose.psd.Graphics بالمصفوفة com.aspose.psd.Matrix المحددة عن طريق إلحاق المصفوفة com.aspose.psd.matrix المحددة في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة com.aspose.psd.Matrix التي يتم ضربها في التحويل الهندسي. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب الـ com.aspose.psd.Matrix الذي يمثل التحويل الهندسي المحلي لهذا com.aspose.psd.Graphics بالمصفوفة com.aspose.psd.Matrix المحددة وفقًا للترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة com.aspose.psd.Matrix التي يتم ضربها في التحويل الهندسي. |
| الترتيب | int | قيمة com.aspose.psd.MatrixOrder التي تحدد ترتيب ضرب المصفوفتين. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين خاصية com.aspose.psd.graphics.Transform إلى الهوية.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد. هذه الطريقة تسبق الدوران إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالمقدار المحدد وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | float | زاوية الدوران. |
| الترتيب | int | قيمة com.aspose.psd.MatrixOrder التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. هذه الطريقة تسبق مصفوفة التكبير إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتحجيم التحويل الهندسي المحلي بالمقاسات المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور x. |
| sy | float | المقدار الذي يتم به تكبير التحويل في اتجاه محور y. |
| الترتيب | int | قيمة com.aspose.psd.MatrixOrder التي تحدد ما إذا كان سيتم إلحاق أو إلحاق مسبق لمصفوفة التحجيم. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


يحصل أو يضبط منطقة القص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | منطقة القص. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


يحصل أو يضبط جودة التركيب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | جودة التركيب. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


يحصل أو يضبط وضع الاستيفاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع الاستيفاء. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


يحصل أو يضبط التحجيم بين وحدات العالم ووحدات الصفحة لهذا  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | نسبة التحجيم بين وحدات العالم ووحدات الصفحة لهذا com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وحدة القياس المستخدمة لإحداثيات الصفحة في هذا com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهية قابلة للرسم.

القيمة: خيارات الصورة، المستخدمة لإنشاء صور vactor قابلة للطلاء للرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


يحصل أو يضبط وضع التنعيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع التنعيم. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


يحصل أو يضبط تلميح عرض النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح عرض النص. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا  com.aspose.psd.graphics .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | نسخة من المصفوفة com.aspose.psd.Matrix التي تمثل التحويل الهندسي العالمي لهذا com.aspose.psd.graphics. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يترجم التحويل الهندسي المحلي بالأبعاد المحددة. هذه الطريقة تسبق الترجمة إلى التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفق الترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الترجمة في المحور x. |
| dy | float | قيمة الترجمة في المحور y. |
| الترتيب | int | الترتيب (سابق أو لاحق) لتطبيق الترجمة. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

