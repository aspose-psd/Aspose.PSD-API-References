---
title: "Graphics"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt de graphics voor volgens de graphics-engine die in de huidige assembly wordt gebruikt."
type: docs
weight: 49
url: /nl/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Stelt de graphics voor volgens de graphics-engine die in de huidige assembly wordt gebruikt.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Initialiseert een nieuw exemplaar van de Graphics‑klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Haalt de groottecoëfficiënt van de vetgedrukte tekststijl op. |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Haalt de groottecoëfficiënt van de cursieve tekststijl op. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Past het effect toe. |
| [beginUpdate()](#beginUpdate--) | Start het cachen van de volgende grafische bewerkingen. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Wist het grafische oppervlak met de opgegeven kleur. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een Rectangle‑structuur. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een RectangleF‑structuur. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Tekent een Bézier‑spline gedefinieerd door vier Point‑structuren. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Tekent een Bézier‑spline gedefinieerd door vier PointF‑structuren. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Tekent een Bézier-spline gedefinieerd door vier geordende coördinaatparen die punten vertegenwoordigen. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Tekent een reeks Bézier-splines uit een array van  PointF  structuren. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Tekent een reeks Bézier-splines uit een array van  Point  structuren. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Tekent een gesloten cardinal-spline gedefinieerd door een array van  PointF  structuren. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Tekent een gesloten cardinal-spline gedefinieerd door een array van  PointF  structuren met een opgegeven spanning. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Tekent een gesloten cardinal-spline gedefinieerd door een array van  Point  structuren. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Tekent een gesloten cardinal-spline gedefinieerd door een array van  Point  structuren met een opgegeven spanning. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Tekent een cardinal-spline door een opgegeven array van  PointF  structuren. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Tekent een cardinal-spline door een opgegeven array van  PointF  structuren met een opgegeven spanning. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Tekent een cardinal-spline door een opgegeven array van  PointF  structuren. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Tekent een cardinal-spline door een opgegeven array van  PointF  structuren met een opgegeven spanning. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Tekent een cardinal-spline door een opgegeven array van  Point  structuren. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Tekent een cardinal-spline door een opgegeven array van  Point  structuren met een opgegeven spanning. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Tekent een cardinal-spline door een opgegeven array van  Point  structuren met een opgegeven spanning. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Tekent een ellips gespecificeerd door een begrenzende  Rectangle  structuur. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Tekent een ellips gedefinieerd door een begrenzende  RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Tekent de opgegeven  Image , met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Tekent de opgegeven  Image , met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Tekent de opgegeven  Image , met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Tekent de opgegeven afbeelding, met de oorspronkelijke fysieke grootte, op de locatie gespecificeerd door een coördinaatpaar. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Tekent de opgegeven afbeelding met de oorspronkelijke fysieke grootte op de locatie gespecificeerd door een coördinaatpaar. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Tekent de opgegeven afbeelding zonder schalen en knipt deze bij, indien nodig, om te passen in de opgegeven rechthoek. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Tekent een lijn die twee  Point  structuren verbindt. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Tekent een lijn die twee  PointF  structuren verbindt. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinaatparen. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinaatparen. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Tekent een reeks lijnsegmenten die een array van  PointF  structuren verbinden. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Tekent een reeks lijnsegmenten die een array van  Point  structuren verbinden. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Tekent een  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een  Rectangle  structuur en twee radiale lijnen. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een  RectangleF  structuur en twee radiale lijnen. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Tekent een veelhoek gedefinieerd door een array van  PointF  structuren. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Tekent een veelhoek gedefinieerd door een array van  Point  structuren. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Tekent een rechthoek gespecificeerd door een  Rectangle  structuur. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Tekent een rechthoek gespecificeerd door een  RectangleF  structuur. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Tekent een reeks rechthoeken gespecificeerd door  RectangleF  structuren. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Tekent een reeks rechthoeken gespecificeerd door  Rectangle  structuren. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Tekent de opgegeven tekenreeks op Adobe-compatibele wijze in de opgegeven rechthoek met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Tekent de opgegeven tekenreeks op Adobe-compatibele wijze op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten. |
| [endUpdate()](#endUpdate--) | Rondt het cachen van de grafische bewerkingen af die gestart zijn nadat BeginUpdate werd aangeroepen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.PointF  structuren. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.PointF  structuren, gebruikmakend van de opgegeven vulmodus. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.PointF  structuren, gebruikmakend van de opgegeven vulmodus en spanning. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.Point  structuren. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.Point  structuren, gebruikmakend van de opgegeven vulmodus. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.Point  structuren, gebruikmakend van de opgegeven vulmodus en spanning. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een  com.aspose.psd.Rectangle  structuur. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een  com.aspose.psd.RectangleF  structuur. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Vult het interieur van een  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een  com.aspose.psd.RectangleF  structuur en twee radiale lijnen. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een  com.aspose.psd.RectangleF  structuur en twee radiale lijnen. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.PointF  structuren en  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.PointF  structuren met de opgegeven vulmodus. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.Point  structuren en  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.Point  structuren met de opgegeven vulmodus. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Vult het interieur van een rechthoek gespecificeerd door een  Rectangle  structuur. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Vult het interieur van een rechthoek gespecificeerd door een  RectangleF  structuur. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Vult het interieur van een rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Vult het interieur van een rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Vult de interieurs van een reeks rechthoeken gespecificeerd door  RectangleF  structuren. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Vult de interieurs van een reeks rechthoeken gespecificeerd door  Rectangle  structuren. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Vult het interieur van een  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Haalt op of stelt de clipregio in. |
| [getCompositingQuality()](#getCompositingQuality--) | Haalt op of stelt de compositingkwaliteit in. |
| [getDpiX()](#getDpiX--) | Haalt de horizontale resolutie van deze com.aspose.psd.graphics op. |
| [getDpiY()](#getDpiY--) | Haalt de verticale resolutie van deze com.aspose.psd.graphics op. |
| [getImage()](#getImage--) | Haalt de afbeelding op. |
| [getInterpolationMode()](#getInterpolationMode--) | Haalt op of stelt de interpolatiemodus in. |
| [getPageScale()](#getPageScale--) | Haalt op of stelt de schaal tussen wereldeenheden en pagina-eenheden voor deze com.aspose.psd.graphics in. |
| [getPageUnit()](#getPageUnit--) | Haalt op of stelt de meeteenheid die wordt gebruikt voor paginacoördinaten in deze com.aspose.psd.graphics in. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Haalt op of stelt afbeeldingsopties in, gebruikt om schilderbare vectorafbeeldingen te maken om te tekenen. |
| [getSmoothingMode()](#getSmoothingMode--) | Haalt of stelt de smoothing-modus in. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Haalt of stelt de hint voor tekstopmaak in. |
| [getTransform()](#getTransform--) | Haalt of stelt een kopie van de geometrische wereldtransformatie voor deze  com.aspose.psd.graphics  in. |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Haalt een waarde op die aangeeft of graphics zich in de BeginUpdate‑aanroepstatus bevindt. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Meet de tekenreeks met behulp van de [GraphicsPath](../../com.aspose.psd/graphicspath)-klasse. |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Meet de tekenreeks. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Meet de opgegeven tekstreeks met opgegeven parameters |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Vermenigvuldigt de  com.aspose.psd.Matrix  die de lokale geometrische transformatie van deze  com.aspose.psd.Graphics  vertegenwoordigt met de opgegeven  com.aspose.psd.Matrix  door de opgegeven  com.aspose.psd.matrix  voor te voegen . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Vermenigvuldigt de  com.aspose.psd.Matrix  die de lokale geometrische transformatie van deze  com.aspose.psd.Graphics  vertegenwoordigt met de opgegeven  com.aspose.psd.Matrix  in de opgegeven volgorde. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Reset de  com.aspose.psd.graphics.Transform  eigenschap naar de identiteit. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Haalt op of stelt de clipregio in. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Haalt op of stelt de compositingkwaliteit in. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Haalt op of stelt de interpolatiemodus in. |
| [setPageScale(float value)](#setPageScale-float-) | Haalt op of stelt de schaal tussen wereldeenheden en pagina-eenheden voor deze com.aspose.psd.graphics in. |
| [setPageUnit(int value)](#setPageUnit-int-) | Haalt op of stelt de meeteenheid die wordt gebruikt voor paginacoördinaten in deze com.aspose.psd.graphics in. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Haalt op of stelt afbeeldingsopties in, gebruikt om schilderbare vectorafbeeldingen te maken om te tekenen. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Haalt of stelt de smoothing-modus in. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Haalt of stelt de hint voor tekstopmaak in. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Haalt of stelt een kopie van de geometrische wereldtransformatie voor deze  com.aspose.psd.graphics  in. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Initialiseert een nieuw exemplaar van de Graphics‑klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De bronafbeelding. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Haalt de groottecoëfficiënt van de vetgedrukte tekststijl op.

Gebruik van magische getallen omdat GDI altijd alleen metingen levert voor de reguliere stijl.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Haalt de groottecoëfficiënt van de cursieve tekststijl op.

Gebruik van magische getallen omdat GDI altijd alleen metingen levert voor de reguliere stijl.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Past het effect toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| effect | com.aspose.internal.IEffect | Het toe te passen effect. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Start het cachen van de volgende graphics-bewerkingen. De graphics-effecten die daarna worden toegepast, worden niet onmiddellijk toegepast; in plaats daarvan zorgt EndUpdate ervoor dat alle effecten in één keer worden toegepast.

Let op: de effecten na het aanroepen van BeginUpdate worden niet toegepast als EndUpdate niet wordt aangeroepen.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Wist het grafische oppervlak met de opgegeven kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | De kleur waarmee het graphics-oppervlak wordt gewist. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een Rectangle‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de boog bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | RectangleF  structuur die de grenzen van de ellips definieert. |
| startAngle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweepAngle | float | Hoek in graden gemeten met de klok mee vanaf de  startAngle  parameter tot het eindpunt van de boog. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een RectangleF‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de boog bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  structuur die de grenzen van de ellips definieert. |
| startAngle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweepAngle | float | Hoek in graden gemeten met de klok mee vanaf de  startAngle  parameter tot het eindpunt van de boog. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de boog bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van het rechthoek die de ellips definieert. |
| y | float | De y-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert. |
| breedte | float | Breedte van de rechthoek die de ellips definieert. |
| hoogte | float | Hoogte van de rechthoek die de ellips definieert. |
| startAngle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweepAngle | float | Hoek in graden gemeten met de klok mee vanaf de  startAngle  parameter tot het eindpunt van de boog. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de boog bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van het rechthoek die de ellips definieert. |
| y | int | De y-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert. |
| breedte | int | Breedte van de rechthoek die de ellips definieert. |
| hoogte | int | Hoogte van de rechthoek die de ellips definieert. |
| startAngle | int | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweepAngle | int | Hoek in graden gemeten met de klok mee vanaf de  startAngle  parameter tot het eindpunt van de boog. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Tekent een Bézier‑spline gedefinieerd door vier Point‑structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen-structuur die de kleur, breedte en stijl van de curve bepaalt. |
| pt1 | [Point](../../com.aspose.psd/point) | Point-structuur die het startpunt van de curve vertegenwoordigt. |
| pt2 | [Point](../../com.aspose.psd/point) | Point-structuur die het eerste controlepunt voor de curve vertegenwoordigt. |
| pt3 | [Point](../../com.aspose.psd/point) | Point-structuur die het tweede controlepunt voor de curve vertegenwoordigt. |
| pt4 | [Point](../../com.aspose.psd/point) | Point-structuur die het eindpunt van de curve vertegenwoordigt. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Tekent een Bézier‑spline gedefinieerd door vier PointF‑structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de curve bepaalt. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF-structuur die het startpunt van de curve vertegenwoordigt. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF-structuur die het eerste controlepunt voor de curve vertegenwoordigt. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF-structuur die het tweede controlepunt voor de curve vertegenwoordigt. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF-structuur die het eindpunt van de curve vertegenwoordigt. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Tekent een Bézier-spline gedefinieerd door vier geordende coördinaatparen die punten vertegenwoordigen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de curve bepaalt. |
| x1 | float | De x-coördinaat van het startpunt van de curve. |
| y1 | float | De y-coördinaat van het startpunt van de curve. |
| x2 | float | De x-coördinaat van het eerste controlepunt van de curve. |
| y2 | float | De y-coördinaat van het eerste controlepunt van de curve. |
| x3 | float | De x-coördinaat van het tweede controlepunt van de curve. |
| y3 | float | De y-coördinaat van het tweede controlepunt van de curve. |
| x4 | float | De x-coördinaat van het eindpunt van de curve. |
| y4 | float | De y-coördinaat van het eindpunt van de curve. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Tekent een reeks Bézier-splines uit een array van  PointF  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de punten vertegenwoordigen die de curve bepalen. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Tekent een reeks Bézier-splines uit een array van  Point  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de curve bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de punten vertegenwoordigen die de curve bepalen. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Teken een gesloten cardinal spline gedefinieerd door een array van  PointF  structuren. Deze methode gebruikt een standaard spanning van 0.5 en  FillMode.Alternate  vulmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de spline definiëren. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Teken een gesloten cardinal spline gedefinieerd door een array van  PointF  structuren met een opgegeven spanning. Deze methode gebruikt een standaard  FillMode.Alternate  vulmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de spline definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Teken een gesloten cardinal spline gedefinieerd door een array van  Point  structuren. Deze methode gebruikt een standaard spanning van 0.5 en  FillMode.Alternate  vulmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de spline definiëren. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Teken een gesloten cardinal spline gedefinieerd door een array van  Point  structuren met een opgegeven spanning. Deze methode gebruikt een standaard  FillMode.Alternate  vulmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de spline definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Teken een cardinal spline door een opgegeven array van  PointF  structuren. Deze methode gebruikt een standaard spanning van 0.5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de spline definiëren. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Tekent een cardinal-spline door een opgegeven array van  PointF  structuren met een opgegeven spanning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de punten vertegenwoordigen die de curve definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Teken een cardinal spline door een opgegeven array van  PointF  structuren. Het tekenen begint met een offset vanaf het begin van de array. Deze methode gebruikt een standaard spanning van 0.5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de spline definiëren. |
| offset | int | Offset van het eerste element in de array van de  points  parameter naar het startpunt in de curve. |
| numberOfSegments | int | Aantal segmenten na het startpunt die in de curve moeten worden opgenomen. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Teken een cardinal spline door een opgegeven array van  PointF  structuren met een opgegeven spanning. Het tekenen begint met een offset vanaf het begin van de array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de spline definiëren. |
| offset | int | Offset van het eerste element in de array van de  points  parameter naar het startpunt in de curve. |
| numberOfSegments | int | Aantal segmenten na het startpunt die in de curve moeten worden opgenomen. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Tekent een cardinal-spline door een opgegeven array van  Point  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de spline definiëren. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Tekent een cardinal-spline door een opgegeven array van  Point  structuren met een opgegeven spanning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de spline definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Tekent een cardinal-spline door een opgegeven array van  Point  structuren met een opgegeven spanning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de spline definiëren. |
| offset | int | Offset van het eerste element in de array van de  points  parameter naar het startpunt in de curve. |
| numberOfSegments | int | Aantal segmenten na het startpunt die in de curve moeten worden opgenomen. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Tekent een ellips gespecificeerd door een begrenzende  Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de ellips bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  structuur die de grenzen van de ellips definieert. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Tekent een ellips gedefinieerd door een begrenzende  RectangleF .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de ellips bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  structuur die de grenzen van de ellips definieert. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de ellips bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| y | float | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| breedte | float | Breedte van de begrenzende rechthoek die de ellips definieert. |
| hoogte | float | Hoogte van de begrenzende rechthoek die de ellips definieert. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de ellips bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| y | int | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| breedte | int | Breedte van de begrenzende rechthoek die de ellips definieert. |
| hoogte | int | Hoogte van de begrenzende rechthoek die de ellips definieert. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Tekent de opgegeven  Image , met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| point | [Point](../../com.aspose.psd/point) | Point  structuur die de locatie van de linkerbovenhoek van de getekende afbeelding weergeeft. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Tekent de opgegeven  Image , met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| point | [PointF](../../com.aspose.psd/pointf) | PointF  structuur die de linkerbovenhoek van de getekende afbeelding weergeeft. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array van drie PointF-structuren die een parallellogram definiëren. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array van drie PointF-structuren die een parallellogram definiëren. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | De bronrechthoek. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array van drie PointF-structuren die een parallellogram definiëren. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | De bronrechthoek. |
| srcUnit | int | De meeteenheden. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array van drie PointF-structuren die een parallellogram definiëren. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | De bronrechthoek. |
| srcUnit | int | De meeteenheden. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array van drie PointF-structuren die een parallellogram definiëren. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array van drie PointF-structuren die een parallellogram definiëren. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | De bronrechthoek. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array van drie PointF-structuren die een parallellogram definiëren. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | De bronrechthoek. |
| srcUnit | int | De meeteenheden. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Tekent het opgegeven gedeelte van de opgegeven  afbeelding  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te tekenen. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array van drie PointF-structuren die een parallellogram definiëren. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | De bronrechthoek. |
| srcUnit | int | De meeteenheden. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  structuur die de locatie en grootte van de getekende afbeelding specificeert. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | De rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | De rect destination. |
| graphicsUnit | int | De grafische eenheid. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | De rect source. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | De rect destination. |
| graphicsUnit | int | De grafische eenheid. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | De bestemmingsrechthoek. |
| graphicsUnit | int | De grafische eenheid. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | De bestemmingsrechthoek. |
| graphicsUnit | int | De grafische eenheid. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  structuur die de locatie en grootte van de getekende afbeelding specificeert. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | De rect source. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | De rect destination. |
| graphicsUnit | int | De grafische eenheid. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | De bronrechthoek. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | De bestemmingsrechthoek. |
| graphicsUnit | int | De te gebruiken grafische eenheid. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | De te gebruiken afbeeldingseigenschappen. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | De bestemmingsrechthoek. |
| graphicsUnit | int | De grafische eenheid. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | De bestemmingsrechthoek waarin getekend moet worden. |
| graphicsUnit | int | De grafische eenheid. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Tekent de opgegeven  Image , met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| breedte | float | Breedte van de getekende afbeelding. |
| hoogte | float | Height of the drawn image. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Tekent de opgegeven afbeelding, met de oorspronkelijke fysieke grootte, op de locatie gespecificeerd door een coördinaatpaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Tekent de opgegeven  Image  op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| breedte | int | Breedte van de getekende afbeelding. |
| hoogte | int | Height of the drawn image. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| point | [Point](../../com.aspose.psd/point) | Point  structuur die de linkerbovenhoek van de getekende afbeelding specificeert. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  die de linkerbovenhoek van de getekende afbeelding specificeert. De X- en Y-eigenschappen van de rechthoek geven de linkerbovenhoek aan. De Breedte- en Hoogte-eigenschappen worden genegeerd. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Tekent de opgegeven afbeelding met de oorspronkelijke fysieke grootte op de locatie gespecificeerd door een coördinaatpaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| breedte | int | De parameter wordt niet gebruikt. |
| hoogte | int | De parameter wordt niet gebruikt. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Tekent de opgegeven afbeelding zonder schalen en knipt deze bij, indien nodig, om te passen in de opgegeven rechthoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  Rectangle  waarin de afbeelding getekend moet worden. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Tekent een lijn die twee  Point  structuren verbindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de lijn bepaalt. |
| point1 | [Point](../../com.aspose.psd/point) | Point  structuur die het eerste te verbinden punt vertegenwoordigt. |
| point2 | [Point](../../com.aspose.psd/point) | Point  structuur die het tweede te verbinden punt vertegenwoordigt. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Tekent een lijn die twee  PointF  structuren verbindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de lijn bepaalt. |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF  structuur die het eerste te verbinden punt vertegenwoordigt. |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF  structuur die het tweede te verbinden punt vertegenwoordigt. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinaatparen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de lijn bepaalt. |
| x1 | float | De x-coördinaat van het eerste punt. |
| y1 | float | De y-coördinaat van het eerste punt. |
| x2 | float | De x-coördinaat van het tweede punt. |
| y2 | float | De y-coördinaat van het tweede punt. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinaatparen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de lijn bepaalt. |
| x1 | int | De x-coördinaat van het eerste punt. |
| y1 | int | De y-coördinaat van het eerste punt. |
| x2 | int | De x-coördinaat van het tweede punt. |
| y2 | int | De y-coördinaat van het tweede punt. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Tekent een reeks lijnsegmenten die een array van  PointF  structuren verbinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de lijnsegmenten bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de te verbinden punten vertegenwoordigen. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Tekent een reeks lijnsegmenten die een array van  Point  structuren verbinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de lijnsegmenten bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de te verbinden punten vertegenwoordigen. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Tekent een  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen  die de kleur, breedte en stijl van het pad bepaalt. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  om te tekenen. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een  Rectangle  structuur en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de taartvorm bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert waaruit de taartvorm ontstaat. |
| startAngle | float | Hoek gemeten in graden met de klok mee vanaf de x-as naar de eerste zijde van de taartvorm. |
| sweepAngle | float | Hoek gemeten in graden met de klok mee vanaf de  startAngle  parameter naar de tweede zijde van de taartvorm. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een  RectangleF  structuur en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de taartvorm bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert waaruit de taartvorm ontstaat. |
| startAngle | float | Hoek gemeten in graden met de klok mee vanaf de x-as naar de eerste zijde van de taartvorm. |
| sweepAngle | float | Hoek gemeten in graden met de klok mee vanaf de  startAngle  parameter naar de tweede zijde van de taartvorm. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de taartvorm bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| y | float | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| breedte | float | Breedte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| hoogte | float | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| startAngle | float | Hoek gemeten in graden met de klok mee vanaf de x-as naar de eerste zijde van de taartvorm. |
| sweepAngle | float | Hoek gemeten in graden met de klok mee vanaf de  startAngle  parameter naar de tweede zijde van de taartvorm. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  die de kleur, breedte en stijl van de taartvorm bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| y | int | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| breedte | int | Breedte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| hoogte | int | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| startAngle | int | Hoek gemeten in graden met de klok mee vanaf de x-as naar de eerste zijde van de taartvorm. |
| sweepAngle | int | Hoek gemeten in graden met de klok mee vanaf de  startAngle  parameter naar de tweede zijde van de taartvorm. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Tekent een veelhoek gedefinieerd door een array van  PointF  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van het veelhoek bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  PointF  structuren die de hoekpunten van het veelhoek vertegenwoordigen. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Tekent een veelhoek gedefinieerd door een array van  Point  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van het veelhoek bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  Point  structuren die de hoekpunten van het veelhoek vertegenwoordigen. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Tekent een rechthoek gespecificeerd door een  Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Een  Pen  die de kleur, breedte en stijl van de rechthoek bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een  Rectangle  structuur die de te tekenen rechthoek vertegenwoordigt. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Tekent een rechthoek gespecificeerd door een  RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Een  Pen  die de kleur, breedte en stijl van de rechthoek bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  RectangleF  structuur die de te tekenen rechthoek vertegenwoordigt. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Een  Pen  die de kleur, breedte en stijl van de rechthoek bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| breedte | float | De breedte van de te tekenen rechthoek. |
| hoogte | float | De hoogte van de te tekenen rechthoek. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de rechthoek bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| breedte | int | Breedte van de te tekenen rechthoek. |
| hoogte | int | Hoogte van de te tekenen rechthoek. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Tekent een reeks rechthoeken gespecificeerd door  RectangleF  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de contouren van de rechthoeken bepaalt. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array van  RectangleF  structuren die de te tekenen rechthoeken vertegenwoordigen. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Tekent een reeks rechthoeken gespecificeerd door  Rectangle  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen die de kleur, breedte en stijl van de contouren van de rechthoeken bepaalt. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array van  Rectangle  structuren die de te tekenen rechthoeken vertegenwoordigen. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF structuur die de linkerbovenhoek van de getekende tekst specificeert. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF structuur die de linkerbovenhoek van de getekende tekst specificeert. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat die opmaak‑attributen specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF structuur die de locatie van de getekende tekst specificeert. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF structuur die de locatie van de getekende tekst specificeert. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat die opmaak‑attributen specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat die opmaak‑attributen specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Tekent de opgegeven tekenreeks op Adobe-compatibele wijze in de opgegeven rechthoek met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten, gebruikmakend van de opmaakkenmerken van de opgegeven  com.aspose.psd.stringFormat .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF structuur die de locatie van de getekende tekst specificeert. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat die opmaak‑attributen specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Tekent de opgegeven tekenreeks op Adobe-compatibele wijze op de opgegeven locatie met de opgegeven  com.aspose.psd.Brush  en  com.aspose.psd.Font  objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | java.lang.String | String om te tekenen. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font die het tekstformaat van de string definieert. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kleur en textuur van de getekende tekst bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Rondt het cachen van de grafische bewerkingen af die zijn gestart nadat BeginUpdate is aangeroepen. De voorafgaande grafische bewerkingen worden in één keer toegepast bij het aanroepen van deze methode.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Vult de binnenkant van een gesloten kardinale spline‑curve die wordt gedefinieerd door een array van com.aspose.psd.PointF-structuren. Deze methode gebruikt een standaard spanning van 0,5 en de vulmodus FillMode.Alternate.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van com.aspose.psd.PointF-structuren die de spline definiëren. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Vult de binnenkant van een gesloten kardinale spline‑curve die wordt gedefinieerd door een array van com.aspose.psd.PointF-structuren met de opgegeven vulmodus. Deze methode gebruikt een standaard spanning van 0,5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van com.aspose.psd.PointF-structuren die de spline definiëren. |
| vulmodus | int | Lid van de com.aspose.psd.FillMode-enumeratie die bepaalt hoe de curve wordt gevuld. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.PointF  structuren, gebruikmakend van de opgegeven vulmodus en spanning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Een com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van com.aspose.psd.PointF-structuren die de spline definiëren. |
| vulmodus | int | Lid van de com.aspose.psd.FillMode-enumeratie die bepaalt hoe de curve wordt gevuld. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Vult de binnenkant van een gesloten kardinale spline‑curve die wordt gedefinieerd door een array van com.aspose.psd.Point-structuren. Deze methode gebruikt een standaard spanning van 0,5 en de vulmodus FillMode.Alternate.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van com.aspose.psd.Point-structuren die de spline definiëren. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Vult de binnenkant van een gesloten kardinale spline‑curve die wordt gedefinieerd door een array van com.aspose.psd.Point-structuren met de opgegeven vulmodus. Deze methode gebruikt een standaard spanning van 0,5.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van com.aspose.psd.Point-structuren die de spline definiëren. |
| vulmodus | int | Lid van de com.aspose.psd.FillMode-enumeratie die bepaalt hoe de curve wordt gevuld. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Vult het binnenste van een gesloten cardinal spline curve die gedefinieerd is door een array van  com.aspose.psd.Point  structuren, gebruikmakend van de opgegeven vulmodus en spanning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van com.aspose.psd.Point-structuren die de spline definiëren. |
| vulmodus | int | Lid van de com.aspose.psd.FillMode-enumeratie die bepaalt hoe de curve wordt gevuld. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle-structuur die de begrenzende rechthoek weergeeft die de ellips definieert. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF-structuur die de begrenzende rechthoek weergeeft die de ellips definieert. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| y | float | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| breedte | float | Breedte van de begrenzende rechthoek die de ellips definieert. |
| hoogte | float | Hoogte van de begrenzende rechthoek die de ellips definieert. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Vult het interieur van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| y | int | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert. |
| breedte | int | Breedte van de begrenzende rechthoek die de ellips definieert. |
| hoogte | int | Hoogte van de begrenzende rechthoek die de ellips definieert. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Vult het interieur van een  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath die het pad weergeeft dat moet worden gevuld. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een  com.aspose.psd.RectangleF  structuur en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle-structuur die de begrenzende rechthoek weergeeft die de ellips definieert waaruit het taartsegment komt. |
| startAngle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweepAngle | float | Hoek in graden gemeten met de klok mee vanaf de parameter startAngle tot de tweede zijde van het taartsegment. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een  com.aspose.psd.RectangleF  structuur en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF-structuur die de begrenzende rechthoek weergeeft die de ellips definieert waaruit het taartsegment komt. |
| startAngle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweepAngle | float | Hoek in graden gemeten met de klok mee vanaf de parameter startAngle tot de tweede zijde van het taartsegment. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| y | float | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| breedte | float | Breedte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| hoogte | float | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| startAngle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweepAngle | float | Hoek in graden gemeten met de klok mee vanaf de parameter startAngle tot de tweede zijde van het taartsegment. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Vult het interieur van een taartsegment gedefinieerd door een ellips gespecificeerd door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| y | int | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| breedte | int | Breedte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| hoogte | int | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| startAngle | int | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweepAngle | int | Hoek in graden gemeten met de klok mee vanaf de parameter startAngle tot de tweede zijde van het taartsegment. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.PointF  structuren en  FillMode.Alternate .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  com.aspose.psd.PointF  structuren die de hoekpunten van het in te vullen polygon vertegenwoordigen. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.PointF  structuren met de opgegeven vulmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array van  com.aspose.psd.PointF  structuren die de hoekpunten van het in te vullen polygon vertegenwoordigen. |
| fillMode | int | Lid van de  com.aspose.psd.FillMode  enumeratie die de stijl van de vulling bepaalt. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.Point  structuren en  FillMode.Alternate .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  com.aspose.psd.Point  structuren die de hoekpunten van het in te vullen polygon vertegenwoordigen. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Vult het interieur van een veelhoek gedefinieerd door een array van punten gespecificeerd door  com.aspose.psd.Point  structuren met de opgegeven vulmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array van  com.aspose.psd.Point  structuren die de hoekpunten van het in te vullen polygon vertegenwoordigen. |
| fillMode | int | Lid van de  com.aspose.psd.FillMode  enumeratie die de stijl van de vulling bepaalt. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Vult het interieur van een rechthoek gespecificeerd door een  Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  die de kenmerken van de vulling bepaalt. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  structuur die het te vullen rechthoek vertegenwoordigt. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Vult het interieur van een rechthoek gespecificeerd door een  RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  die de kenmerken van de vulling bepaalt. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  structuur die het te vullen rechthoek vertegenwoordigt. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Vult het interieur van een rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  die de kenmerken van de vulling bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van het te vullen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van het te vullen rechthoek. |
| breedte | float | Breedte van het te vullen rechthoek. |
| hoogte | float | Hoogte van het te vullen rechthoek. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Vult het interieur van een rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  die de kenmerken van de vulling bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van het te vullen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van het te vullen rechthoek. |
| breedte | int | Breedte van het te vullen rechthoek. |
| hoogte | int | Hoogte van het te vullen rechthoek. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Vult de interieurs van een reeks rechthoeken gespecificeerd door  RectangleF  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  die de kenmerken van de vulling bepaalt. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array van  Rectangle  structuren die de te vullen rechthoeken vertegenwoordigen. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Vult de interieurs van een reeks rechthoeken gespecificeerd door  Rectangle  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush  die de kenmerken van de vulling bepaalt. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array van  Rectangle  structuren die de te vullen rechthoeken vertegenwoordigen. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Vult het interieur van een  com.aspose.psd.region .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush die de kenmerken van de vulling bepaalt. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region  die het te vullen gebied vertegenwoordigt. |

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


Haalt op of stelt de clipregio in.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Haalt op of stelt de compositingkwaliteit in.

**Returns:**
int - De compositiekwaliteit.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Haalt de horizontale resolutie van deze com.aspose.psd.graphics op.

**Returns:**
float - De waarde, in dots per inch, voor de horizontale resolutie die door deze com.aspose.psd.graphics wordt ondersteund.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Haalt de verticale resolutie van deze com.aspose.psd.graphics op.

**Returns:**
float - De waarde, in dots per inch, voor de verticale resolutie die door deze com.aspose.psd.graphics wordt ondersteund.
### getImage() {#getImage--}
```
public Image getImage()
```


Haalt de afbeelding op.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Haalt op of stelt de interpolatiemodus in.

**Returns:**
int - De interpolatiemodus.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Haalt op of stelt de schaal tussen wereldeenheden en pagina-eenheden voor deze com.aspose.psd.graphics in.

**Returns:**
float - De schaal tussen wereldeenheden en paginaneenheden voor deze com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Haalt op of stelt de meeteenheid die wordt gebruikt voor paginacoördinaten in deze com.aspose.psd.graphics in.

**Returns:**
int - De meeteenheid die wordt gebruikt voor paginacoördinaten in deze com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Haalt op of stelt afbeeldingsopties in, gebruikt om schilderbare vectorafbeeldingen te maken om te tekenen.

Waarde: De afbeeldingopties, gebruikt om schilderbare vectorafbeeldingen te maken om te tekenen.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Haalt of stelt de smoothing-modus in.

**Returns:**
int - De verzachtingsmodus.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Haalt of stelt de hint voor tekstopmaak in.

**Returns:**
int - De hint voor tekstweergave.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Haalt of stelt een kopie van de geometrische wereldtransformatie voor deze  com.aspose.psd.graphics  in.

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


Haalt een waarde op die aangeeft of graphics zich in de BeginUpdate‑aanroepstatus bevindt.

**Returns:**
boolean -  True  als graphics zich in de BeginUpdate-aanroepstatus bevindt; anders,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Meet de tekenreeks met behulp van de [GraphicsPath](../../com.aspose.psd/graphicspath)-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Het lettertype. |
| tekst | java.lang.String | De tekst. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Meet de tekenreeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Het lettertype. |
|  | tekst | java.lang.String | De tekst. |

--------------------

GDI-resultaat is bijna altijd niet geldig voor cursieve en vaak niet geldig voor vette stijlen. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Meet de opgegeven tekstreeks met opgegeven parameters

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekst | java.lang.String | De te meten tekst. |
| font | [Font](../../com.aspose.psd/font) | Het lettertype om te meten. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Het lay-outgebied. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Het tekenreeksformaat. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | De private lettertypecache ophalen. |
| useMagicNumbersForStyles | boolean | indien ingesteld op  true  [gebruik magische getallen voor stijlen]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Vermenigvuldigt de  com.aspose.psd.Matrix  die de lokale geometrische transformatie van deze  com.aspose.psd.Graphics  vertegenwoordigt met de opgegeven  com.aspose.psd.Matrix  door de opgegeven  com.aspose.psd.matrix  voor te voegen .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De  com.aspose.psd.Matrix  waarmee de geometrische transformatie wordt vermenigvuldigd. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Vermenigvuldigt de  com.aspose.psd.Matrix  die de lokale geometrische transformatie van deze  com.aspose.psd.Graphics  vertegenwoordigt met de opgegeven  com.aspose.psd.Matrix  in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De  com.aspose.psd.Matrix  waarmee de geometrische transformatie wordt vermenigvuldigd. |
| volgorde | int | Een  com.aspose.psd.MatrixOrder  die aangeeft in welke volgorde de twee matrices worden vermenigvuldigd. |

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


Reset de  com.aspose.psd.graphics.Transform  eigenschap naar de identiteit.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode voegt de rotatie vooraan toe aan de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |
| volgorde | int | Een  com.aspose.psd.MatrixOrder  die aangeeft of de rotatiematrix moet worden toegevoegd of voorafgeplaatst. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De hoeveelheid waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie in de y-richting wordt geschaald. |
| volgorde | int | Een  com.aspose.psd.MatrixOrder  die aangeeft of de schaalmatrix moet worden toegevoegd of voorafgeplaatst. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Haalt op of stelt de clipregio in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Het clipgebied. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Haalt op of stelt de compositingkwaliteit in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De compositiekwaliteit. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Haalt op of stelt de interpolatiemodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De interpolatiemodus. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Haalt op of stelt de schaal tussen wereldeenheden en pagina-eenheden voor deze com.aspose.psd.graphics in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De schaal tussen wereldeenheden en pagina-eenheden voor deze com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Haalt op of stelt de meeteenheid die wordt gebruikt voor paginacoördinaten in deze com.aspose.psd.graphics in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De meeteenheid die wordt gebruikt voor paginacoördinaten in deze com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Haalt op of stelt afbeeldingsopties in, gebruikt om schilderbare vectorafbeeldingen te maken om te tekenen.

Waarde: De afbeeldingopties, gebruikt om schilderbare vectorafbeeldingen te maken om te tekenen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Haalt of stelt de smoothing-modus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De verzachtingsmodus. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Haalt of stelt de hint voor tekstopmaak in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De tekstweergavetip. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Haalt of stelt een kopie van de geometrische wereldtransformatie voor deze  com.aspose.psd.graphics  in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Een kopie van de  com.aspose.psd.Matrix  die de geometrische wereldtransformatie voor deze  com.aspose.psd.graphics  vertegenwoordigt. |

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


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| volgorde | int | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

