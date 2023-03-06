---
title: Class Graphics
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Graphics klass. Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen.
type: docs
weight: 4310
url: /sv/net/aspose.psd/graphics/
---
## Graphics class

Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen.

```csharp
public sealed class Graphics
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Graphics](graphics/)(Image) | Initierar en ny instans av`Graphics` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Hämtar eller ställer in klippområdet. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Hämtar eller ställer in kompositkvaliteten. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Får den horisontella upplösningen för denna Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Får den vertikala upplösningen för denna Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Hämtar bilden. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Hämtar eller ställer in interpolationsläget. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Får ett värde som indikerar om grafik är i BeginUpdate-anropstillstånd. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Hämtar eller ställer in skalningen mellan världsenheter och sidenheter för denna Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Hämtar eller ställer in måttenheten som används för sidkoordinater i denna Aspose.PSD.Graphics. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Hämtar eller ställer in utjämningsläget. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Hämtar eller ställer in textåtergivningstipset. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Hämtar eller ställer in en kopia av den geometriska världsomvandlingen för detta`Graphics` . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Startar cachelagring av följande grafikoperationer. De grafiska effekterna som appliceras efteråt kommer inte att tillämpas omedelbart, istället kommer EndUpdate att orsaka att alla effekter appliceras på en gång. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Rensar grafikytan med den angivna färgen. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Ritar en båge som representerar en del av en ellips specificerad av a[`Rectangle`](../rectangle/)struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Ritar en båge som representerar en del av en ellips specificerad av a[`RectangleF`](../rectanglef/)struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Ritar en båge som representerar en del av en ellips specificerad av ett par koordinater, en bredd och en höjd. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Ritar en båge som representerar en del av en ellips specificerad av ett par koordinater, en bredd och en höjd. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Ritar en Bézier-spline definierad av fyra[`Point`](../point/) strukturer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Ritar en Bézier-spline definierad av fyra[`PointF`](../pointf/) strukturer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Ritar en Bézier-spline definierad av fyra ordnade par av koordinater som representerar punkter. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Ritar en serie Bézier-splines från en uppsättning av[`PointF`](../pointf/) strukturer. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Ritar en serie Bézier-splines från en uppsättning av[`Point`](../point/) strukturer. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Ritar en sluten kardinalspline definierad av en array av[`PointF`](../pointf/) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Ritar en sluten kardinalspline definierad av en array av[`Point`](../point/) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Ritar en sluten kardinalspline definierad av en array av[`PointF`](../pointf/) strukturer med en specificerad spänning. Denna metod använder en standardAlternate fyllningsläge. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Ritar en sluten kardinalspline definierad av en array av[`Point`](../point/) strukturer med en specificerad spänning. Denna metod använder en standardAlternate fyllningsläge. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf/) strukturer. Den här metoden använder en standardspänning på 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Ritar en kardinal spline genom en specificerad array av[`Point`](../point/) strukturer. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf/) strukturer med en specificerad spänning. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Ritar en kardinal spline genom en specificerad array av[`Point`](../point/) strukturer med en specificerad spänning. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf/) strukturer. Ritningen börjar offset från början av arrayen. Denna metod använder en standardspänning på 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf/) strukturer med en specificerad spänning. Ritningen börjar offset från början av arrayen. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Ritar en kardinal spline genom en specificerad array av[`Point`](../point/) strukturer med en specificerad spänning. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Ritar en ellips specificerad av en begränsning[`Rectangle`](../rectangle/)struktur. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Ritar en ellips definierad av en avgränsning[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Ritar en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en höjd och en bredd. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Ritar en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en höjd och en bredd. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Ritar det angivna[`Image`](./image/) , med sin ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Ritar det angivna[`Image`](./image/) , med sin ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Ritar det angivna[`Image`](./image/) , med sin ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den plats som anges av ett koordinatpar. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image/) på angiven plats och med angiven storlek. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Ritar en angiven bild med dess ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Ritar en angiven bild med dess ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Ritar den angivna bilden med dess ursprungliga fysiska storlek på den plats som anges av ett koordinatpar. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Ritar en angiven bild med dess ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Ritar den angivna bilden utan skalning och klipper den vid behov så att den passar i den angivna rektangeln. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Ritar en linje som förbinder två[`Point`](../point/) strukturer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Ritar en linje som förbinder två[`PointF`](../pointf/) strukturer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Ritar en linje som förbinder de två punkter som anges av koordinatparen. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Ritar en linje som förbinder de två punkter som anges av koordinatparen. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Ritar en serie linjesegment som förbinder en array av[`PointF`](../pointf/) strukturer. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Ritar en serie linjesegment som förbinder en array av[`Point`](../point/) strukturer. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Ritar en[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Ritar en pajform definierad av en ellips specificerad av a[`Rectangle`](../rectangle/) struktur och två radiella linjer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Ritar en pajform definierad av en ellips specificerad av a[`RectangleF`](../rectanglef/) struktur och två radiella linjer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Ritar en cirkelform som definieras av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiella linjer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Ritar en cirkelform som definieras av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiella linjer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Ritar en polygon som definieras av en array av[`PointF`](../pointf/) strukturer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Ritar en polygon som definieras av en array av[`Point`](../point/) strukturer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Ritar en rektangel specificerad av a[`Rectangle`](../rectangle/)struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Ritar en rektangel specificerad av a[`RectangleF`](../rectanglef/)struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Ritar en serie rektanglar specificerade av[`RectangleF`](../rectanglef/) strukturer. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Ritar en serie rektanglar specificerade av[`Rectangle`](../rectangle/) strukturer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush/) och[`Font`](../font/) objekt. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../brush/) och[`Font`](../font/) objekt. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush/) och[`Font`](../font/) objekt. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush/) och[`Font`](../font/) objekt som använder formateringsattributen för de angivna[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../brush/) och[`Font`](../font/) objekt som använder formateringsattributen för de angivna[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush/) och[`Font`](../font/) objekt som använder formateringsattributen för de angivna[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Avslutar cachelagring av grafikoperationerna som startade efter att BeginUpdate anropades. De föregående grafikoperationerna kommer att tillämpas på en gång när den här metoden anropas. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`PointF`](../pointf/) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`Point`](../point/) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`PointF`](../pointf/) strukturer med det angivna fyllningsläget. Den här metoden använder en standardspänning på 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`Point`](../point/) strukturer med det angivna fyllningsläget. Den här metoden använder en standardspänning på 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`PointF`](../pointf/) strukturer som använder det angivna fyllningsläget och spänningen. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`Point`](../point/) strukturer som använder det angivna fyllningsläget och spänningen. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av en[`Rectangle`](../rectangle/)struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av en[`RectangleF`](../rectanglef/)struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Fyller det inre av en[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Fyller det inre av en pajsektion definierad av en ellips specificerad av en[`RectangleF`](../rectanglef/) struktur och två radiella linjer. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Fyller det inre av en pajsektion definierad av en ellips specificerad av en[`RectangleF`](../rectanglef/) struktur och två radiella linjer. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Fyller det inre av en pajsektion definierad av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiella linjer. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Fyller det inre av en pajsektion definierad av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiella linjer. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`PointF`](../pointf/) strukturer ochAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`Point`](../point/) strukturer ochAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`PointF`](../pointf/) strukturer som använder det angivna fyllningsläget. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`Point`](../point/) strukturer som använder det angivna fyllningsläget. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Fyller det inre av en rektangel specificerad av a[`Rectangle`](../rectangle/)struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Fyller det inre av en rektangel specificerad av a[`RectangleF`](../rectanglef/)struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Fyller det inre av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Fyller det inre av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Fyller det inre av en serie rektanglar som anges av[`RectangleF`](../rectanglef/) strukturer. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Fyller det inre av en serie rektanglar som anges av[`Rectangle`](../rectangle/) strukturer. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Fyller det inre av en[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Multiplicerar[`Matrix`](../matrix/) som representerar den lokala geometriska transformationen av detta`Graphics` av den angivna[`Matrix`](../matrix/) genom att föregå det angivna[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar[`Matrix`](../matrix/) som representerar den lokala geometriska transformationen av detta`Graphics` av den angivna[`Matrix`](../matrix/) i angiven ordning. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Återställer[`Transform`](./transform/) egenskap till identitet. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Roterar den lokala geometriska transformationen med angivet belopp. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med angivet belopp i angiven ordning. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna mängderna. Den här metoden lägger in skalningsmatrisen i transformationen. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna mängderna i angiven ordning. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Exempel

Det här exemplet använder klassen Graphics för att skapa primitiva former på bildytan. För att demonstrera funktionen skapar exemplet en ny bild i PSD-format och ritar primitiva former på bildytan med hjälp av Draw-metoder exponerade av Graphics-klassen och exporterar den sedan till PSD-filformat.

```csharp
[C#]

//Skapa en instans av bild 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan
    graphics.Clear(Color.Wheat);

    //Rita en båge genom att ange Pen-objektet som har svart färg, 
    //a rektangel som omger bågen, startvinkeln och svepvinkeln
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Rita en Bezier genom att ange Pen-objektet som har blå färg och koordinatpunkter.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Rita en kurva genom att ange att Pen-objektet har grön färg och en array av punkter
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Rita en ellips med hjälp av Pen-objektet och en omgivande rektangel
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dra ett streck 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Rita ett pajsegment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Rita en polygon genom att ange att Pen-objektet har röd färg och en array av punkter
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Rita en rektangel
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Skapa ett SolidBrush-objekt och ställ in dess olika egenskaper
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Rita en sträng med SolidBrush-objektet och Font, vid en viss punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Skapa en instans av PngOptions och ställ in dess olika egenskaper
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // spara alla ändringar.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


