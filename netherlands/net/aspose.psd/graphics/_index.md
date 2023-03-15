---
title: Class Graphics
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Graphics klas. Vertegenwoordigt de grafische weergave volgens de grafische engine die in de huidige assembly wordt gebruikt.
type: docs
weight: 4310
url: /nl/net/aspose.psd/graphics/
---
## Graphics class

Vertegenwoordigt de grafische weergave volgens de grafische engine die in de huidige assembly wordt gebruikt.

```csharp
public sealed class Graphics
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Graphics](graphics/)(Image) | Initialiseert een nieuw exemplaar van het`Graphics` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Haalt of stelt het clipgebied in. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Haalt of stelt de compositiekwaliteit in. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Krijgt de horizontale resolutie van deze Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Krijgt de verticale resolutie van deze Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Krijgt de afbeelding. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Haalt of stelt de interpolatiemodus in. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Krijgt een waarde die aangeeft of de afbeelding zich in de BeginUpdate-aanroepstatus bevindt. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Haalt of stelt de schaal in tussen wereldeenheden en pagina-eenheden voor deze Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Hiermee wordt de maateenheid voor paginacoördinaten in deze Aspose.PSD.Graphics. opgehaald of ingesteld |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Hiermee wordt de afvlakmodus opgehaald of ingesteld. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Haalt de hint voor tekstweergave op of stelt deze in. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Haalt of stelt hiervoor een kopie van de geometrische wereldtransformatie in`Graphics` . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Start het cachen van de volgende grafische bewerkingen. De grafische effecten die daarna worden toegepast, worden niet onmiddellijk toegepast, maar de EndUpdate zorgt ervoor dat alle effecten in één keer worden toegepast. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Maakt het grafische oppervlak leeg met de opgegeven kleur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Tekent een boog die een deel van een ellips vertegenwoordigt, gespecificeerd door a[`Rectangle`](../rectangle/)structuur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Tekent een boog die een deel van een ellips vertegenwoordigt, gespecificeerd door a[`RectangleF`](../rectanglef/)structuur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Tekent een boog die een deel van een ellips vertegenwoordigt, gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Tekent een boog die een deel van een ellips vertegenwoordigt, gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Tekent een Bézier-spline gedefinieerd door vier[`Point`](../point/) structuren. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Tekent een Bézier-spline gedefinieerd door vier[`PointF`](../pointf/) structuren. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Tekent een Bézier-spline gedefinieerd door vier geordende paar coördinaten die punten vertegenwoordigen. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Tekent een reeks Bézier-splines uit een reeks van[`PointF`](../pointf/) structuren. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Tekent een reeks Bézier-splines uit een reeks van[`Point`](../point/) structuren. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Tekent een gesloten kardinale spline gedefinieerd door een array van[`PointF`](../pointf/) structuren. Deze methode gebruikt een standaardspanning van 0,5 enAlternate vulmodus. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Tekent een gesloten kardinale spline gedefinieerd door een array van[`Point`](../point/) structuren. Deze methode gebruikt een standaardspanning van 0,5 enAlternate vulmodus. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Tekent een gesloten kardinale spline gedefinieerd door een array van[`PointF`](../pointf/) constructies met een bepaalde spanning. Deze methode gebruikt een standaardAlternate vulmodus. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Tekent een gesloten kardinale spline gedefinieerd door een array van[`Point`](../point/) constructies met een bepaalde spanning. Deze methode gebruikt een standaardAlternate vulmodus. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../pointf/) structuren. Deze methode gebruikt een standaardspanning van 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Tekent een kardinale spline door een gespecificeerde reeks van[`Point`](../point/) structuren. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../pointf/) constructies met een gespecificeerde spanning. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Tekent een kardinale spline door een gespecificeerde reeks van[`Point`](../point/) constructies met een gespecificeerde spanning. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../pointf/) structuren. De tekening begint offset vanaf het begin van de array. Deze methode gebruikt een standaardspanning van 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Tekent een kardinale spline door een gespecificeerde reeks van[`PointF`](../pointf/) constructies met een bepaalde spanning. De tekening begint offset vanaf het begin van de array. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Tekent een kardinale spline door een gespecificeerde reeks van[`Point`](../point/) constructies met een gespecificeerde spanning. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Tekent een ellips gespecificeerd door een begrenzing[`Rectangle`](../rectangle/)structuur. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Tekent een ellips gedefinieerd door een begrenzing[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Tekent het gespecificeerde[`Image`](./image/) , met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Tekent het gespecificeerde[`Image`](./image/) , met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Tekent het gespecificeerde[`Image`](./image/) , met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Tekent de gespecificeerde afbeelding, gebruikmakend van de oorspronkelijke fysieke grootte, op de locatie gespecificeerd door een coördinatenpaar. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Tekent het opgegeven gedeelte van het opgegeven*image* op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Tekent het gespecificeerde[`Image`](./image/) op de opgegeven locatie en met de opgegeven grootte. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Tekent de gespecificeerde afbeelding met gebruikmaking van de originele fysieke grootte op de locatie gespecificeerd door een coördinatenpaar. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Tekent de opgegeven afbeelding zonder te schalen en knipt deze, indien nodig, af zodat deze in de opgegeven rechthoek past. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Tekent een lijn die twee verbindt[`Point`](../point/) structuren. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Tekent een lijn die twee verbindt[`PointF`](../pointf/) structuren. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Tekent een lijn die de twee punten verbindt die worden gespecificeerd door de coördinatenparen. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Tekent een lijn die de twee punten verbindt die worden gespecificeerd door de coördinatenparen. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Tekent een reeks lijnsegmenten die een reeks verbinden[`PointF`](../pointf/) structuren. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Tekent een reeks lijnsegmenten die een reeks verbinden[`Point`](../point/) structuren. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Tekent een[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door a[`Rectangle`](../rectangle/) structuur en twee radiale lijnen. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door a[`RectangleF`](../rectanglef/) structuur en twee radiale lijnen. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Tekent een polygoon gedefinieerd door een array van[`PointF`](../pointf/) structuren. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Tekent een polygoon gedefinieerd door een array van[`Point`](../point/) structuren. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Tekent een rechthoek gespecificeerd door a[`Rectangle`](../rectangle/)structuur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Tekent een rechthoek gespecificeerd door a[`RectangleF`](../rectanglef/)structuur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Tekent een reeks rechthoeken gespecificeerd door[`RectangleF`](../rectanglef/) structuren. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Tekent een reeks rechthoeken gespecificeerd door[`Rectangle`](../rectangle/) structuren. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../brush/) En[`Font`](../font/) objecten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven[`Brush`](../brush/) En[`Font`](../font/) objecten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../brush/) En[`Font`](../font/) objecten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../brush/) En[`Font`](../font/) objecten met behulp van de opmaakkenmerken van het opgegeven[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven[`Brush`](../brush/) En[`Font`](../font/) objecten met behulp van de opmaakkenmerken van het opgegeven[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../brush/) En[`Font`](../font/) objecten met behulp van de opmaakkenmerken van het opgegeven[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Beëindigt het cachen van de grafische bewerkingen die zijn gestart nadat BeginUpdate is aangeroepen. De voorgaande grafische bewerkingen worden in één keer toegepast bij het aanroepen van deze methode. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Vult het inwendige van een gesloten kardinale spline-curve gedefinieerd door een reeks van[`PointF`](../pointf/) structuren. Deze methode gebruikt een standaardspanning van 0,5 enAlternate vulmodus. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Vult het inwendige van een gesloten kardinale spline-curve gedefinieerd door een reeks van[`Point`](../point/) structuren. Deze methode gebruikt een standaardspanning van 0,5 enAlternate vulmodus. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Vult het inwendige van een gesloten kardinale spline-curve gedefinieerd door een reeks van[`PointF`](../pointf/) structuren met behulp van de opgegeven vulmodus. Deze methode gebruikt een standaardspanning van 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Vult het inwendige van een gesloten kardinale spline-curve gedefinieerd door een reeks van[`Point`](../point/) structuren met behulp van de opgegeven vulmodus. Deze methode gebruikt een standaardspanning van 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Vult het inwendige van een gesloten kardinale spline-curve gedefinieerd door een reeks van[`PointF`](../pointf/) constructies met de opgegeven vulmodus en spanning. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Vult het inwendige van een gesloten kardinale spline-curve gedefinieerd door een reeks van[`Point`](../point/) constructies met de opgegeven vulmodus en spanning. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Vult het inwendige van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door a[`Rectangle`](../rectangle/)structuur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Vult het inwendige van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door a[`RectangleF`](../rectanglef/)structuur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Vult het inwendige van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Vult het inwendige van een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Vult het interieur van een[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Vult het inwendige van een taartsectie gedefinieerd door een ellips gespecificeerd door a[`RectangleF`](../rectanglef/) structuur en twee radiale lijnen. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Vult het inwendige van een taartsectie gedefinieerd door een ellips gespecificeerd door a[`RectangleF`](../rectanglef/) structuur en twee radiale lijnen. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Vult het inwendige van een cirkelsectie gedefinieerd door een ellips gespecificeerd door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Vult het inwendige van een cirkelsectie gedefinieerd door een ellips gespecificeerd door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Vult het inwendige van een polygoon gedefinieerd door een reeks punten gespecificeerd door[`PointF`](../pointf/) structuren enAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Vult het inwendige van een polygoon gedefinieerd door een reeks punten gespecificeerd door[`Point`](../point/) structuren enAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Vult het inwendige van een polygoon gedefinieerd door een reeks punten gespecificeerd door[`PointF`](../pointf/) structuren die de opgegeven vulmodus gebruiken. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Vult het inwendige van een polygoon gedefinieerd door een reeks punten gespecificeerd door[`Point`](../point/) structuren die de opgegeven vulmodus gebruiken. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Vult het binnenste van een rechthoek gespecificeerd door a[`Rectangle`](../rectangle/)structuur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Vult het binnenste van een rechthoek gespecificeerd door a[`RectangleF`](../rectanglef/)structuur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Vult het binnenste van een rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Vult het binnenste van een rechthoek gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Vult de binnenkant van een reeks rechthoeken gespecificeerd door[`RectangleF`](../rectanglef/) structuren. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Vult de binnenkant van een reeks rechthoeken gespecificeerd door[`Rectangle`](../rectangle/) structuren. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Vult het interieur van een[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Vermenigvuldigt de[`Matrix`](../matrix/) dat vertegenwoordigt de lokale geometrische transformatie hiervan`Graphics` door de opgegeven[`Matrix`](../matrix/) door het gespecificeerde vooraf te gaan[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Vermenigvuldigt de[`Matrix`](../matrix/) dat vertegenwoordigt de lokale geometrische transformatie hiervan`Graphics` door de opgegeven[`Matrix`](../matrix/) in de opgegeven volgorde. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Reset de[`Transform`](./transform/) eigendom tot identiteit. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Roteert de lokale geometrische transformatie met de gespecificeerde hoeveelheid. Deze methode voegt de rotatie toe aan de transformatie. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Schaalt de lokale geometrische transformatie met de gespecificeerde hoeveelheden. Deze methode voegt de schaalmatrix toe aan de transformatie. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Schaalt de lokale geometrische transformatie met de opgegeven hoeveelheden in de opgegeven volgorde. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies. Deze methode voegt de vertaling toe aan de transformatie. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies in de opgegeven volgorde. |

### Voorbeelden

In dit voorbeeld wordt de klasse Graphics gebruikt om primitieve vormen op het afbeeldingsoppervlak te maken. Om de werking te demonstreren, maakt het voorbeeld een nieuwe afbeelding in PSD-indeling en tekent primitieve vormen op het afbeeldingsoppervlak met behulp van Draw-methoden die worden weergegeven door de klasse Graphics en exporteert deze vervolgens naar de PSD-bestandsindeling.

```csharp
[C#]

//Maak een exemplaar van Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Maak en initialiseer een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Grafisch oppervlak wissen
    graphics.Clear(Color.Wheat);

    // Teken een boog door het Pen-object op te geven met zwarte kleur, 
    //a Rechthoek rond de boog, starthoek en zwaaihoek
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // Teken een Bezier door het Pen-object op te geven met blauwe kleur en coördinaatpunten.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // Teken een curve door het Pen-object op te geven met een groene kleur en een reeks punten
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // Teken een ellips met het Pen-object en een omringende rechthoek
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Teken een lijn 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // Teken een taartsegment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // Teken een polygoon door het Pen-object op te geven met een rode kleur en een reeks punten
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // Teken een rechthoek
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    // Maak een SolidBrush-object en stel de verschillende eigenschappen in
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Teken een tekenreeks met behulp van het SolidBrush-object en lettertype op een specifiek punt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Maak een instantie van PngOptions en stel de verschillende eigenschappen in
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // sla alle veranderingen op.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


