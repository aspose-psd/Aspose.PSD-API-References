---
title: "Klasse Graphics"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Graphics‑Klasse. Stellt die Grafik gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar."
type: docs
weight: 4780
url: /de/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Stellt die Grafik gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar.

```csharp
public sealed class Graphics
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Graphics](graphics/)(Image) | Initialisiert eine neue Instanz der `Graphics`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Liest oder setzt den Clip‑Bereich. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Liest oder setzt die Kompositierungsqualität. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Liest die horizontale Auflösung dieses Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Liest die vertikale Auflösung dieses Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Liest das Bild. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Liest oder setzt den Interpolationsmodus. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Liest einen Wert, der angibt, ob die Grafik sich im BeginUpdate‑Aufrufzustand befindet. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem Aspose.PSD.Graphics verwendet wird. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Liest oder setzt Bildoptionen, die zum Erstellen von zeichnungsfähigen Vektor‑Bildern verwendet werden. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Liest oder setzt den Glättungsmodus. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Liest oder setzt den Hinweis zur Textdarstellung. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses `Graphics`. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Startet das Zwischenspeichern der folgenden Grafikoperationen. Die danach angewendeten Grafikeffekte werden nicht sofort angewendet; stattdessen bewirkt EndUpdate, dass alle Effekte auf einmal angewendet werden. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Löscht die Grafikoberfläche mit der angegebenen Farbe. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine [`Rectangle`](../rectangle/)-Struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine [`RectangleF`](../rectanglef/)-Struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Zeichnet eine Bézier‑Kurve, definiert durch vier [`Point`](../point/)-Strukturen. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Zeichnet eine Bézier‑Kurve, die durch vier [`PointF`](../pointf/) Strukturen definiert ist. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Zeichnet eine Bézier‑Kurve, die durch vier geordnete Koordinatenpaare definiert ist, die Punkte darstellen. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [`PointF`](../pointf/) Strukturen. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [`Point`](../point/) Strukturen. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Zeichnet einen geschlossenen Kardinal‑Spline, definiert durch ein Array von [`PointF`](../pointf/) Strukturen. Diese Methode verwendet eine Standard‑Spannung von 0,5 und den alternativen Füllmodus. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Zeichnet einen geschlossenen Kardinal‑Spline, definiert durch ein Array von [`Point`](../point/) Strukturen. Diese Methode verwendet eine Standard‑Spannung von 0,5 und den alternativen Füllmodus. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Zeichnet einen geschlossenen Kardinal‑Spline, definiert durch ein Array von [`PointF`](../pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den standardmäßigen alternativen Füllmodus. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Zeichnet einen geschlossenen Kardinal‑Spline, definiert durch ein Array von [`Point`](../point/) Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den standardmäßigen alternativen Füllmodus. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`PointF`](../pointf/) Strukturen. Diese Methode verwendet eine Standard‑Spannung von 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`Point`](../point/) Strukturen. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`PointF`](../pointf/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`Point`](../point/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`PointF`](../pointf/) Strukturen. Das Zeichnen beginnt versetzt vom Anfang des Arrays. Diese Methode verwendet eine Standard‑Spannung von 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`PointF`](../pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Das Zeichnen beginnt versetzt vom Anfang des Arrays. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Zeichnet einen Kardinal‑Spline durch ein angegebenes Array von [`Point`](../point/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Zeichnet eine Ellipse, die durch eine begrenzende [`Rectangle`](../rectangle/) Struktur angegeben ist. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Zeichnet eine Ellipse, definiert durch eine begrenzende [`RectangleF`](../rectanglef/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben wird. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Zeichnet eine Ellipse, definiert durch ein begrenzendes Rechteck, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben wird. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Zeichnet das angegebene [`Image`](./image/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Zeichnet das angegebene [`Image`](./image/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Zeichnet das angegebene [`Image`](./image/), unter Verwendung seiner ursprünglichen physischen Größe, am angegebenen Ort. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Zeichnet das angegebene Bild, unter Verwendung seiner ursprünglichen physischen Größe, an dem durch ein Koordinatenpaar angegebenen Ort. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Zeichnet den angegebenen Teil des angegebenen *Bildes* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene [`Image`](./image/) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Zeichnet das angegebene Bild, das seine ursprüngliche physische Größe verwendet, an dem durch ein Koordinatenpaar angegebenen Ort. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Zeichnet ein angegebenes Bild, das seine ursprüngliche physische Größe verwendet, an einem angegebenen Ort. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Zeichnet eine Linie, die zwei [`Point`](../point/) Strukturen verbindet. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Zeichnet eine Linie, die zwei [`PointF`](../pointf/) Strukturen verbindet. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [`PointF`](../pointf/) Strukturen verbinden. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [`Point`](../point/) Strukturen verbinden. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Zeichnet einen [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Zeichnet eine Kuchenform, definiert durch eine Ellipse, die durch eine [`Rectangle`](../rectangle/) Struktur und zwei Radiallinien angegeben ist. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Zeichnet eine Kuchenform, definiert durch eine Ellipse, die durch eine [`RectangleF`](../rectanglef/) Struktur und zwei Radiallinien angegeben ist. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Zeichnet eine Kuchenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Zeichnet eine Kuchenform, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Zeichnet ein Polygon, definiert durch ein Array von [`PointF`](../pointf/) Strukturen. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Zeichnet ein Polygon, definiert durch ein Array von [`Point`](../point/) Strukturen. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Zeichnet ein Rechteck, das durch eine [`Rectangle`](../rectangle/) Struktur angegeben ist. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Zeichnet ein Rechteck, das durch eine [`RectangleF`](../rectanglef/) Struktur angegeben ist. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Zeichnet eine Reihe von Rechtecken, die durch [`RectangleF`](../rectanglef/) Strukturen angegeben sind. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Zeichnet eine Reihe von Rechtecken, die durch [`Rectangle`](../rectangle/) Strukturen angegeben sind. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [`Brush`](../brush/) und [`Font`](../font/) Objekten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [`Brush`](../brush/) und [`Font`](../font/) Objekten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [`Brush`](../brush/) und [`Font`](../font/) Objekten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [`Brush`](../brush/) und [`Font`](../font/) Objekten unter Verwendung der Formatattribute des angegebenen [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [`Brush`](../brush/) und [`Font`](../font/) Objekten unter Verwendung der Formatattribute des angegebenen [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [`Brush`](../brush/) und [`Font`](../font/) Objekten unter Verwendung der Formatattribute des angegebenen [`StringFormat`](../stringformat/). |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Beendet das Zwischenspeichern der Grafikoperationen, die nach dem Aufruf von BeginUpdate gestartet wurden. Die vorherigen Grafikoperationen werden beim Aufruf dieser Methode sofort angewendet. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, definiert durch ein Array von [`PointF`](../pointf/) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den alternativen Füllmodus. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, definiert durch ein Array von [`Point`](../point/) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den alternativen Füllmodus. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, definiert durch ein Array von [`PointF`](../pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, definiert durch ein Array von [`Point`](../point/) Strukturen, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, definiert durch ein Array von [`PointF`](../pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Füllt das Innere einer geschlossenen Kardinal‑Spline‑Kurve, die durch ein Array von [`Point`](../point/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [`Rectangle`](../rectangle/) Struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch eine [`RectangleF`](../rectanglef/) Struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Füllt das Innere eines [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, die durch eine [`RectangleF`](../rectanglef/) Struktur angegeben ist, und zwei Radiallinien. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, die durch eine [`RectangleF`](../rectanglef/) Struktur angegeben ist, und zwei Radiallinien. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Füllt das Innere eines Kuchenabschnitts, definiert durch eine Ellipse, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben ist. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [`PointF`](../pointf/) Strukturen und Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [`Point`](../point/) Strukturen und Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [`PointF`](../pointf/) Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Füllt das Innere eines Polygons, definiert durch ein Array von Punkten, angegeben durch [`Point`](../point/) Strukturen, unter Verwendung des angegebenen Füllmodus. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Füllt das Innere eines Rechtecks, angegeben durch eine [`Rectangle`](../rectangle/) Struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Füllt das Innere eines Rechtecks, angegeben durch eine [`RectangleF`](../rectanglef/) Struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Füllt das Innere eines Rechtecks, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [`RectangleF`](../rectanglef/) Strukturen. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Füllt die Innenbereiche einer Reihe von Rechtecken, angegeben durch [`Rectangle`](../rectangle/) Strukturen. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Füllt das Innere eines [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Multipliziert die [`Matrix`](../matrix/), die die lokale geometrische Transformation dieses `Graphics` darstellt, mit der angegebenen [`Matrix`](../matrix/), indem die angegebene [`Matrix`](../matrix/) vorangestellt wird. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multipliziert die [`Matrix`](../matrix/), die die lokale geometrische Transformation dieses `Graphics` darstellt, mit der angegebenen [`Matrix`](../matrix/) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Setzt die [`Transform`](./transform/) Eigenschaft auf die Identität zurück. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Rotiert die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation vor die Transformation. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rotiert die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode stellt die Skalierungs-Matrix vor die Transformation. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation am Anfang der Transformation ein. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Übersetzt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

## Beispiele

Dieses Beispiel verwendet die Graphics class, um primitive Formen auf der Image Oberfläche zu erstellen. Um den Vorgang zu demonstrieren, erstellt das Beispiel ein neues Image im PSD‑Format und zeichnet primitive Formen auf der Image Oberfläche mithilfe der von der Graphics class bereitgestellten Draw‑Methoden, um es anschließend in das PSD‑Dateiformat zu exportieren.

```csharp
[C#]

//Erstelle eine Instanz von Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Zeichnen Sie einen Bogen, indem Sie das Pen‑Objekt mit schwarzer Farbe angeben, 
    //ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep‑Winkel
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Zeichnen Sie eine Bézier-Kurve, indem Sie das Pen‑Objekt mit blauer Farbe und Koordinatenpunkten angeben.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Zeichnen Sie eine Kurve, indem Sie das Pen‑Objekt mit grüner Farbe und einem Array von Punkten angeben
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Zeichnen Sie eine Ellipse mit dem Pen‑Objekt und einem umgebenden Rechteck
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Zeichnen Sie eine Linie 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Zeichnen Sie ein Kuchen‑Segment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Zeichnen Sie ein Polygon, indem Sie das Pen‑Objekt mit roter Farbe und einem Array von Punkten angeben
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Zeichnen Sie ein Rechteck
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Erstellen Sie ein SolidBrush‑Objekt und setzen Sie dessen verschiedene Eigenschaften
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Zeichnen Sie einen String mit dem SolidBrush-Objekt und Font an einem bestimmten Punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Erstellen Sie eine Instanz von PngOptions und setzen Sie deren verschiedene Eigenschaften
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Speichere alle Änderungen.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


