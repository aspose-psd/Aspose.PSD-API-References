---
title: "Graphics"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt die Grafiken gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar."
type: docs
weight: 49
url: /de/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Stellt die Grafiken gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Initialisiert eine neue Instanz der  Graphics  Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Ermittelt den Größenkoeffizienten des fetten Textstils |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Ermittelt den Größenkoeffizienten des kursiven Textstils |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Wendet den Effekt an. |
| [beginUpdate()](#beginUpdate--) | Startet das Zwischenspeichern der folgenden Grafikoperationen. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Löscht die Grafikfläche mit der angegebenen Farbe. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine  Rectangle  Struktur angegeben ist. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine RectangleF-Struktur angegeben ist. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Zeichnet eine Bézier-Kurve, die durch vier Point-Strukturen definiert ist. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Zeichnet eine Bézier-Kurve, die durch vier PointF-Strukturen definiert ist. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Zeichnet eine Bézier-Kurve, die durch vier geordnete Koordinatenpaare definiert ist, die Punkte darstellen. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Zeichnet eine Reihe von Bézier-Kurven aus einem Array von PointF-Strukturen. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Zeichnet eine Reihe von Bézier-Kurven aus einem Array von Point-Strukturen. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Zeichnet eine geschlossene kardinale Spline, die durch ein Array von PointF-Strukturen definiert ist. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Zeichnet eine geschlossene kardinale Spline, die durch ein Array von PointF-Strukturen definiert ist und eine angegebene Spannung verwendet. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Zeichnet eine geschlossene kardinale Spline, die durch ein Array von Point-Strukturen definiert ist. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Zeichnet eine geschlossene kardinale Spline, die durch ein Array von Point-Strukturen definiert ist und eine angegebene Spannung verwendet. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Zeichnet eine kardinale Spline durch ein angegebenes Array von PointF-Strukturen. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Zeichnet eine kardinale Spline durch ein angegebenes Array von PointF-Strukturen und verwendet eine angegebene Spannung. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Zeichnet eine kardinale Spline durch ein angegebenes Array von PointF-Strukturen. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Zeichnet eine kardinale Spline durch ein angegebenes Array von PointF-Strukturen und verwendet eine angegebene Spannung. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Zeichnet eine kardinale Spline durch ein angegebenes Array von Point-Strukturen. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Zeichnet eine kardinale Spline durch ein angegebenes Array von Point-Strukturen und verwendet eine angegebene Spannung. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Zeichnet eine kardinale Spline durch ein angegebenes Array von Point-Strukturen und verwendet eine angegebene Spannung. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Zeichnet eine Ellipse, die durch eine begrenzende Rectangle-Struktur angegeben ist. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Zeichnet eine Ellipse, die durch eine begrenzende RectangleF definiert ist. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben wird. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben wird. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Zeichnet das angegebene Image, verwendet seine ursprüngliche physische Größe und platziert es am angegebenen Ort. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Zeichnet das angegebene Image, verwendet seine ursprüngliche physische Größe und platziert es am angegebenen Ort. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Zeichnet das angegebene Image, verwendet seine ursprüngliche physische Größe und platziert es am angegebenen Ort. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Zeichnet das angegebene Bild, verwendet seine ursprüngliche physische Größe und platziert es an dem durch ein Koordinatenpaar angegebenen Ort. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Zeichnet das angegebene Bild, das seine ursprüngliche physische Größe verwendet, an dem durch ein Koordinatenpaar angegebenen Ort. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Zeichnet eine Linie, die zwei  Point  Strukturen verbindet. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Zeichnet eine Linie, die zwei  PointF  Strukturen verbindet. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von  PointF  Strukturen verbinden. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von  Point  Strukturen verbinden. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Zeichnet einen  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine  Rectangle  Struktur und zwei Radiallinien angegeben wird. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine  RectangleF  Struktur und zwei Radiallinien angegeben wird. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Zeichnet ein Polygon, das durch ein Array von  PointF  Strukturen definiert ist. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Zeichnet ein Polygon, das durch ein Array von  Point  Strukturen definiert ist. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Zeichnet ein Rechteck, das durch eine  Rectangle  Struktur angegeben wird. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Zeichnet ein Rechteck, das durch eine  RectangleF  Struktur angegeben wird. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Zeichnet eine Reihe von Rechtecken, die durch  RectangleF  Strukturen angegeben werden. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Zeichnet eine Reihe von Rechtecken, die durch  Rectangle  Strukturen angegeben werden. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Zeichnet die angegebene Textzeichenfolge in Adobe-kompatibler Weise im angegebenen Rechteck mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Zeichnet die angegebene Textzeichenfolge in Adobe-kompatibler Weise am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten. |
| [endUpdate()](#endUpdate--) | Beendet das Caching der Grafikoperationen, die nach dem Aufruf von BeginUpdate gestartet wurden. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Füllt das Innere einer geschlossenen Cardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.PointF  Strukturen definiert ist. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Füllt das Innere einer geschlossenen Cardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.PointF  Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.PointF  Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.Point  Strukturen definiert ist. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.Point  Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.Point  Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch eine  com.aspose.psd.Rectangle  Struktur. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch eine  com.aspose.psd.RectangleF  Struktur. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Füllt das Innere eines  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine  com.aspose.psd.RectangleF  Struktur und zwei Radiallinien. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine  com.aspose.psd.RectangleF  Struktur und zwei Radiallinien. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.PointF  Strukturen und  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.PointF  Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.Point  Strukturen und  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.Point  Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Füllt das Innere eines Rechtecks, angegeben durch eine  Rectangle  Struktur. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Füllt das Innere eines Rechtecks, angegeben durch eine  RectangleF  Struktur. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Füllt die Innenräume einer Reihe von Rechtecken, angegeben durch  RectangleF  Strukturen. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Füllt die Innenräume einer Reihe von Rechtecken, angegeben durch  Rectangle  Strukturen. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Füllt das Innere einer  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Liest oder setzt den Clip-Bereich. |
| [getCompositingQuality()](#getCompositingQuality--) | Liest oder setzt die Kompositierungsqualität. |
| [getDpiX()](#getDpiX--) | Liest die horizontale Auflösung dieses com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Liest die vertikale Auflösung dieses com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Liest das Bild. |
| [getInterpolationMode()](#getInterpolationMode--) | Liest oder setzt den Interpolationsmodus. |
| [getPageScale()](#getPageScale--) | Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem com.aspose.psd.graphics verwendet wird. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Liest oder setzt Bildoptionen, die zum Erstellen von zeichnungsfähigen Vektor‑Bildern verwendet werden. |
| [getSmoothingMode()](#getSmoothingMode--) | Liest oder setzt den Glättungsmodus. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Liest oder setzt den Hinweis zur Textdarstellung. |
| [getTransform()](#getTransform--) | Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Liest einen Wert, der angibt, ob die Grafik sich im BeginUpdate‑Aufrufzustand befindet. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Misst die Zeichenkette mithilfe der Klasse [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Misst die Zeichenkette. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Misst die angegebene Textzeichenkette mit den angegebenen Parametern |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multipliziert die  com.aspose.psd.Matrix , die die lokale geometrische Transformation dieses  com.aspose.psd.Graphics  darstellt, mit der angegebenen  com.aspose.psd.Matrix , indem die angegebene  com.aspose.psd.matrix  vorangestellt wird. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multipliziert die  com.aspose.psd.Matrix , die die lokale geometrische Transformation dieses  com.aspose.psd.Graphics  darstellt, mit der angegebenen  com.aspose.psd.Matrix  in der angegebenen Reihenfolge. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Setzt die Eigenschaft  com.aspose.psd.graphics.Transform  auf die Identität zurück. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Liest oder setzt den Clip-Bereich. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Liest oder setzt die Kompositierungsqualität. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Liest oder setzt den Interpolationsmodus. |
| [setPageScale(float value)](#setPageScale-float-) | Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem com.aspose.psd.graphics verwendet wird. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Liest oder setzt Bildoptionen, die zum Erstellen von zeichnungsfähigen Vektor‑Bildern verwendet werden. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Liest oder setzt den Glättungsmodus. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Liest oder setzt den Hinweis zur Textdarstellung. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Initialisiert eine neue Instanz der  Graphics  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Quellbild. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Ermittelt den Größenkoeffizienten des fetten Textstils

Verwendung von magischen Zahlen, da GDI stets Messungen nur für den regulären Stil liefert.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Ermittelt den Größenkoeffizienten des kursiven Textstils

Verwendung von magischen Zahlen, da GDI stets Messungen nur für den regulären Stil liefert.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Wendet den Effekt an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Effekt | com.aspose.internal.IEffect | Der anzuwendende Effekt. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Startet das Zwischenspeichern der folgenden Grafikoperationen. Die danach angewendeten Grafikeffekte werden nicht sofort angewendet; stattdessen bewirkt EndUpdate, dass alle Effekte auf einmal angewendet werden.

Hinweis: Die Effekte, die nach dem Aufruf von BeginUpdate auftreten, werden nicht angewendet, falls EndUpdate nicht aufgerufen wird.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Löscht die Grafikfläche mit der angegebenen Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Die Farbe, mit der die Grafikoberfläche gelöscht wird. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine  Rectangle  Struktur angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stift  der die Farbe, Breite und den Stil des Bogens bestimmt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | RectangleF  Struktur, die die Grenzen der Ellipse definiert. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter  startAngle  zum Endpunkt des Bogens. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine RectangleF-Struktur angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stift  der die Farbe, Breite und den Stil des Bogens bestimmt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  Struktur, die die Grenzen der Ellipse definiert. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter  startAngle  zum Endpunkt des Bogens. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stift  der die Farbe, Breite und den Stil des Bogens bestimmt. |
| x | float | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| Breite | float | Breite des Rechtecks, das die Ellipse definiert. |
| Höhe | float | Höhe des Rechtecks, das die Ellipse definiert. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter  startAngle  zum Endpunkt des Bogens. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Stift  der die Farbe, Breite und den Stil des Bogens bestimmt. |
| x | int | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| Breite | int | Breite des Rechtecks, das die Ellipse definiert. |
| Höhe | int | Höhe des Rechtecks, das die Ellipse definiert. |
| startAngle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter  startAngle  zum Endpunkt des Bogens. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Zeichnet eine Bézier-Kurve, die durch vier Point-Strukturen definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen-Struktur, die die Farbe, Breite und den Stil der Kurve bestimmt. |
| pt1 | [Point](../../com.aspose.psd/point) | Point-Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [Point](../../com.aspose.psd/point) | Point-Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [Point](../../com.aspose.psd/point) | Point-Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [Point](../../com.aspose.psd/point) | Point-Struktur, die den Endpunkt der Kurve darstellt. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Zeichnet eine Bézier-Kurve, die durch vier PointF-Strukturen definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, der die Farbe, Breite und den Stil der Kurve bestimmt. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF-Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF-Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF-Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF-Struktur, die den Endpunkt der Kurve darstellt. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Zeichnet eine Bézier-Kurve, die durch vier geordnete Koordinatenpaare definiert ist, die Punkte darstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, der die Farbe, Breite und den Stil der Kurve bestimmt. |
| x1 | float | Die x-Koordinate des Startpunkts der Kurve. |
| y1 | float | Die y-Koordinate des Startpunkts der Kurve. |
| x2 | float | Die x-Koordinate des ersten Kontrollpunkts der Kurve. |
| y2 | float | Die y-Koordinate des ersten Kontrollpunkts der Kurve. |
| x3 | float | Die x-Koordinate des zweiten Kontrollpunkts der Kurve. |
| y3 | float | Die y-Koordinate des zweiten Kontrollpunkts der Kurve. |
| x4 | float | Die x-Koordinate des Endpunkts der Kurve. |
| y4 | float | Die y-Koordinate des Endpunkts der Kurve. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Zeichnet eine Reihe von Bézier-Kurven aus einem Array von PointF-Strukturen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, der die Farbe, Breite und den Stil der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Zeichnet eine Reihe von Bézier-Kurven aus einem Array von Point-Strukturen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen, der die Farbe, Breite und den Stil der Kurve bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Zeichnet einen geschlossenen kardinalen Spline, definiert durch ein Array von  PointF  Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und  FillMode.Alternate  Füllmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die den Spline definieren. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Zeichnet einen geschlossenen kardinalen Spline, definiert durch ein Array von  PointF  Strukturen, unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard-  FillMode.Alternate  Füllmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die den Spline definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Zeichnet einen geschlossenen kardinalen Spline, definiert durch ein Array von  Point  Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und  FillMode.Alternate  Füllmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die den Spline definieren. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Zeichnet einen geschlossenen kardinalen Spline, definiert durch ein Array von  Point  Strukturen, unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard-  FillMode.Alternate  Füllmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die den Spline definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Zeichnet einen kardinalen Spline durch ein angegebenes Array von  PointF  Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die den Spline definieren. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Zeichnet eine kardinale Spline durch ein angegebenes Array von PointF-Strukturen und verwendet eine angegebene Spannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Zeichnet einen kardinalen Spline durch ein angegebenes Array von  PointF  Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die den Spline definieren. |
| Versatz | int | Versatz vom ersten Element im Array des  points  Parameters zum Startpunkt der Kurve. |
| numberOfSegments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Zeichnet eine kardinale Spline durch ein angegebenes Array von  PointF  Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die den Spline definieren. |
| Versatz | int | Versatz vom ersten Element im Array des  points  Parameters zum Startpunkt der Kurve. |
| numberOfSegments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Zeichnet eine kardinale Spline durch ein angegebenes Array von Point-Strukturen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die den Spline definieren. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Zeichnet eine kardinale Spline durch ein angegebenes Array von Point-Strukturen und verwendet eine angegebene Spannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die den Spline definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Zeichnet eine kardinale Spline durch ein angegebenes Array von Point-Strukturen und verwendet eine angegebene Spannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  das die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die den Spline definieren. |
| Versatz | int | Versatz vom ersten Element im Array des  points  Parameters zum Startpunkt der Kurve. |
| numberOfSegments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Zeichnet eine Ellipse, die durch eine begrenzende Rectangle-Struktur angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  Struktur, die die Grenzen der Ellipse definiert. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Zeichnet eine Ellipse, die durch eine begrenzende RectangleF definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  Struktur, die die Grenzen der Ellipse definiert. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | float | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| Breite | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| Höhe | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | int | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| Breite | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| Höhe | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Zeichnet das angegebene Image, verwendet seine ursprüngliche physische Größe und platziert es am angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](../../com.aspose.psd/point) | Point  Struktur, die den Ort der oberen linken Ecke des gezeichneten Bildes darstellt. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Zeichnet das angegebene Image, verwendet seine ursprüngliche physische Größe und platziert es am angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| point | [PointF](../../com.aspose.psd/pointf) | PointF  Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Das Quellrechteck. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Das Quellrechteck. |
| srcUnit | int | Die Maßeinheiten. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Das Quellrechteck. |
| srcUnit | int | Die Maßeinheiten. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Die Bildeigenschaften. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Das Quellrechteck. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Das Quellrechteck. |
| srcUnit | int | Die Maßeinheiten. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das Bild zum Zeichnen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array von drei PointF  Strukturen, die ein Parallelogramm definieren. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Das Quellrechteck. |
| srcUnit | int | Die Maßeinheiten. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Die Bildeigenschaften. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Das rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Das rect destination. |
| graphicsUnit | int | Die Grafik‑Einheit. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Das rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Das rect destination. |
| graphicsUnit | int | Die Grafik‑Einheit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Die Bildeigenschaften. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Das Zielrechteck. |
| graphicsUnit | int | Die Grafik‑Einheit. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Das Zielrechteck. |
| graphicsUnit | int | Die Grafik‑Einheit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Die Bildeigenschaften. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Das rect source. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Das rect destination. |
| graphicsUnit | int | Die Grafik‑Einheit. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Das Quellrechteck. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Das Zielrechteck. |
| graphicsUnit | int | Die zu verwendende Grafik‑Einheit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Die zu verwendenden Bildeigenschaften. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Das Zielrechteck. |
| graphicsUnit | int | Die Grafik‑Einheit. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Das Zielrechteck, in das gezeichnet wird. |
| graphicsUnit | int | Die Grafik‑Einheit. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Die Bildeigenschaften. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Zeichnet das angegebene Image, verwendet seine ursprüngliche physische Größe und platziert es am angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| Breite | float | Breite des gezeichneten Bildes. |
| Höhe | float | Höhe des gezeichneten Bildes. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Zeichnet das angegebene Bild, verwendet seine ursprüngliche physische Größe und platziert es an dem durch ein Koordinatenpaar angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Zeichnet das angegebene Image am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| Breite | int | Breite des gezeichneten Bildes. |
| Höhe | int | Höhe des gezeichneten Bildes. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](../../com.aspose.psd/point) | Point  Struktur, die die obere linke Ecke des gezeichneten Bildes angibt. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  das die obere linke Ecke des gezeichneten Bildes angibt. Die X- und Y-Eigenschaften des Rechtecks geben die obere linke Ecke an. Die Breite- und Höhe-Eigenschaften werden ignoriert. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Zeichnet das angegebene Bild, das seine ursprüngliche physische Größe verwendet, an dem durch ein Koordinatenpaar angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| Breite | int | Der Parameter wird nicht verwendet. |
| Höhe | int | Der Parameter wird nicht verwendet. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das  Rectangle  in dem das Bild gezeichnet wird. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Zeichnet eine Linie, die zwei  Point  Strukturen verbindet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Linie. |
| point1 | [Point](../../com.aspose.psd/point) | Point  Struktur, die den ersten zu verbindenden Punkt darstellt. |
| point2 | [Point](../../com.aspose.psd/point) | Point  Struktur, die den zweiten zu verbindenden Punkt darstellt. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Zeichnet eine Linie, die zwei  PointF  Strukturen verbindet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Linie. |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF  Struktur, die den ersten zu verbindenden Punkt darstellt. |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF  Struktur, die den zweiten zu verbindenden Punkt darstellt. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Linie. |
| x1 | float | Die x-Koordinate des ersten Punktes. |
| y1 | float | Die y-Koordinate des ersten Punktes. |
| x2 | float | Die x-Koordinate des zweiten Punktes. |
| y2 | float | Die y-Koordinate des zweiten Punktes. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Linie. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Zeichnet eine Reihe von Liniensegmenten, die ein Array von  PointF  Strukturen verbinden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die die zu verbindenden Punkte darstellen. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Zeichnet eine Reihe von Liniensegmenten, die ein Array von  Point  Strukturen verbinden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die die zu verbindenden Punkte darstellen. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Zeichnet einen  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen  bestimmt die Farbe, Breite und den Stil des Pfads. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  zum Zeichnen. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine  Rectangle  Struktur und zwei Radiallinien angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform entsteht. |
| startAngle | float | Winkel gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | float | Winkel gemessen in Grad im Uhrzeigersinn vom  startAngle  Parameter zur zweiten Seite der Kuchenform. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch eine  RectangleF  Struktur und zwei Radiallinien angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | float | Winkel gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | float | Winkel gemessen in Grad im Uhrzeigersinn vom  startAngle  Parameter zur zweiten Seite der Kuchenform. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Breite | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Höhe | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | float | Winkel gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | float | Winkel gemessen in Grad im Uhrzeigersinn vom  startAngle  Parameter zur zweiten Seite der Kuchenform. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Zeichnet eine Kuchenform, die durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Kuchenform. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Breite | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| Höhe | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Kuchenform stammt. |
| startAngle | int | Winkel gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Kuchenform. |
| sweepAngle | int | Winkel gemessen in Grad im Uhrzeigersinn vom  startAngle  Parameter zur zweiten Seite der Kuchenform. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Zeichnet ein Polygon, das durch ein Array von  PointF  Strukturen definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil des Polygons. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  PointF  Strukturen, die die Eckpunkte des Polygons darstellen. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Zeichnet ein Polygon, das durch ein Array von  Point  Strukturen definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil des Polygons. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  Point  Strukturen, die die Eckpunkte des Polygons darstellen. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Zeichnet ein Rechteck, das durch eine  Rectangle  Struktur angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ein  Pen  bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Ein  Rectangle  Struktur, die das zu zeichnende Rechteck darstellt. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Zeichnet ein Rechteck, das durch eine  RectangleF  Struktur angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ein  Pen  bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Ein  RectangleF  Struktur, die das zu zeichnende Rechteck darstellt. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ein  Pen  bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| x | float | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| Breite | float | Die Breite des zu zeichnenden Rechtecks. |
| Höhe | float | Die Höhe des zu zeichnenden Rechtecks. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil des Rechtecks. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| Breite | int | Breite des zu zeichnenden Rechtecks. |
| Höhe | int | Höhe des zu zeichnenden Rechtecks. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Zeichnet eine Reihe von Rechtecken, die durch  RectangleF  Strukturen angegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Umrisse der Rechtecke. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array von  RectangleF  Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Zeichnet eine Reihe von Rechtecken, die durch  Rectangle  Strukturen angegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  bestimmt die Farbe, Breite und den Stil der Umrisse der Rechtecke. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array von  Rectangle  Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF Struktur, die die obere linke Ecke des gezeichneten Textes festlegt. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF Struktur, die die obere linke Ecke des gezeichneten Textes festlegt. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, das Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF Struktur, die den Ort des gezeichneten Textes festlegt. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF Struktur, die den Ort des gezeichneten Textes festlegt. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, das Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Textes. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, das Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Zeichnet die angegebene Textzeichenfolge in Adobe-kompatibler Weise im angegebenen Rechteck mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten unter Verwendung der Formatattribute des angegebenen  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF Struktur, die den Ort des gezeichneten Textes festlegt. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, das Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Zeichnet die angegebene Textzeichenfolge in Adobe-kompatibler Weise am angegebenen Ort mit den angegebenen  com.aspose.psd.Brush  und  com.aspose.psd.Font  Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | java.lang.String | Zeichenkette zum Zeichnen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, der das Textformat der Zeichenkette definiert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Textes. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Beendet das Zwischenspeichern der Grafikoperationen, die nach dem Aufruf von BeginUpdate gestartet wurden. Die vorherigen Grafikoperationen werden beim Aufruf dieser Methode sofort angewendet.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von com.aspose.psd.PointF Strukturen definiert ist. Diese Methode verwendet eine Standard‑Spannung von 0,5 und den Füllmodus FillMode.Alternate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von com.aspose.psd.PointF Strukturen, die den Spline definieren. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von com.aspose.psd.PointF Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standard‑Spannung von 0,5.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von com.aspose.psd.PointF Strukturen, die den Spline definieren. |
| Füllmodus | int | Mitglied der Aufzählung com.aspose.psd.FillMode, die bestimmt, wie die Kurve gefüllt wird. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.PointF  Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Ein com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von com.aspose.psd.PointF Strukturen, die den Spline definieren. |
| Füllmodus | int | Mitglied der Aufzählung com.aspose.psd.FillMode, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von com.aspose.psd.Point Strukturen definiert ist. Diese Methode verwendet eine Standard‑Spannung von 0,5 und den Füllmodus FillMode.Alternate.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von com.aspose.psd.Point Strukturen, die den Spline definieren. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von com.aspose.psd.Point Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standard‑Spannung von 0,5.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von com.aspose.psd.Point Strukturen, die den Spline definieren. |
| Füllmodus | int | Mitglied der Aufzählung com.aspose.psd.FillMode, die bestimmt, wie die Kurve gefüllt wird. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von  com.aspose.psd.Point  Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von com.aspose.psd.Point Strukturen, die den Spline definieren. |
| Füllmodus | int | Mitglied der Aufzählung com.aspose.psd.FillMode, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch eine  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch eine  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| Breite | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| Höhe | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Füllt das Innere einer Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| x | int | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| Breite | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| Höhe | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Füllt das Innere eines  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath, der den zu füllenden Pfad darstellt. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine  com.aspose.psd.RectangleF  Struktur und zwei Radiallinien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zur zweiten Seite des Kuchenstücks. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch eine  com.aspose.psd.RectangleF  Struktur und zwei Radiallinien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zur zweiten Seite des Kuchenstücks. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Breite | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Höhe | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zur zweiten Seite des Kuchenstücks. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| x | int | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Breite | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| Höhe | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kuchenabschnitt stammt. |
| startAngle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweepAngle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zur zweiten Seite des Kuchenstücks. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.PointF  Strukturen und  FillMode.Alternate .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  com.aspose.psd.PointF  Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.PointF  Strukturen, unter Verwendung des angegebenen Füllmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array von  com.aspose.psd.PointF  Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |
| fillMode | int | Element der  com.aspose.psd.FillMode  Aufzählung, die den Füllstil bestimmt. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.Point  Strukturen und  FillMode.Alternate .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  com.aspose.psd.Point  Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch  com.aspose.psd.Point  Strukturen, unter Verwendung des angegebenen Füllmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array von  com.aspose.psd.Point  Strukturen, die die Eckpunkte des auszufüllenden Polygons darstellen. |
| fillMode | int | Element der  com.aspose.psd.FillMode  Aufzählung, die den Füllstil bestimmt. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Füllt das Innere eines Rechtecks, angegeben durch eine  Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  Struktur, die das auszufüllende Rechteck darstellt. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Füllt das Innere eines Rechtecks, angegeben durch eine  RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  der die Eigenschaften der Füllung bestimmt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  Struktur, die das auszufüllende Rechteck darstellt. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  der die Eigenschaften der Füllung bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| Breite | float | Breite des auszufüllenden Rechtecks. |
| Höhe | float | Höhe des auszufüllenden Rechtecks. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  der die Eigenschaften der Füllung bestimmt. |
| x | int | Die x‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des auszufüllenden Rechtecks. |
| Breite | int | Breite des auszufüllenden Rechtecks. |
| Höhe | int | Höhe des auszufüllenden Rechtecks. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Füllt die Innenräume einer Reihe von Rechtecken, angegeben durch  RectangleF  Strukturen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  der die Eigenschaften der Füllung bestimmt. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array von  Rectangle  Strukturen, die die auszufüllenden Rechtecke darstellen. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Füllt die Innenräume einer Reihe von Rechtecken, angegeben durch  Rectangle  Strukturen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  der die Eigenschaften der Füllung bestimmt. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array von  Rectangle  Strukturen, die die auszufüllenden Rechtecke darstellen. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Füllt das Innere einer  com.aspose.psd.region .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, der die Eigenschaften der Füllung bestimmt. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region  die den auszufüllenden Bereich darstellt. |

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


Liest oder setzt den Clip-Bereich.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Liest oder setzt die Kompositierungsqualität.

**Returns:**
int - Die Kompositierungsqualität.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Liest die horizontale Auflösung dieses com.aspose.psd.graphics.

**Returns:**
float - Der Wert in Punkten pro Zoll für die horizontale Auflösung, die von diesem com.aspose.psd.graphics unterstützt wird.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Liest die vertikale Auflösung dieses com.aspose.psd.graphics.

**Returns:**
float - Der Wert in Punkten pro Zoll für die vertikale Auflösung, die von diesem com.aspose.psd.graphics unterstützt wird.
### getImage() {#getImage--}
```
public Image getImage()
```


Liest das Bild.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Liest oder setzt den Interpolationsmodus.

**Returns:**
int - Der Interpolationsmodus.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses com.aspose.psd.graphics.

**Returns:**
float - Die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem com.aspose.psd.graphics verwendet wird.

**Returns:**
int - Die Maßeinheit, die für Seitenkoordinaten in diesem com.aspose.psd.graphics verwendet wird.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Liest oder setzt Bildoptionen, die zum Erstellen von zeichnungsfähigen Vektor‑Bildern verwendet werden.

Wert: Die Bildoptionen, die verwendet werden, um malbare Vektor‑Bilder zu zeichnen.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Liest oder setzt den Glättungsmodus.

**Returns:**
int - Der Glättungsmodus.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Liest oder setzt den Hinweis zur Textdarstellung.

**Returns:**
int - Der Textdarstellungs‑Hinweis.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses  com.aspose.psd.graphics .

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


Liest einen Wert, der angibt, ob die Grafik sich im BeginUpdate‑Aufrufzustand befindet.

**Returns:**
boolesch -  True  wenn graphics sich im BeginUpdate-Aufrufzustand befindet; andernfalls  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Misst die Zeichenkette mithilfe der Klasse [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Die Schriftart. |
| text | java.lang.String | Der Text. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Misst die Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Die Schriftart. |
|  | text | java.lang.String | Der Text. |

--------------------

GDI-Ergebnis ist fast immer ungültig für Kursiv und oft ungültig für Fett‑Stile. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Misst die angegebene Textzeichenkette mit den angegebenen Parametern

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu messende Text. |
| font | [Font](../../com.aspose.psd/font) | Die zu messende Schriftart. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Der Layout‑Bereich. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Das Zeichenkettenformat. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Der Abruf des privaten Schriftarten-Caches. |
| useMagicNumbersForStyles | boolean | wenn auf  true  gesetzt [magic numbers für Stile verwenden]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die  com.aspose.psd.Matrix , die die lokale geometrische Transformation dieses  com.aspose.psd.Graphics  darstellt, mit der angegebenen  com.aspose.psd.Matrix , indem die angegebene  com.aspose.psd.matrix  vorangestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die  com.aspose.psd.Matrix  mit der die geometrische Transformation multipliziert wird. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die  com.aspose.psd.Matrix , die die lokale geometrische Transformation dieses  com.aspose.psd.Graphics  darstellt, mit der angegebenen  com.aspose.psd.Matrix  in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Die  com.aspose.psd.Matrix  mit der die geometrische Transformation multipliziert wird. |
| Reihenfolge | int | Ein  com.aspose.psd.MatrixOrder  der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

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


Setzt die Eigenschaft  com.aspose.psd.graphics.Transform  auf die Identität zurück.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | float | Der Rotationswinkel. |
| Reihenfolge | int | Ein  com.aspose.psd.MatrixOrder  der angibt, ob die Rotationsmatrix angehängt oder vorangestellt werden soll. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungsmatrix der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Der Betrag, um den die Transformation in x-Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y-Richtung skaliert wird. |
| Reihenfolge | int | Ein  com.aspose.psd.MatrixOrder  der angibt, ob die Skalierungsmatrix angehängt oder vorangestellt werden soll. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Liest oder setzt den Clip-Bereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Der Clip‑Bereich. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Liest oder setzt die Kompositierungsqualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Kompositierungsqualität. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Liest oder setzt den Interpolationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Interpolationsmodus. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses com.aspose.psd.graphics.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem com.aspose.psd.graphics verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Maßeinheit, die für Seitenkoordinaten in diesem com.aspose.psd.graphics verwendet wird. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Liest oder setzt Bildoptionen, die zum Erstellen von zeichnungsfähigen Vektor‑Bildern verwendet werden.

Wert: Die Bildoptionen, die verwendet werden, um malbare Vektor‑Bilder zu zeichnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Liest oder setzt den Glättungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Glättungsmodus. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Liest oder setzt den Hinweis zur Textdarstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hinweis zur Textdarstellung. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Eine Kopie der  com.aspose.psd.Matrix  die die geometrische Welttransformation für dieses  com.aspose.psd.graphics  darstellt. |

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


Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | float | Der Wert der Translation in x. |
| dy | float | Der Wert der Translation in y. |
| Reihenfolge | int | Die Reihenfolge (voranstellen oder anhängen), in der die Translation angewendet wird. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

