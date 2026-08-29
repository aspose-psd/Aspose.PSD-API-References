---
title: "Graphics"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar grafik enligt den grafikmotor som används i den aktuella samlingen."
type: docs
weight: 49
url: /sv/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Representerar grafik enligt den grafikmotor som används i den aktuella samlingen.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Initierar en ny instans av klassen  Graphics . |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Hämtar fet textstil storlekskoefficient |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Hämtar kursiv textstil storlekskoefficient |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Tillämpar effekten. |
| [beginUpdate()](#beginUpdate--) | Startar cachning av följande grafikoperationer. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Rensar grafikytan med den angivna färgen. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Ritar en båge som representerar en del av en ellips specificerad av en  Rectangle  struktur. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Ritar en båge som representerar en del av en ellips specificerad av en  RectangleF  struktur. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Ritar en båge som representerar en del av en ellips som anges av ett koordinatpar, en bredd och en höjd. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Ritar en båge som representerar en del av en ellips som anges av ett koordinatpar, en bredd och en höjd. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Ritar en Bézier-spline definierad av fyra  Point  strukturer. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Ritar en Bézier-spline definierad av fyra  PointF  strukturer. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Ritar en Bézier-spline definierad av fyra ordnade koordinatpar som representerar punkter. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Ritar en serie av Bézier-splines från en matris av  PointF  strukturer. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Ritar en serie av Bézier-splines från en matris av  Point  strukturer. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Ritar en sluten cardinal-spline definierad av en matris av  PointF  strukturer. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Ritar en sluten cardinal-spline definierad av en matris av  PointF  strukturer med en angiven spänning. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Ritar en sluten cardinal-spline definierad av en matris av  Point  strukturer. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Ritar en sluten cardinal-spline definierad av en matris av  Point  strukturer med en angiven spänning. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Ritar en cardinal-spline genom en angiven matris av  PointF  strukturer. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Ritar en cardinal-spline genom en angiven matris av  PointF  strukturer med en angiven spänning. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Ritar en cardinal-spline genom en angiven matris av  PointF  strukturer. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Ritar en cardinal-spline genom en angiven matris av  PointF  strukturer med en angiven spänning. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Ritar en cardinal-spline genom en angiven matris av  Point  strukturer. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Ritar en cardinal-spline genom en angiven matris av  Point  strukturer med en angiven spänning. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Ritar en cardinal-spline genom en angiven matris av  Point  strukturer med en angiven spänning. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Ritar en ellips som anges av en begränsande  Rectangle  struktur. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Ritar en ellips definierad av en begränsande  RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Ritar en ellips definierad av en begränsande rektangel som anges av ett koordinatpar, en höjd och en bredd. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Ritar en ellips definierad av en begränsande rektangel som anges av ett koordinatpar, en höjd och en bredd. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Ritar den angivna  Image , med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Ritar den angivna  Image , med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Ritar den angivna  Image , med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Ritar den angivna image, med dess ursprungliga fysiska storlek, på platsen som anges av ett koordinatpar. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Ritar den angivna  Image  på den angivna platsen och med den angivna storleken. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Ritar en angiven image med dess ursprungliga fysiska storlek på en angiven plats. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Ritar en angiven image med dess ursprungliga fysiska storlek på en angiven plats. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Ritar den angivna image med dess ursprungliga fysiska storlek på den plats som anges av ett koordinatpar. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Ritar en angiven image med dess ursprungliga fysiska storlek på en angiven plats. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Ritar den angivna image utan skalning och beskär den, om nödvändigt, för att passa i den angivna rektangeln. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Ritar en linje som förbinder två  Point  strukturer. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Ritar en linje som förbinder två  PointF  strukturer. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Ritar en linje som förbinder de två punkterna som anges av koordinatparen. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Ritar en linje som förbinder de två punkterna som anges av koordinatparen. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Ritar en serie linjesegment som förbinder en matris av  PointF  strukturer. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Ritar en serie linjesegment som förbinder en matris av  Point  strukturer. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Ritar en  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Ritar en pajform definierad av en ellips som anges av en  Rectangle  struktur och två radiala linjer. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Ritar en pajform definierad av en ellips som anges av en  RectangleF  struktur och två radiala linjer. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Ritar en polygon definierad av en matris av  PointF  strukturer. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Ritar en polygon definierad av en matris av  Point  strukturer. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Ritar en rektangel som anges av en  Rectangle  struktur. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Ritar en rektangel som anges av en  RectangleF  struktur. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Ritar en serie rektanglar som anges av  RectangleF  strukturer. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Ritar en serie rektanglar som anges av  Rectangle  strukturer. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Ritar den angivna textsträngen på Adobe-kompatibelt sätt i den angivna rektangeln med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Ritar den angivna textsträngen på Adobe-kompatibelt sätt på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten. |
| [endUpdate()](#endUpdate--) | Avslutar cachning av grafikoperationerna som startades efter att BeginUpdate anropades. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av  com.aspose.psd.PointF  strukturer. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av  com.aspose.psd.PointF  strukturer med den angivna fyllningsläget. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av  com.aspose.psd.PointF  strukturer med det angivna fyllningsläget och spänningen. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Fyller innanmätet av en sluten kardinalsplinekurva definierad av en array av  com.aspose.psd.Point  strukturer. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Fyller innanmätet av en sluten kardinalsplinekurva definierad av en array av  com.aspose.psd.Point  strukturer med det angivna fyllningsläget. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Fyller innanmätet av en sluten kardinalsplinekurva definierad av en array av  com.aspose.psd.Point  strukturer med det angivna fyllningsläget och spänning. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av en  com.aspose.psd.Rectangle  struktur. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av en  com.aspose.psd.RectangleF  struktur. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Fyller innanmätet av en  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av en  com.aspose.psd.RectangleF  struktur och två radiala linjer. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av en  com.aspose.psd.RectangleF  struktur och två radiala linjer. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.PointF  strukturer och  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.PointF  strukturer med det angivna fyllningsläget. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.Point  strukturer och  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.Point  strukturer med det angivna fyllningsläget. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Fyller innanmätet av en rektangel specificerad av en  Rectangle  struktur. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Fyller innanmätet av en rektangel specificerad av en  RectangleF  struktur. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Fyller innanmätet av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Fyller innanmätet av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Fyller innanmätet av en serie rektanglar specificerade av  RectangleF  strukturer. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Fyller innanmätet av en serie rektanglar specificerade av  Rectangle  strukturer. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Fyller innanmätet av en  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Hämtar eller anger klippregionen. |
| [getCompositingQuality()](#getCompositingQuality--) | Hämtar eller anger kompositkvaliteten. |
| [getDpiX()](#getDpiX--) | Hämtar den horisontella upplösningen för detta  com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Hämtar den vertikala upplösningen för detta  com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Hämtar bilden. |
| [getInterpolationMode()](#getInterpolationMode--) | Hämtar eller anger interpolationsläget. |
| [getPageScale()](#getPageScale--) | Hämtar eller anger skalningen mellan världsenheter och sid‑enheter för detta com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Hämtar eller anger måttenheten som används för sidkoordinater i detta com.aspose.psd.graphics. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Hämtar eller anger bildalternativ, som används för att skapa målbara vektor‑bilder att rita. |
| [getSmoothingMode()](#getSmoothingMode--) | Hämtar eller anger jämningsläget. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Hämtar eller anger tips för textåtergivning. |
| [getTransform()](#getTransform--) | Hämtar eller anger en kopia av den geometriska världstransformationen för detta com.aspose.psd.graphics. |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Hämtar ett värde som indikerar om grafik är i BeginUpdate‑anropstillstånd. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Mäter strängen med hjälp av klassen [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Mäter strängen. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Mäter den angivna textsträngen med angivna parametrar |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplicerar com.aspose.psd.Matrix som representerar den lokala geometriska transformen för detta com.aspose.psd.Graphics med den angivna com.aspose.psd.Matrix genom att föregå den angivna com.aspose.psd.matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplicerar com.aspose.psd.Matrix som representerar den lokala geometriska transformen för detta com.aspose.psd.Graphics med den angivna com.aspose.psd.Matrix i angiven ordning. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Återställer egenskapen com.aspose.psd.graphics.Transform till identitet. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotera den lokala geometriska transformationen med den angivna mängden. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna värdena. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Hämtar eller anger klippregionen. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Hämtar eller anger kompositkvaliteten. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Hämtar eller anger interpolationsläget. |
| [setPageScale(float value)](#setPageScale-float-) | Hämtar eller anger skalningen mellan världsenheter och sid‑enheter för detta com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Hämtar eller anger måttenheten som används för sidkoordinater i detta com.aspose.psd.graphics. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Hämtar eller anger bildalternativ, som används för att skapa målbara vektor‑bilder att rita. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Hämtar eller anger jämningsläget. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Hämtar eller anger tips för textåtergivning. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Hämtar eller anger en kopia av den geometriska världstransformationen för detta com.aspose.psd.graphics. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Initierar en ny instans av klassen  Graphics .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Källbilden. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Hämtar fet textstil storlekskoefficient

Använder magiska tal eftersom GDI alltid endast ger mätning för Regular‑stil.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Hämtar kursiv textstil storlekskoefficient

Använder magiska tal eftersom GDI alltid endast ger mätning för Regular‑stil.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Tillämpar effekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| effekt | com.aspose.internal.IEffect | Effekten att tillämpa. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Startar cachning av följande grafikoperationer. Grafik‑effekterna som tillämpas därefter kommer inte att tillämpas omedelbart utan EndUpdate kommer att orsaka att alla effekter tillämpas på en gång.

Observera att effekterna efter att BeginUpdate har anropats inte kommer att tillämpas om EndUpdate inte anropas.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Rensar grafikytan med den angivna färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Färgen som används för att rensa grafikytan. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Ritar en båge som representerar en del av en ellips specificerad av en  Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färg, bredd och stil för bågen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | RectangleF‑struktur som definierar ellipsens gränser. |
| startvinkel | float | Vinkel i grader, mätt medurs från x‑axeln till bågens startpunkt. |
| sweepAngle | float | Vinkel i grader mätt medurs från den  startAngle  parametern till slutpunkten på bågen. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Ritar en båge som representerar en del av en ellips specificerad av en  RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färg, bredd och stil för bågen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF‑struktur som definierar ellipsens gränser. |
| startvinkel | float | Vinkel i grader, mätt medurs från x‑axeln till bågens startpunkt. |
| sweepAngle | float | Vinkel i grader mätt medurs från den  startAngle  parametern till slutpunkten på bågen. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Ritar en båge som representerar en del av en ellips som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färg, bredd och stil för bågen. |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen. |
| bredd | float | Bredden på rektangeln som definierar ellipsen. |
| höjd | float | Höjden på rektangeln som definierar ellipsen. |
| startvinkel | float | Vinkel i grader, mätt medurs från x‑axeln till bågens startpunkt. |
| sweepAngle | float | Vinkel i grader mätt medurs från den  startAngle  parametern till slutpunkten på bågen. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Ritar en båge som representerar en del av en ellips som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färg, bredd och stil för bågen. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som definierar ellipsen. |
| bredd | int | Bredden på rektangeln som definierar ellipsen. |
| höjd | int | Höjden på rektangeln som definierar ellipsen. |
| startvinkel | int | Vinkel i grader, mätt medurs från x‑axeln till bågens startpunkt. |
| sweepAngle | int | Vinkel i grader mätt medurs från den  startAngle  parametern till slutpunkten på bågen. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Ritar en Bézier-spline definierad av fyra  Point  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  struktur som bestämmer färgen, bredden och stilen på kurvan. |
| pt1 | [Point](../../com.aspose.psd/point) | Point  struktur som representerar startpunkten för kurvan. |
| pt2 | [Point](../../com.aspose.psd/point) | Point  struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | [Point](../../com.aspose.psd/point) | Point  struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | [Point](../../com.aspose.psd/point) | Point  struktur som representerar slutpunkten för kurvan. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Ritar en Bézier-spline definierad av fyra  PointF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på kurvan. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar startpunkten för kurvan. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar slutpunkten för kurvan. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Ritar en Bézier-spline definierad av fyra ordnade koordinatpar som representerar punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på kurvan. |
| x1 | float | X-koordinaten för startpunkten för kurvan. |
| y1 | float | Y-koordinaten för startpunkten för kurvan. |
| x2 | float | X-koordinaten för den första kontrollpunkten för kurvan. |
| y2 | float | Y-koordinaten för den första kontrollpunkten för kurvan. |
| x3 | float | X-koordinaten för den andra kontrollpunkten på kurvan. |
| y3 | float | Y-koordinaten för den andra kontrollpunkten på kurvan. |
| x4 | float | X-koordinaten för slutpunkten på kurvan. |
| y4 | float | Y-koordinaten för slutpunkten på kurvan. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Ritar en serie av Bézier-splines från en matris av  PointF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som representerar punkterna som bestämmer kurvan. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Ritar en serie av Bézier-splines från en matris av  Point  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på kurvan. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som representerar punkterna som bestämmer kurvan. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Ritar en sluten kardinal spline definierad av en array av  PointF  strukturer. Denna metod använder en standardspänning på 0.5 och  FillMode.Alternate  fyllningsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som definierar splinen. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Ritar en sluten kardinal spline definierad av en array av  PointF  strukturer med en specificerad spänning. Denna metod använder ett standard  FillMode.Alternate  fyllningsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Ritar en sluten kardinal spline definierad av en array av  Point  strukturer. Denna metod använder en standardspänning på 0.5 och  FillMode.Alternate  fyllningsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som definierar splinen. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Ritar en sluten kardinal spline definierad av en array av  Point  strukturer med en specificerad spänning. Denna metod använder ett standard  FillMode.Alternate  fyllningsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Ritar en kardinal spline genom en specificerad array av  PointF  strukturer. Denna metod använder en standardspänning på 0.5.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som definierar splinen. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Ritar en cardinal-spline genom en angiven matris av  PointF  strukturer med en angiven spänning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som representerar punkterna som definierar kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Ritar en kardinal spline genom en specificerad array av  PointF  strukturer. Ritningen börjar med ett förskjutning från början av arrayen. Denna metod använder en standardspänning på 0.5.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som definierar splinen. |
| offset | int | Förskjutning från det första elementet i arrayen av  points  parametern till startpunkten i kurvan. |
| numberOfSegments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Ritar en kardinal spline genom en specificerad array av  PointF  strukturer med en specificerad spänning. Ritningen börjar med ett förskjutning från början av arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som definierar splinen. |
| offset | int | Förskjutning från det första elementet i arrayen av  points  parametern till startpunkten i kurvan. |
| numberOfSegments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Ritar en cardinal-spline genom en angiven matris av  Point  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som definierar splinen. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Ritar en cardinal-spline genom en angiven matris av  Point  strukturer med en angiven spänning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som definierar splinen. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Ritar en cardinal-spline genom en angiven matris av  Point  strukturer med en angiven spänning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och höjden på kurvan. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som definierar splinen. |
| offset | int | Förskjutning från det första elementet i arrayen av  points  parametern till startpunkten i kurvan. |
| numberOfSegments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Ritar en ellips som anges av en begränsande  Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på ellipsen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  struktur som definierar ellipsens gränser. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Ritar en ellips definierad av en begränsande  RectangleF .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på ellipsen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF‑struktur som definierar ellipsens gränser. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Ritar en ellips definierad av en begränsande rektangel som anges av ett koordinatpar, en höjd och en bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på ellipsen. |
| x | float | x-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | float | y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| bredd | float | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| höjd | float | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Ritar en ellips definierad av en begränsande rektangel som anges av ett koordinatpar, en höjd och en bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på ellipsen. |
| x | int | x-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | int | y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| bredd | int | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| höjd | int | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Ritar den angivna  Image , med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| point | [Point](../../com.aspose.psd/point) | Point  struktur som representerar platsen för det övre vänstra hörnet av den ritade bilden. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Ritar den angivna  Image , med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| point | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar det övre vänstra hörnet av den ritade bilden. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Källrektangeln. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Källrektangeln. |
| srcUnit | int | Måttenheterna. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Källrektangeln. |
| srcUnit | int | Måttenheterna. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Bildattributen. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Källrektangeln. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Källrektangeln. |
| srcUnit | int | Måttenheterna. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Ritar den angivna delen av den angivna  image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Bilden att rita. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Källrektangeln. |
| srcUnit | int | Måttenheterna. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Bildattributen. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  struktur som specificerar platsen och storleken på den ritade bilden. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Källrektangeln. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Källrektangeln. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Bildattributen. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Bildattributen. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  struktur som specificerar platsen och storleken på den ritade bilden. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Källrektangeln. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Källrektangeln. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten att använda. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Bildattributen att använda. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Målrrektangeln. |
| graphicsUnit | int | Grafikenheten. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Målrrektangeln att rita i. |
| graphicsUnit | int | Grafikenheten. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Bildattributen. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Ritar den angivna  Image , med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| bredd | float | Bredden på den ritade bilden. |
| höjd | float | Höjden på den ritade bilden. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Ritar den angivna image, med dess ursprungliga fysiska storlek, på platsen som anges av ett koordinatpar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Ritar den angivna  Image  på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| bredd | int | Bredden på den ritade bilden. |
| höjd | int | Höjden på den ritade bilden. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Ritar en angiven image med dess ursprungliga fysiska storlek på en angiven plats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| point | [Point](../../com.aspose.psd/point) | Point  struktur som specificerar det övre vänstra hörnet av den ritade bilden. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Ritar en angiven image med dess ursprungliga fysiska storlek på en angiven plats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  som specificerar det övre vänstra hörnet av den ritade bilden. X‑ och Y‑egenskaperna för rektangeln specificerar det övre vänstra hörnet. Bredd‑ och höjd‑egenskaperna ignoreras. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Ritar den angivna image med dess ursprungliga fysiska storlek på den plats som anges av ett koordinatpar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Ritar en angiven image med dess ursprungliga fysiska storlek på en angiven plats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| bredd | int | Parametern används inte. |
| höjd | int | Parametern används inte. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Ritar den angivna image utan skalning och beskär den, om nödvändigt, för att passa i den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Bilden att rita med. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  Rectangle  i vilken bilden ska ritas. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Ritar en linje som förbinder två  Point  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [Point](../../com.aspose.psd/point) | Point  struktur som representerar den första punkten att ansluta. |
| point2 | [Point](../../com.aspose.psd/point) | Point  struktur som representerar den andra punkten att ansluta. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Ritar en linje som förbinder två  PointF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar den första punkten att ansluta. |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF  struktur som representerar den andra punkten att ansluta. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Ritar en linje som förbinder de två punkterna som anges av koordinatparen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på linjen. |
| x1 | float | X-koordinaten för den första punkten. |
| y1 | float | Y-koordinaten för den första punkten. |
| x2 | float | X-koordinaten för den andra punkten. |
| y2 | float | Y-koordinaten för den andra punkten. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Ritar en linje som förbinder de två punkterna som anges av koordinatparen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på linjen. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Ritar en serie linjesegment som förbinder en matris av  PointF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på linjesegmenten. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som representerar punkterna att ansluta. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Ritar en serie linjesegment som förbinder en matris av  Point  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på linjesegmenten. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som representerar punkterna att ansluta. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Ritar en  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen som bestämmer färgen, bredden och stilen på sökvägen. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath att rita. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Ritar en pajform definierad av en ellips som anges av en  Rectangle  struktur och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på pajformen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| startvinkel | float | Vinkel mätt i grader medurs från x‑axeln till den första sidan av pajformen. |
| sweepAngle | float | Vinkel som mäts i grader medurs från  startAngle  parametern till den andra sidan av pajformen. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Ritar en pajform definierad av en ellips som anges av en  RectangleF  struktur och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på pajformen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| startvinkel | float | Vinkel mätt i grader medurs från x‑axeln till den första sidan av pajformen. |
| sweepAngle | float | Vinkel som mäts i grader medurs från  startAngle  parametern till den andra sidan av pajformen. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på pajformen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| bredd | float | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| höjd | float | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| startvinkel | float | Vinkel mätt i grader medurs från x‑axeln till den första sidan av pajformen. |
| sweepAngle | float | Vinkel som mäts i grader medurs från  startAngle  parametern till den andra sidan av pajformen. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen som bestämmer färgen, bredden och stilen på pajformen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| bredd | int | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| höjd | int | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| startvinkel | int | Vinkel mätt i grader medurs från x‑axeln till den första sidan av pajformen. |
| sweepAngle | int | Vinkel som mäts i grader medurs från  startAngle  parametern till den andra sidan av pajformen. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Ritar en polygon definierad av en matris av  PointF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på polygonen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  PointF  strukturer som representerar polygonens hörn. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Ritar en polygon definierad av en matris av  Point  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på polygonen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  Point  strukturer som representerar polygonens hörn. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Ritar en rektangel som anges av en  Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | En  Pen  som bestämmer färgen, bredden och stilen på rektangeln. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | En  Rectangle  struktur som representerar rektangeln som ska ritas. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Ritar en rektangel som anges av en  RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | En  Pen  som bestämmer färgen, bredden och stilen på rektangeln. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | En  RectangleF  struktur som representerar rektangeln som ska ritas. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | En  Pen  som bestämmer färgen, bredden och stilen på rektangeln. |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| bredd | float | Bredden på rektangeln som ska ritas. |
| höjd | float | Höjden på rektangeln som ska ritas. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på rektangeln. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska ritas. |
| bredd | int | Bredden på rektangeln som ska ritas. |
| höjd | int | Höjden på rektangeln som ska ritas. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Ritar en serie rektanglar som anges av  RectangleF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på konturerna av rektanglarna. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array av  RectangleF  strukturer som representerar rektanglarna som ska ritas. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Ritar en serie rektanglar som anges av  Rectangle  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  som bestämmer färgen, bredden och stilen på konturerna av rektanglarna. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array av  Rectangle  strukturer som representerar rektanglarna som ska ritas. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF struktur som specificerar det övre vänstra hörnet av den ritade texten. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF struktur som specificerar det övre vänstra hörnet av den ritade texten. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Ritar den angivna textsträngen i den angivna rektangeln med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur som specificerar placeringen av den ritade texten. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Ritar den angivna textsträngen i den angivna rektangeln med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur som specificerar placeringen av den ritade texten. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Ritar den angivna textsträngen på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Ritar den angivna textsträngen på Adobe-kompatibelt sätt i den angivna rektangeln med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten med hjälp av formateringsattributen för den angivna  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur som specificerar placeringen av den ritade texten. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Ritar den angivna textsträngen på Adobe-kompatibelt sätt på den angivna platsen med de angivna  com.aspose.psd.Brush  och  com.aspose.psd.Font  objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | java.lang.String | Sträng att rita. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  som definierar textformatet för strängen. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer färgen och texturen för den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Avslutar cachning av grafikoperationerna som startades efter att BeginUpdate anropades. De föregående grafikoperationerna kommer att tillämpas på en gång när denna metod anropas.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Fyller insidan av en sluten kardinal spline-kurva definierad av en array av com.aspose.psd.PointF strukturer. Denna metod använder en standardspänning på 0,5 och FillMode.Alternate fyllningsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av com.aspose.psd.PointF strukturer som definierar spline:n. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Fyller insidan av en sluten kardinal spline-kurva definierad av en array av com.aspose.psd.PointF strukturer med angivet fyllningsläge. Denna metod använder en standardspänning på 0,5.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av com.aspose.psd.PointF strukturer som definierar spline:n. |
| fyllningsläge | int | Medlem av com.aspose.psd.FillMode uppräkning som bestämmer hur kurvan fylls. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av  com.aspose.psd.PointF  strukturer med det angivna fyllningsläget och spänningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | En com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av com.aspose.psd.PointF strukturer som definierar spline:n. |
| fyllningsläge | int | Medlem av com.aspose.psd.FillMode uppräkning som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Fyller insidan av en sluten kardinal spline-kurva definierad av en array av com.aspose.psd.Point strukturer. Denna metod använder en standardspänning på 0,5 och FillMode.Alternate fyllningsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av com.aspose.psd.Point strukturer som definierar spline:n. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Fyller insidan av en sluten kardinal spline-kurva definierad av en array av com.aspose.psd.Point strukturer med angivet fyllningsläge. Denna metod använder en standardspänning på 0,5.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av com.aspose.psd.Point strukturer som definierar spline:n. |
| fyllningsläge | int | Medlem av com.aspose.psd.FillMode uppräkning som bestämmer hur kurvan fylls. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Fyller innanmätet av en sluten kardinalsplinekurva definierad av en array av  com.aspose.psd.Point  strukturer med det angivna fyllningsläget och spänning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av com.aspose.psd.Point strukturer som definierar spline:n. |
| fyllningsläge | int | Medlem av com.aspose.psd.FillMode uppräkning som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0.0F som specificerar kurvans spänning. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av en  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av en  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| x | float | x-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | float | y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| bredd | float | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| höjd | float | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Fyller innanmätet av en ellips definierad av en omslutande rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| x | int | x-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | int | y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| bredd | int | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| höjd | int | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Fyller innanmätet av en  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath som representerar sökvägen att fylla. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av en  com.aspose.psd.RectangleF  struktur och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle struktur som representerar den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| startvinkel | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | float | Vinkel i grader mätt medurs från parametern startAngle till den andra sidan av pajsektionen. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av en  com.aspose.psd.RectangleF  struktur och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur som representerar den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| startvinkel | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | float | Vinkel i grader mätt medurs från parametern startAngle till den andra sidan av pajsektionen. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| bredd | float | Bredden på den avgränsande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| höjd | float | Höjden på den avgränsande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| startvinkel | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | float | Vinkel i grader mätt medurs från parametern startAngle till den andra sidan av pajsektionen. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Fyller innanmätet av ett pajsegment definierat av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen varifrån pajsektionen kommer. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| bredd | int | Bredden på den avgränsande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| höjd | int | Höjden på den avgränsande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| startvinkel | int | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweepAngle | int | Vinkel i grader mätt medurs från parametern startAngle till den andra sidan av pajsektionen. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.PointF  strukturer och  FillMode.Alternate .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  com.aspose.psd.PointF  strukturer som representerar polygonens hörn som ska fyllas. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.PointF  strukturer med det angivna fyllningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array av  com.aspose.psd.PointF  strukturer som representerar polygonens hörn som ska fyllas. |
| fillMode | int | Medlem av  com.aspose.psd.FillMode  enumeration som bestämmer fyllningsstilen. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.Point  strukturer och  FillMode.Alternate .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  com.aspose.psd.Point  strukturer som representerar polygonens hörn som ska fyllas. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Fyller innanmätet av en polygon definierad av en array av punkter specificerade av  com.aspose.psd.Point  strukturer med det angivna fyllningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array av  com.aspose.psd.Point  strukturer som representerar polygonens hörn som ska fyllas. |
| fillMode | int | Medlem av  com.aspose.psd.FillMode  enumeration som bestämmer fyllningsstilen. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Fyller innanmätet av en rektangel specificerad av en  Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pensel  som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  struktur som representerar rektangeln som ska fyllas. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Fyller innanmätet av en rektangel specificerad av en  RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pensel  som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  struktur som representerar rektangeln som ska fyllas. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Fyller innanmätet av en rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pensel  som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| bredd | float | Bredden på rektangeln som ska fyllas. |
| höjd | float | Höjden på rektangeln som ska fyllas. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Fyller innanmätet av en rektangel specificerad av ett par koordinater, en bredd och en höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pensel  som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| bredd | int | Bredden på rektangeln som ska fyllas. |
| höjd | int | Höjden på rektangeln som ska fyllas. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Fyller innanmätet av en serie rektanglar specificerade av  RectangleF  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pensel  som bestämmer fyllningens egenskaper. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array av  Rectangle  strukturer som representerar rektanglarna som ska fyllas. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Fyller innanmätet av en serie rektanglar specificerade av  Rectangle  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Pensel  som bestämmer fyllningens egenskaper. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array av  Rectangle  strukturer som representerar rektanglarna som ska fyllas. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Fyller innanmätet av en  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush som bestämmer egenskaperna för fyllningen. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region  som representerar området som ska fyllas. |

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


Hämtar eller anger klippregionen.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Hämtar eller anger kompositkvaliteten.

**Returns:**
int - Kompositkvaliteten.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Hämtar den horisontella upplösningen för detta  com.aspose.psd.graphics.

**Returns:**
float - Värdet, i punkter per tum, för den horisontella upplösning som stöds av detta com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Hämtar den vertikala upplösningen för detta  com.aspose.psd.graphics.

**Returns:**
float - Värdet, i punkter per tum, för den vertikala upplösning som stöds av detta com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Hämtar bilden.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Hämtar eller anger interpolationsläget.

**Returns:**
int - Interpolationsläget.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Hämtar eller anger skalningen mellan världsenheter och sid‑enheter för detta com.aspose.psd.graphics.

**Returns:**
float - Skalningen mellan världsenheter och sid-enheter för detta com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Hämtar eller anger måttenheten som används för sidkoordinater i detta com.aspose.psd.graphics.

**Returns:**
int - Måttenheten som används för sidkoordinater i detta com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Hämtar eller anger bildalternativ, som används för att skapa målbara vektor‑bilder att rita.

Värde: Bildalternativen, som används för att skapa målbara vektorbilder att rita.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Hämtar eller anger jämningsläget.

**Returns:**
int - Jämningsläget.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Hämtar eller anger tips för textåtergivning.

**Returns:**
int - Textrenderingstips.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar eller anger en kopia av den geometriska världstransformationen för detta com.aspose.psd.graphics.

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


Hämtar ett värde som indikerar om grafik är i BeginUpdate‑anropstillstånd.

**Returns:**
boolean -  True  om grafik är i BeginUpdate-anropstillstånd; annars,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Mäter strängen med hjälp av klassen [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Teckensnittet. |
| text | java.lang.String | Texten. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Mäter strängen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Teckensnittet. |
|  | text | java.lang.String | Texten. |

--------------------

GDI-resultatet är nästan alltid ogiltigt för kursiv och ofta ogiltigt för fet stil. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Mäter den angivna textsträngen med angivna parametrar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att mäta. |
| font | [Font](../../com.aspose.psd/font) | Typsnittet att mäta. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Layoutområdet. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Strängformatet. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Hämta privat typsnittscache. |
| useMagicNumbersForStyles | boolean | om satt till  true  [använd magiska tal för stilar]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar com.aspose.psd.Matrix som representerar den lokala geometriska transformen för detta com.aspose.psd.Graphics med den angivna com.aspose.psd.Matrix genom att föregå den angivna com.aspose.psd.matrix.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Den  com.aspose.psd.Matrix  som används för att multiplicera den geometriska transformationen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar com.aspose.psd.Matrix som representerar den lokala geometriska transformen för detta com.aspose.psd.Graphics med den angivna com.aspose.psd.Matrix i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Den  com.aspose.psd.Matrix  som används för att multiplicera den geometriska transformationen. |
| ordning | int | En  com.aspose.psd.MatrixOrder  som specificerar i vilken ordning de två matriserna ska multipliceras. |

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


Återställer egenskapen com.aspose.psd.graphics.Transform till identitet.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformationen med den angivna mängden. Denna metod lägger till rotationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |
| ordning | int | En  com.aspose.psd.MatrixOrder  som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod lägger till skalningsmatrisen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Mängden att skala transformen i x‑axelns riktning. |
| sy | float | Mängden att skala transformen i y‑axelns riktning. |
| ordning | int | En  com.aspose.psd.MatrixOrder  som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Hämtar eller anger klippregionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Klippområdet. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Hämtar eller anger kompositkvaliteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Kompositkvaliteten. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Hämtar eller anger interpolationsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Interpolationsläget. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Hämtar eller anger skalningen mellan världsenheter och sid‑enheter för detta com.aspose.psd.graphics.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Skalningen mellan världsenheter och sid-enheter för detta com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Hämtar eller anger måttenheten som används för sidkoordinater i detta com.aspose.psd.graphics.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Måttenheten som används för sidkoordinater i detta com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Hämtar eller anger bildalternativ, som används för att skapa målbara vektor‑bilder att rita.

Värde: Bildalternativen, som används för att skapa målbara vektorbilder att rita.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Hämtar eller anger jämningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Utjämningsläget. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Hämtar eller anger tips för textåtergivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Tips för textrendering. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Hämtar eller anger en kopia av den geometriska världstransformationen för detta com.aspose.psd.graphics.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | En kopia av  com.aspose.psd.Matrix  som representerar den geometriska världstransformationen för detta  com.aspose.psd.graphics . |

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


Översätter den lokala geometriska transformen med de angivna dimensionerna. Denna metod lägger till översättningen i början av transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för översättningen i x. |
| dy | float | Värdet för översättningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för översättningen i x. |
| dy | float | Värdet för översättningen i y. |
| ordning | int | Ordningen (infoga i början eller i slutet) i vilken översättningen ska tillämpas. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

