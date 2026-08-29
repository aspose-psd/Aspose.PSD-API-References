---
title: "Graphics"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет графику в соответствии с графическим движком, используемым в текущей сборке."
type: docs
weight: 49
url: /ru/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Представляет графику в соответствии с графическим движком, используемым в текущей сборке.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Инициализирует новый экземпляр класса  Graphics  . |
## Поля

| Поле | Описание |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Получает коэффициент размера стиля жирного текста. |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Получает коэффициент размера стиля курсивного текста. |
## Методы

| Метод | Описание |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Применяет эффект. |
| [beginUpdate()](#beginUpdate--) | Начинает кэширование следующих графических операций. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Очищает графическую поверхность, используя указанный цвет. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Рисует дугу, представляющую часть эллипса, заданную структурой  Rectangle . |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Рисует дугу, представляющую часть эллипса, заданную структурой  RectangleF . |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Рисует сплайн Безье, определённый четырьмя структурами  Point . |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Рисует сплайн Безье, определённый четырьмя структурами  PointF . |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Рисует серию сплайнов Безье из массива  PointF  структур. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Рисует серию сплайнов Безье из массива  Point  структур. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Рисует замкнутый кардинальный сплайн, определённый массивом  PointF  структур. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Рисует замкнутый кардинальный сплайн, определённый массивом  PointF  структур, используя указанное натяжение. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Рисует замкнутый кардинальный сплайн, определённый массивом  Point  структур. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Рисует замкнутый кардинальный сплайн, определённый массивом  Point  структур, используя указанное натяжение. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Рисует кардинальный сплайн через указанный массив  PointF  структур. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Рисует кардинальный сплайн через указанный массив  PointF  структур, используя указанное натяжение. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Рисует кардинальный сплайн через указанный массив  PointF  структур. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Рисует кардинальный сплайн через указанный массив  PointF  структур, используя указанное натяжение. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Рисует кардинальный сплайн через указанный массив  Point  структур. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Рисует кардинальный сплайн через указанный массив  Point  структур, используя указанное натяжение. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Рисует кардинальный сплайн через указанный массив  Point  структур, используя указанное натяжение. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Рисует эллипс, заданный ограничивающей структурой  Rectangle . |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Рисует эллипс, определённый ограничивающим  RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Рисует указанное  Image , используя его оригинальный физический размер, в указанном месте. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Рисует указанное  Image , используя его оригинальный физический размер, в указанном месте. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Рисует указанную часть указанного  image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Рисует указанное  Image , используя его оригинальный физический размер, в указанном месте. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Рисует указанное  Image  в указанном месте и с указанным размером. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы поместить в указанный прямоугольник. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Рисует линию, соединяющую две  Point  структуры. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Рисует линию, соединяющую две  PointF  структуры. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Рисует серию отрезков, соединяющих массив  PointF  структур. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Рисует серию отрезков, соединяющих массив  Point  структур. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Отрисовывает  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Отрисовывает сектор, определенный эллипсом, заданным структурой  Rectangle  и двумя радиальными линиями. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Отрисовывает сектор, определенный эллипсом, заданным структурой  RectangleF  и двумя радиальными линиями. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Отрисовывает сектор, определенный эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Отрисовывает сектор, определенный эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Отрисовывает многоугольник, определенный массивом структур  PointF . |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Отрисовывает многоугольник, определенный массивом структур  Point . |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Отрисовывает прямоугольник, заданный структурой  Rectangle . |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Отрисовывает прямоугольник, заданный структурой  RectangleF . |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Отрисовывает прямоугольник, заданный парой координат, шириной и высотой. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Отрисовывает прямоугольник, заданный парой координат, шириной и высотой. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Отрисовывает серию прямоугольников, заданных структурами  RectangleF . |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Отрисовывает серию прямоугольников, заданных структурами  Rectangle . |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Отрисовывает указанную строку текста в указанном прямоугольнике с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Отрисовывает указанную строку текста в указанном прямоугольнике с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Отрисовывает указанную строку текста совместимым с Adobe способом в указанном прямоугольнике с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Отрисовывает указанную строку текста совместимым с Adobe способом в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font . |
| [endUpdate()](#endUpdate--) | Завершает кэширование графических операций, начатых после вызова BeginUpdate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.PointF . |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.PointF , используя указанный режим заполнения. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.PointF , используя указанный режим заполнения и натяжение. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.Point . |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.Point , используя указанный режим заполнения. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.Point , используя указанный режим заполнения и натяжение. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным структурой  com.aspose.psd.Rectangle . |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, указанным структурой  com.aspose.psd.RectangleF . |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Заполняет внутреннюю часть  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, указанным структурой  com.aspose.psd.RectangleF  и двумя радиальными линиями. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, указанным структурой  com.aspose.psd.RectangleF  и двумя радиальными линиями. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.PointF  и  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.PointF , используя указанный режим заливки. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.Point  и  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.Point , используя указанный режим заливки. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Заполняет внутреннюю часть прямоугольника, указанного структурой  Rectangle . |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Заполняет внутреннюю часть прямоугольника, указанного структурой  RectangleF . |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Заполняет внутреннюю часть прямоугольника, указанного парой координат, шириной и высотой. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Заполняет внутреннюю часть прямоугольника, указанного парой координат, шириной и высотой. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Заполняет внутренние части серии прямоугольников, указанных структурами  RectangleF . |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Заполняет внутренние части серии прямоугольников, указанных структурами  Rectangle . |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Заполняет внутреннюю часть  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Получает или задаёт область обрезки. |
| [getCompositingQuality()](#getCompositingQuality--) | Получает или задаёт качество композитинга. |
| [getDpiX()](#getDpiX--) | Получает горизонтальное разрешение этого com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Получает вертикальное разрешение этого com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Получает изображение. |
| [getInterpolationMode()](#getInterpolationMode--) | Получает или задаёт режим интерполяции. |
| [getPageScale()](#getPageScale--) | Получает или задаёт масштабирование между мировыми единицами и единицами страницы для этого com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Получает или задаёт единицу измерения, используемую для координат страницы в этом com.aspose.psd.graphics. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Получает или задаёт параметры изображения, используемые для создания рисуемых векторных изображений. |
| [getSmoothingMode()](#getSmoothingMode--) | Получает или задаёт режим сглаживания. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Получает или задает подсказку рендеринга текста. |
| [getTransform()](#getTransform--) | Получает или задает копию геометрического мирового преобразования для этого  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Измеряет строку с использованием класса [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Измеряет строку. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Измеряет указанную текстовую строку с заданными параметрами |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Умножает  com.aspose.psd.Matrix , представляющий локальное геометрическое преобразование этого  com.aspose.psd.Graphics , на указанный  com.aspose.psd.Matrix , предварительно добавляя указанный  com.aspose.psd.matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Умножает  com.aspose.psd.Matrix , представляющий локальное геометрическое преобразование этого  com.aspose.psd.Graphics , на указанный  com.aspose.psd.Matrix  в указанном порядке. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство  com.aspose.psd.graphics.Transform  к единичному. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Получает или задаёт область обрезки. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Получает или задаёт качество композитинга. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Получает или задаёт режим интерполяции. |
| [setPageScale(float value)](#setPageScale-float-) | Получает или задаёт масштабирование между мировыми единицами и единицами страницы для этого com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Получает или задаёт единицу измерения, используемую для координат страницы в этом com.aspose.psd.graphics. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Получает или задаёт параметры изображения, используемые для создания рисуемых векторных изображений. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Получает или задаёт режим сглаживания. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Получает или задает подсказку рендеринга текста. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Получает или задает копию геометрического мирового преобразования для этого  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Инициализирует новый экземпляр класса  Graphics  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Исходное изображение. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Получает коэффициент размера стиля жирного текста.

Используются магические числа, поскольку GDI всегда предоставляет измерения только для стиля Regular.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Получает коэффициент размера стиля курсивного текста.

Используются магические числа, поскольку GDI всегда предоставляет измерения только для стиля Regular.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Применяет эффект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| эффект | com.aspose.internal.IEffect | Эффект для применения. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Начинает кэширование следующих графических операций. Применяемые после этого графические эффекты не будут применяться немедленно; вместо этого EndUpdate вызовет применение всех эффектов сразу.

Обратите внимание, что эффекты после вызова BeginUpdate не будут применены, если EndUpdate не будет вызван.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Очищает графическую поверхность, используя указанный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Цвет, которым будет очищена графическая поверхность. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Рисует дугу, представляющую часть эллипса, заданную структурой  Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль дуги. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура RectangleF, определяющая границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до конечной точки дуги. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Рисует дугу, представляющую часть эллипса, заданную структурой  RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль дуги. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура RectangleF, определяющая границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до конечной точки дуги. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль дуги. |
| x | float | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | float | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| ширина | float | Ширина прямоугольника, определяющего эллипс. |
| высота | float | Высота прямоугольника, определяющего эллипс. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до конечной точки дуги. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль дуги. |
| x | int | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | int | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| ширина | int | Ширина прямоугольника, определяющего эллипс. |
| высота | int | Высота прямоугольника, определяющего эллипс. |
| startAngle | int | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweepAngle | int | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до конечной точки дуги. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Рисует сплайн Безье, определённый четырьмя структурами  Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Структура Pen, определяющая цвет, ширину и стиль кривой. |
| pt1 | [Point](../../com.aspose.psd/point) | Структура Point, представляющая начальную точку кривой. |
| pt2 | [Point](../../com.aspose.psd/point) | Структура Point, представляющая первую управляющую точку кривой. |
| pt3 | [Point](../../com.aspose.psd/point) | Структура Point, представляющая вторую управляющую точку кривой. |
| pt4 | [Point](../../com.aspose.psd/point) | Структура Point, представляющая конечную точку кривой. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Рисует сплайн Безье, определённый четырьмя структурами  PointF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль кривой. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая начальную точку кривой. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая первую управляющую точку кривой. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая вторую управляющую точку кривой. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая конечную точку кривой. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль кривой. |
| x1 | float | Координата x начальной точки кривой. |
| y1 | float | Координата y начальной точки кривой. |
| x2 | float | Координата x первой управляющей точки кривой. |
| y2 | float | Координата y первой управляющей точки кривой. |
| x3 | float | Координата x второй управляющей точки кривой. |
| y3 | float | Координата y второй управляющей точки кривой. |
| x4 | float | Координата x конечной точки кривой. |
| y4 | float | Координата y конечной точки кривой. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Рисует серию сплайнов Безье из массива  PointF  структур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , представляющих точки, определяющие кривую. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Рисует серию сплайнов Безье из массива  Point  структур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль кривой. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point  , представляющих точки, определяющие кривую. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Рисует закрытый кардинальный сплайн, определённый массивом структур  PointF . Этот метод использует натяжение по умолчанию 0.5 и  FillMode.Alternate  режим заливки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , определяющих сплайн. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Рисует закрытый кардинальный сплайн, определённый массивом структур  PointF  с указанным натяжением. Этот метод использует  FillMode.Alternate  режим заливки по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Рисует закрытый кардинальный сплайн, определённый массивом структур  Point . Этот метод использует натяжение по умолчанию 0.5 и  FillMode.Alternate  режим заливки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point  , определяющих сплайн. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Рисует закрытый кардинальный сплайн, определённый массивом структур  Point  с указанным натяжением. Этот метод использует  FillMode.Alternate  режим заливки по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point  , определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Рисует кардинальный сплайн через указанный массив структур  PointF . Этот метод использует натяжение по умолчанию 0.5.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , определяющих сплайн. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Рисует кардинальный сплайн через указанный массив  PointF  структур, используя указанное натяжение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , представляющих точки, определяющие кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Рисует кардинальный сплайн через указанный массив структур  PointF . Рисование начинается со смещения от начала массива. Этот метод использует натяжение по умолчанию 0.5.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , определяющих сплайн. |
| смещение | int | Смещение от первого элемента массива параметра  points  к начальной точке кривой. |
| numberOfSegments | int | Количество сегментов после начальной точки, включаемых в кривую. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Рисует кардинальный сплайн через указанный массив структур  PointF  с указанным натяжением. Рисование начинается со смещения от начала массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF  , определяющих сплайн. |
| смещение | int | Смещение от первого элемента массива параметра  points  к начальной точке кривой. |
| numberOfSegments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Рисует кардинальный сплайн через указанный массив  Point  структур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point  , определяющих сплайн. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Рисует кардинальный сплайн через указанный массив  Point  структур, используя указанное натяжение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point  , определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Рисует кардинальный сплайн через указанный массив  Point  структур, используя указанное натяжение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и высоту кривой. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point  , определяющих сплайн. |
| смещение | int | Смещение от первого элемента массива параметра  points  к начальной точке кривой. |
| numberOfSegments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Рисует эллипс, заданный ограничивающей структурой  Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль эллипса. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  структура, определяющая границы эллипса. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Рисует эллипс, определённый ограничивающим  RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль эллипса. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура RectangleF, определяющая границы эллипса. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль эллипса. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| ширина | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| высота | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  определяющий цвет, ширину и стиль эллипса. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| ширина | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| высота | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Рисует указанное  Image , используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| point | [Point](../../com.aspose.psd/point) | Структура Point, представляющая расположение верхнего левого угла нарисованного изображения. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Рисует указанное  Image , используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| point | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая верхний левый угол нарисованного изображения. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Исходный прямоугольник. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Исходный прямоугольник. |
| srcUnit | int | Единицы измерения. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Исходный прямоугольник. |
| srcUnit | int | Единицы измерения. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Атрибуты изображения. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Исходный прямоугольник. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Исходный прямоугольник. |
| srcUnit | int | Единицы измерения. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Рисует указанную часть указанного  image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Изображение для рисования. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Исходный прямоугольник. |
| srcUnit | int | Единицы измерения. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Атрибуты изображения. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура Rectangle, указывающая расположение и размер нарисованного изображения. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Исходный rect. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Целевой rect. |
| graphicsUnit | int | Графическая единица. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Исходный rect. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Целевой rect. |
| graphicsUnit | int | Графическая единица. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Атрибуты изображения. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Целевой прямоугольник. |
| graphicsUnit | int | Графическая единица. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Целевой прямоугольник. |
| graphicsUnit | int | Графическая единица. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Атрибуты изображения. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура RectangleF, указывающая расположение и размер нарисованного изображения. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Исходный rect. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Целевой rect. |
| graphicsUnit | int | Графическая единица. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Исходный прямоугольник. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Целевой прямоугольник. |
| graphicsUnit | int | Графическая единица для использования. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Атрибуты изображения для использования. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Целевой прямоугольник. |
| graphicsUnit | int | Графическая единица. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Целевой прямоугольник, в котором выполнять рисование. |
| graphicsUnit | int | Графическая единица. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Атрибуты изображения. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Рисует указанное  Image , используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| x | float | Координата X верхнего левого угла нарисованного изображения. |
| y | float | Координата Y верхнего левого угла нарисованного изображения. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| x | float | Координата X верхнего левого угла нарисованного изображения. |
| y | float | Координата Y верхнего левого угла нарисованного изображения. |
| ширина | float | Ширина нарисованного изображения. |
| высота | float | Высота нарисованного изображения. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Рисует указанное  Image  в указанном месте и с указанным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |
| ширина | int | Ширина нарисованного изображения. |
| высота | int | Высота нарисованного изображения. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| point | [Point](../../com.aspose.psd/point) | Структура Point, указывающая верхний левый угол нарисованного изображения. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle, указывающий верхний левый угол нарисованного изображения. Свойства X и Y прямоугольника указывают верхний левый угол. Свойства Width и Height игнорируются. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Рисует указанное изображение, используя его оригинальный физический размер, в месте, указанном парой координат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |
| ширина | int | Параметр не используется. |
| высота | int | Параметр не используется. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы поместить в указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Изображение, которым следует рисовать. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle, в котором следует нарисовать изображение. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Рисует линию, соединяющую две  Point  структуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль линии. |
| point1 | [Point](../../com.aspose.psd/point) | Структура Point, представляющая первую точку для соединения. |
| point2 | [Point](../../com.aspose.psd/point) | Структура Point, представляющая вторую точку для соединения. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Рисует линию, соединяющую две  PointF  структуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль линии. |
| point1 | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая первую точку для соединения. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Структура PointF, представляющая вторую точку для соединения. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль линии. |
| x1 | float | Координата x первой точки. |
| y1 | float | Координата y первой точки. |
| x2 | float | Координата x второй точки. |
| y2 | float | Координата y второй точки. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль линии. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Рисует серию отрезков, соединяющих массив  PointF  структур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль сегментов линии. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур PointF, представляющих точки для соединения. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Рисует серию отрезков, соединяющих массив  Point  структур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль сегментов линии. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур Point, представляющих точки для соединения. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Отрисовывает  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen, определяющий цвет, ширину и стиль пути. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath для рисования. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Отрисовывает сектор, определенный эллипсом, заданным структурой  Rectangle  и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль формы сектора. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура Rectangle, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся форма сектора. |
| startAngle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | float | Угол, измеряемый в градусах по часовой стрелке от параметра startAngle до второй стороны сектора. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Отрисовывает сектор, определенный эллипсом, заданным структурой  RectangleF  и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль формы сектора. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура RectangleF, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся форма сектора. |
| startAngle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | float | Угол, измеряемый в градусах по часовой стрелке от параметра startAngle до второй стороны сектора. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Отрисовывает сектор, определенный эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль формы сектора. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма сектора. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма сектора. |
| ширина | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| высота | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| startAngle | float | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | float | Угол, измеряемый в градусах по часовой стрелке от параметра startAngle до второй стороны сектора. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Отрисовывает сектор, определенный эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, определяющий цвет, ширину и стиль формы сектора. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма сектора. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма сектора. |
| ширина | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| высота | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| startAngle | int | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны сектора. |
| sweepAngle | int | Угол, измеряемый в градусах по часовой стрелке от параметра startAngle до второй стороны сектора. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Отрисовывает многоугольник, определенный массивом структур  PointF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль многоугольника. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  PointF , представляющих вершины многоугольника. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Отрисовывает многоугольник, определенный массивом структур  Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль многоугольника. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  Point , представляющих вершины многоугольника. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Отрисовывает прямоугольник, заданный структурой  Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль прямоугольника. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  Rectangle , представляющая прямоугольник для рисования. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Отрисовывает прямоугольник, заданный структурой  RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль прямоугольника. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  RectangleF , представляющая прямоугольник для рисования. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Отрисовывает прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль прямоугольника. |
| x | float | Координата x верхнего левого угла прямоугольника для рисования. |
| y | float | Координата y верхнего левого угла прямоугольника для рисования. |
| ширина | float | Ширина прямоугольника для рисования. |
| высота | float | Высота прямоугольника для рисования. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Отрисовывает прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль прямоугольника. |
| x | int | Координата x верхнего левого угла прямоугольника для рисования. |
| y | int | Координата y верхнего левого угла прямоугольника для рисования. |
| ширина | int | Ширина прямоугольника для рисования. |
| высота | int | Высота прямоугольника для рисования. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Отрисовывает серию прямоугольников, заданных структурами  RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Массив структур  RectangleF , представляющих прямоугольники для рисования. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Отрисовывает серию прямоугольников, заданных структурами  Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  который определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Массив структур  Rectangle , представляющих прямоугольники для рисования. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| point | [PointF](../../com.aspose.psd/pointf) | Структура com.aspose.psd.PointF , указывающая верхний левый угол нарисованного текста. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| point | [PointF](../../com.aspose.psd/pointf) | Структура com.aspose.psd.PointF , указывающая верхний левый угол нарисованного текста. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  который задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Отрисовывает указанную строку текста в указанном прямоугольнике с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF , указывающая расположение нарисованного текста. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Отрисовывает указанную строку текста в указанном прямоугольнике с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF , указывающая расположение нарисованного текста. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  который задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Отрисовывает указанную строку текста в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  который задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Отрисовывает указанную строку текста совместимым с Adobe способом в указанном прямоугольнике с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font , используя атрибуты форматирования указанного  com.aspose.psd.stringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Структура com.aspose.psd.RectangleF , указывающая расположение нарисованного текста. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  который задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Отрисовывает указанную строку текста совместимым с Adobe способом в указанном месте с указанными объектами  com.aspose.psd.Brush  и  com.aspose.psd.Font .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Строка для рисования. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  который определяет формат текста строки. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  который определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Завершает кэширование графических операций, начатых после вызова BeginUpdate. Предыдущие графические операции будут применены сразу при вызове этого метода.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определенной массивом структур  com.aspose.psd.PointF . Этот метод использует напряжение по умолчанию 0.5 и режим заливки  FillMode.Alternate .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих сплайн. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определенной массивом структур  com.aspose.psd.PointF , используя указанный режим заливки. Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих сплайн. |
| режим заливки | int | Элемент перечисления  com.aspose.psd.FillMode , определяющий, как заполняется кривая. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.PointF , используя указанный режим заполнения и натяжение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Объект  com.aspose.psd.Brush , определяющий характеристики заливки. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , определяющих сплайн. |
| режим заливки | int | Элемент перечисления  com.aspose.psd.FillMode , определяющий, как заполняется кривая. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определенной массивом структур  com.aspose.psd.Point . Этот метод использует напряжение по умолчанию 0.5 и режим заливки  FillMode.Alternate .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  com.aspose.psd.Point , определяющих сплайн. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Заполняет внутреннюю часть замкнутой кардинальной сплайн-кривой, определенной массивом структур  com.aspose.psd.Point , используя указанный режим заливки. Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  com.aspose.psd.Point , определяющих сплайн. |
| режим заливки | int | Элемент перечисления  com.aspose.psd.FillMode , определяющий, как заполняется кривая. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Заполняет внутреннюю часть закрытой кривой кардинального сплайна, определенной массивом структур  com.aspose.psd.Point , используя указанный режим заполнения и натяжение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур  com.aspose.psd.Point , определяющих сплайн. |
| режим заливки | int | Элемент перечисления  com.aspose.psd.FillMode , определяющий, как заполняется кривая. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным структурой  com.aspose.psd.Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , представляющая ограничивающий прямоугольник, определяющий эллипс. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, указанным структурой  com.aspose.psd.RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF , представляющая ограничивающий прямоугольник, определяющий эллипс. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| ширина | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| высота | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Заполняет внутреннюю часть эллипса, определённого ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс. |
| ширина | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| высота | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Заполняет внутреннюю часть  com.aspose.psd.graphicsPath .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath , представляющий путь для заполнения. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Заполняет внутреннюю часть сектора пирога, определённого эллипсом, указанным структурой  com.aspose.psd.RectangleF  и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура  com.aspose.psd.Rectangle , представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до второй стороны сектора пирога. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Заполняет внутреннюю часть сектора пирога, определённого эллипсом, указанным структурой  com.aspose.psd.RectangleF  и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура  com.aspose.psd.RectangleF , представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор пирога. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до второй стороны сектора пирога. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| ширина | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| высота | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до второй стороны сектора пирога. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Заполняет внутреннюю часть сектора пирога, определённого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| ширина | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| высота | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор пирога. |
| startAngle | int | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора пирога. |
| sweepAngle | int | Угол в градусах, измеряемый по часовой стрелке от параметра  startAngle  до второй стороны сектора пирога. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.PointF  и  FillMode.Alternate .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , представляющих вершины полигона для заполнения. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.PointF , используя указанный режим заливки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Массив структур  com.aspose.psd.PointF , представляющих вершины полигона для заполнения. |
| fillMode | int | Элемент перечисления com.aspose.psd.FillMode, определяющий стиль заливки. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.Point  и  FillMode.Alternate .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур com.aspose.psd.Point, представляющих вершины полигона для заливки. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Заполняет внутреннюю часть многоугольника, определённого массивом точек, указанных структурами  com.aspose.psd.Point , используя указанный режим заливки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.psd/point) | Массив структур com.aspose.psd.Point, представляющих вершины полигона для заливки. |
| fillMode | int | Элемент перечисления com.aspose.psd.FillMode, определяющий стиль заливки. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Заполняет внутреннюю часть прямоугольника, указанного структурой  Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Кисть, определяющая характеристики заливки. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Структура Rectangle, представляющая прямоугольник для заливки. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Заполняет внутреннюю часть прямоугольника, указанного структурой  RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Кисть, определяющая характеристики заливки. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Структура RectangleF, представляющая прямоугольник для заливки. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Заполняет внутреннюю часть прямоугольника, указанного парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Кисть, определяющая характеристики заливки. |
| x | float | Координата x левого верхнего угла прямоугольника для заливки. |
| y | float | Координата y левого верхнего угла прямоугольника для заливки. |
| ширина | float | Ширина прямоугольника для заливки. |
| высота | float | Высота прямоугольника для заливки. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Заполняет внутреннюю часть прямоугольника, указанного парой координат, шириной и высотой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Кисть, определяющая характеристики заливки. |
| x | int | Координата x левого верхнего угла прямоугольника для заливки. |
| y | int | Координата y левого верхнего угла прямоугольника для заливки. |
| ширина | int | Ширина прямоугольника для заливки. |
| высота | int | Высота прямоугольника для заливки. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Заполняет внутренние части серии прямоугольников, указанных структурами  RectangleF .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Кисть, определяющая характеристики заливки. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Массив структур Rectangle, представляющих прямоугольники для заливки. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Заполняет внутренние части серии прямоугольников, указанных структурами  Rectangle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Кисть, определяющая характеристики заливки. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Массив структур Rectangle, представляющих прямоугольники для заливки. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Заполняет внутреннюю часть  com.aspose.psd.region .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  определяющая характеристики заливки. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region, представляющий область для заливки. |

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


Получает или задаёт область обрезки.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Получает или задаёт качество композитинга.

**Returns:**
int — качество композиции.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Получает горизонтальное разрешение этого com.aspose.psd.graphics.

**Returns:**
float — значение в точках на дюйм для горизонтального разрешения, поддерживаемого этим com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Получает вертикальное разрешение этого com.aspose.psd.graphics.

**Returns:**
float — значение в точках на дюйм для вертикального разрешения, поддерживаемого этим com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Получает изображение.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Получает или задаёт режим интерполяции.

**Returns:**
int — режим интерполяции.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Получает или задаёт масштабирование между мировыми единицами и единицами страницы для этого com.aspose.psd.graphics.

**Returns:**
float — масштабирование между мировыми единицами и единицами страницы для этого com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Получает или задаёт единицу измерения, используемую для координат страницы в этом com.aspose.psd.graphics.

**Returns:**
int — единица измерения, используемая для координат страницы в этом com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Получает или задаёт параметры изображения, используемые для создания рисуемых векторных изображений.

Значение: параметры изображения, используемые для создания рисуемых векторных изображений.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Получает или задаёт режим сглаживания.

**Returns:**
int — режим сглаживания.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Получает или задает подсказку рендеринга текста.

**Returns:**
int — подсказка рендеринга текста.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает или задает копию геометрического мирового преобразования для этого  com.aspose.psd.graphics .

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


Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate.

**Returns:**
boolean —  True  если графика находится в состоянии вызова BeginUpdate; иначе  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Измеряет строку с использованием класса [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Шрифт. |
| текст | java.lang.String | Текст. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Измеряет строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Шрифт. |
|  | текст | java.lang.String | Текст. |

--------------------

Результат GDI почти всегда недействителен для курсивных и часто недействителен для жирных стилей. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Измеряет указанную текстовую строку с заданными параметрами

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Текст для измерения. |
| font | [Font](../../com.aspose.psd/font) | Шрифт для измерения. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Область макета. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Формат строки. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Получить приватный кэш шрифтов. |
| useMagicNumbersForStyles | boolean | если установлено в  true  [использовать магические числа для стилей]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает  com.aspose.psd.Matrix , представляющий локальное геометрическое преобразование этого  com.aspose.psd.Graphics , на указанный  com.aspose.psd.Matrix , предварительно добавляя указанный  com.aspose.psd.matrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица  com.aspose.psd.Matrix  для умножения геометрического преобразования. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает  com.aspose.psd.Matrix , представляющий локальное геометрическое преобразование этого  com.aspose.psd.Graphics , на указанный  com.aspose.psd.Matrix  в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица  com.aspose.psd.Matrix  для умножения геометрического преобразования. |
| порядок | int | Тип  com.aspose.psd.MatrixOrder  указывает порядок умножения двух матриц. |

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


Сбрасывает свойство  com.aspose.psd.graphics.Transform  к единичному.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Вращает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| порядок | int | Тип  com.aspose.psd.MatrixOrder  указывает, добавлять ли или предшествовать матрице вращения. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую масштабировать преобразование по оси x. |
| sy | float | Величина, на которую масштабировать преобразование по оси y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую масштабировать преобразование по оси x. |
| sy | float | Величина, на которую масштабировать преобразование по оси y. |
| порядок | int | Тип  com.aspose.psd.MatrixOrder  указывает, добавлять ли или предшествовать матрице масштабирования. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Получает или задаёт область обрезки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Область отсечения. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Получает или задаёт качество композитинга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Качество композитинга. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Получает или задаёт режим интерполяции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Режим интерполяции. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Получает или задаёт масштабирование между мировыми единицами и единицами страницы для этого com.aspose.psd.graphics.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Масштабирование между мировыми и страницными единицами для этого com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Получает или задаёт единицу измерения, используемую для координат страницы в этом com.aspose.psd.graphics.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Единица измерения, используемая для координат страницы в этом com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Получает или задаёт параметры изображения, используемые для создания рисуемых векторных изображений.

Значение: параметры изображения, используемые для создания рисуемых векторных изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Получает или задаёт режим сглаживания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Режим сглаживания. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Получает или задает подсказку рендеринга текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Подсказка рендеринга текста. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Получает или задает копию геометрического мирового преобразования для этого  com.aspose.psd.graphics .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Копия  com.aspose.psd.Matrix  , представляющая геометрическое мировое преобразование для этого  com.aspose.psd.graphics . |

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


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| порядок | int | Порядок (prepend или append), в котором применяется трансляция. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

