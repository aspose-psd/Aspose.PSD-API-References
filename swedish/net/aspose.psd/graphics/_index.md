---
title: "Klass Graphics"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Graphics klass. Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen"
type: docs
weight: 4780
url: /sv/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Representerar grafiken enligt den grafikmotor som används i den aktuella assemblyn.

```csharp
public sealed class Graphics
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Graphics](graphics/)(Image) | Initierar en ny instans av klassen `Graphics`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Hämtar eller anger klippningsregionen. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Hämtar eller anger sammansättningskvaliteten. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Hämtar den horisontella upplösningen för detta Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Hämtar den vertikala upplösningen för detta Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Hämtar bilden. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Hämtar eller anger interpolationsläget. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Hämtar ett värde som indikerar om grafik är i BeginUpdate-anropstillstånd. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Hämtar eller anger skalningen mellan världsenheter och sidoyheter för detta Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Hämtar eller anger måttenheten som används för sidkoordinater i detta Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Hämtar eller anger bildalternativ, som används för att skapa målbara vektorbilder att rita. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Hämtar eller anger utjämningsläget. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Hämtar eller anger textrenderingstips. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Hämtar eller anger en kopia av den geometriska världstransformationen för detta `Graphics`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Startar cachning av följande grafikoperationer. Grafikeffekterna som tillämpas därefter kommer inte att tillämpas omedelbart, utan EndUpdate kommer att orsaka att alla effekter appliceras på en gång. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Rensar grafikytan med den angivna färgen. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Ritar en båge som representerar en del av en ellips specificerad av en [`Rectangle`](../rectangle/) struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Ritar en båge som representerar en del av en ellips specificerad av en [`RectangleF`](../rectanglef/) struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Ritar en Bézier-spline definierad av fyra [`Point`](../point/) strukturer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Ritar en Bézier-spline definierad av fyra [`PointF`](../pointf/) strukturer. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Ritar en Bézier-spline definierad av fyra ordnade koordinatpar som representerar punkter. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Ritar en serie av Bézier-splines från en array av [`PointF`](../pointf/) strukturer. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Ritar en serie av Bézier-splines från en array av [`Point`](../point/) strukturer. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Ritar en sluten kardinal-spline definierad av en array av [`PointF`](../pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och alternativ fyllningsläge. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Ritar en sluten kardinal-spline definierad av en array av [`Point`](../point/) strukturer. Denna metod använder en standardspänning på 0,5 och alternativ fyllningsläge. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Ritar en sluten kardinal-spline definierad av en array av [`PointF`](../pointf/) strukturer med en specificerad spänning. Denna metod använder ett standardalternativt fyllningsläge. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Ritar en sluten kardinal-spline definierad av en array av [`Point`](../point/) strukturer med en specificerad spänning. Denna metod använder ett standardalternativt fyllningsläge. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Ritar en kardinal-spline genom en specificerad array av [`PointF`](../pointf/) strukturer. Denna metod använder en standardspänning på 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Ritar en kardinal-spline genom en specificerad array av [`Point`](../point/) strukturer. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Ritar en kardinal-spline genom en specificerad array av [`PointF`](../pointf/) strukturer med en specificerad spänning. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Ritar en kardinal spline genom en specificerad array av [`Point`](../point/) strukturer med en specificerad spänning. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Ritar en kardinal spline genom en specificerad array av [`PointF`](../pointf/) strukturer. Ritningen börjar förskjuten från början av arrayen. Denna metod använder en standardspänning på 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Ritar en kardinal spline genom en specificerad array av [`PointF`](../pointf/) strukturer med en specificerad spänning. Ritningen börjar förskjuten från början av arrayen. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Ritar en kardinal spline genom en specificerad array av [`Point`](../point/) strukturer med en specificerad spänning. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Ritar en ellips som specificeras av en omgivande [`Rectangle`](../rectangle/) struktur. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Ritar en ellips som definieras av en omgivande [`RectangleF`](../rectanglef/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Ritar en ellips som definieras av en omgivande rektangel specificerad av ett koordinatpar, en höjd och en bredd. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Ritar en ellips som definieras av en omgivande rektangel specificerad av ett koordinatpar, en höjd och en bredd. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Ritar den specificerade [`Image`](./image/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Ritar den specificerade [`Image`](./image/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Ritar den specificerade [`Image`](./image/), med dess ursprungliga fysiska storlek, på den specificerade platsen. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Ritar den specificerade bilden, med dess ursprungliga fysiska storlek, på platsen som specificeras av ett koordinatpar. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Ritar den specificerade delen av den specificerade *image* på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Ritar den specificerade [`Image`](./image/) på den specificerade platsen och med den specificerade storleken. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Ritar den specificerade bilden med dess ursprungliga fysiska storlek på platsen som specificeras av ett koordinatpar. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Ritar den specificerade bilden utan skalning och beskär den, om nödvändigt, för att passa i den specificerade rektangeln. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Ritar en linje som förbinder två [`Point`](../point/) strukturer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Ritar en linje som förbinder två [`PointF`](../pointf/) strukturer. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Ritar en linje som förbinder de två punkterna som specificeras av koordinatparen. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Ritar en serie linjesegment som förbinder en array av [`PointF`](../pointf/) strukturer. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Ritar en serie linjesegment som förbinder en array av [`Point`](../point/) strukturer. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Ritar en [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Ritar en pajform definierad av en ellips specificerad av en [`Rectangle`](../rectangle/) struktur och två radiala linjer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Ritar en pajform definierad av en ellips specificerad av en [`RectangleF`](../rectanglef/) struktur och två radiala linjer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Ritar en pajform definierad av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Ritar en polygon definierad av en array av [`PointF`](../pointf/) strukturer. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Ritar en polygon definierad av en array av [`Point`](../point/) strukturer. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Ritar en rektangel specificerad av en [`Rectangle`](../rectangle/) struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Ritar en rektangel som specificeras av en [`RectangleF`](../rectanglef/) struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Ritar en rektangel som specificeras av ett koordinatpar, en bredd och en höjd. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Ritar en rektangel som specificeras av ett koordinatpar, en bredd och en höjd. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Ritar en serie rektanglar som specificeras av [`RectangleF`](../rectanglef/) strukturer. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Ritar en serie rektanglar som specificeras av [`Rectangle`](../rectangle/) strukturer. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Ritar den angivna textsträngen på den angivna platsen med de angivna [`Brush`](../brush/) och [`Font`](../font/) objekten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [`Brush`](../brush/) och [`Font`](../font/) objekten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Ritar den angivna textsträngen på den angivna platsen med de angivna [`Brush`](../brush/) och [`Font`](../font/) objekten. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Ritar den angivna textsträngen på den angivna platsen med de angivna [`Brush`](../brush/) och [`Font`](../font/) objekten med hjälp av formateringsattributen från den angivna [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [`Brush`](../brush/) och [`Font`](../font/) objekten med hjälp av formateringsattributen från den angivna [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Ritar den angivna textsträngen på den angivna platsen med de angivna [`Brush`](../brush/) och [`Font`](../font/) objekten med hjälp av formateringsattributen från den angivna [`StringFormat`](../stringformat/). |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Avslutar cachning av grafikoperationerna som startades efter att BeginUpdate anropades. De föregående grafikoperationerna kommer att tillämpas på en gång när denna metod anropas. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [`PointF`](../pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och alternativ fyllningsläge. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [`Point`](../point/) strukturer. Denna metod använder en standardspänning på 0,5 och alternativ fyllningsläge. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [`PointF`](../pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [`Point`](../point/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [`PointF`](../pointf/) strukturer med det angivna fyllningsläget och spänningen. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Fyller insidan av en sluten kardinal spline-kurva definierad av en array av [`Point`](../point/) strukturer med det angivna fyllningsläget och spänningen. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Fyller insidan av en ellips som definieras av en avgränsande rektangel specificerad av en [`Rectangle`](../rectangle/) struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Fyller insidan av en ellips som definieras av en avgränsande rektangel specificerad av en [`RectangleF`](../rectanglef/) struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Fyller insidan av en ellips som definieras av en avgränsande rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Fyller insidan av en ellips som definieras av en avgränsande rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Fyller insidan av en [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [`RectangleF`](../rectanglef/) struktur och två radiala linjer. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av en [`RectangleF`](../rectanglef/) struktur och två radiala linjer. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Fyller insidan av ett pajsegment definierat av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [`PointF`](../pointf/) strukturer och alternativ fyllningsläge. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Fyller insidan av en polygon definierad av en array av punkter specificerade av [`Point`](../point/) strukturer och alternativ fyllningsläge. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Fyller polygonens inre som definieras av en matris av punkter specificerade av [`PointF`](../pointf/) strukturer med det angivna fyllningsläget. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Fyller polygonens inre som definieras av en matris av punkter specificerade av [`Point`](../point/) strukturer med det angivna fyllningsläget. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Fyller rektangelns inre som specificeras av en [`Rectangle`](../rectangle/) struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Fyller rektangelns inre som specificeras av en [`RectangleF`](../rectanglef/) struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Fyller rektangelns inre som specificeras av ett par koordinater, en bredd och en höjd. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Fyller rektangelns inre som specificeras av ett par koordinater, en bredd och en höjd. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Fyller inre av en serie rektanglar som specificeras av [`RectangleF`](../rectanglef/) strukturer. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Fyller inre av en serie rektanglar som specificeras av [`Rectangle`](../rectangle/) strukturer. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Fyller inre av en [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Multiplicerar den [`Matrix`](../matrix/) som representerar den lokala geometriska transformen för detta `Graphics` med den angivna [`Matrix`](../matrix/) genom att föregå den angivna [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar den [`Matrix`](../matrix/) som representerar den lokala geometriska transformen för detta `Graphics` med den angivna [`Matrix`](../matrix/) i den angivna ordningen. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Återställer egenskapen [`Transform`](./transform/) till identitet. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Roterar den lokala geometriska transformationen med den angivna mängden. Denna metod lägger rotationen först i transformationen. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod lägger till skalningsmatrisen först i transformationen. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till translationen först i transformationen. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |

## Exempel

Detta exempel använder Graphics-klass för att skapa primitiva former på bildytan. För att demonstrera operationen skapar exemplet en ny bild i PSD-format och ritar primitiva former på bildytan med Draw‑metoder som exponeras av Graphics‑klassen och exporterar den sedan till PSD-filformat.

```csharp
[C#]

//Skapa en instans av Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa och initiera en instans av Graphics-klassen
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics-ytan
    graphics.Clear(Color.Wheat);

    //Rita en båge genom att ange Pen‑objektet med svart färg, 
    //en rektangel som omger bågen, startvinkel och svepvinkel
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Rita en Bezier genom att ange Pen‑objektet med blå färg och koordinatpunkter.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Rita en kurva genom att ange Pen‑objektet med grön färg och en array av punkter
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Rita en ellips med Pen‑objektet och en omgivande rektangel
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Rita en linje 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Rita ett pajsegment
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Rita en polygon genom att ange Pen‑objektet med röd färg och en array av punkter
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Rita en rektangel
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Skapa ett SolidBrush‑objekt och ange dess olika egenskaper
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Rita en sträng med SolidBrush‑objektet och Font, vid en specifik punkt
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Skapa en instans av PngOptions och ange dess olika egenskaper
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // spara alla ändringar.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


