---
title: Class GraphicsPath
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.GraphicsPath klas. Vertegenwoordigt een reeks verbonden lijnen en krommen. Deze klasse kan niet worden geërfd.
type: docs
weight: 4320
url: /nl/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Vertegenwoordigt een reeks verbonden lijnen en krommen. Deze klasse kan niet worden geërfd.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initialiseert een nieuw exemplaar van het`GraphicsPath` klasse. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initialiseert een nieuw exemplaar van het`GraphicsPath` klasse. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initialiseert een nieuw exemplaar van het`GraphicsPath` klasse. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initialiseert een nieuw exemplaar van het`GraphicsPath` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Haalt of stelt de grenzen van het object in. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Haalt de padcijfers op. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Haalt of zet a[`FillMode`](../fillmode/) opsomming die bepaalt hoe de interieurs van vormen hierin`GraphicsPath` zijn gevuld. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Voegt een nieuw cijfer toe. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Voegt nieuwe cijfers toe. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Voegt het gespecificeerde toe`GraphicsPath` naar dit pad. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Voegt het gespecificeerde toe`GraphicsPath` naar dit pad. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Voert een diepe kloon uit van dit grafische pad. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Converteert elke curve in dit pad naar een reeks verbonden lijnsegmenten. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Past de opgegeven transformatie toe en converteert vervolgens elke curve hierin`GraphicsPath` in een reeks verbonden lijnsegmenten. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Converteert hierin elke kromme`GraphicsPath` in een reeks verbonden lijnsegmenten. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Haalt de grenzen van het object op. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Haalt de grenzen van het object op. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) en met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) en met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) en met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Geeft aan of het gespecificeerde punt binnen (onder) de omtrek hiervan ligt`GraphicsPath` wanneer getekend met de opgegeven[`Pen`](../pen/) en met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` in het zichtbare clipgebied van het opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Geeft aan of het gespecificeerde punt hierin is opgenomen`GraphicsPath` , met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Verwijdert een figuur. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Verwijdert cijfers. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Maakt het grafische pad leeg en stelt de[`FillMode`](../fillmode/) naarAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Keert de volgorde van figuren, vormen en punten in elke vorm hiervan om`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Past de opgegeven transformatie toe op de vorm. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Voegt een extra omtrek toe aan het pad. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Voegt een extra omtrek toe aan het`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Vervangt dit`GraphicsPath` met curven die het gebied omsluiten dat wordt gevuld wanneer dit pad wordt getekend met de opgegeven pen. |

### Voorbeelden

Deze voorbeelden maken gebruik van de klasse GraphicsPath en Graphics om figuren op een afbeeldingsoppervlak te maken en te manipuleren. Voorbeeld maakt een nieuwe afbeelding en tekent paden met behulp van de klasse GraphicsPath. Aan het einde wordt de DrawPath-methode die wordt weergegeven door de klasse Graphics aangeroepen om de paden op het oppervlak weer te geven. Ten slotte wordt de afbeelding geëxporteerd naar het Tiff-bestandsformaat.

```csharp
[C#]

//Maak een exemplaar van Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Maak en initialiseer een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Grafisch oppervlak wissen
    graphics.Clear(Color.Wheat);

    //Maak een instantie van de klasse GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Maak een instantie van de klasse Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Vormen toevoegen aan figuurobject
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Voeg figuurobject toe aan GraphicsPath
    graphicspath.AddFigure(figure);

    // Teken een pad met een Pen-object in de kleur Zwart
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Maak een exemplaar van TiffOptions en stel de verschillende eigenschappen in
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // sla alle veranderingen op.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Zie ook

* class [ObjectWithBounds](../objectwithbounds/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


