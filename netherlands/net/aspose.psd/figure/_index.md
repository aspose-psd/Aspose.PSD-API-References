---
title: Class Figure
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Figure klas. Het cijfer. Een container voor vormen.
type: docs
weight: 1200
url: /nl/net/aspose.psd/figure/
---
## Figure class

Het cijfer. Een container voor vormen.

```csharp
public class Figure : ObjectWithBounds
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Figure](figure/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Haalt of stelt de grenzen van het object in. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Haalt of stelt een waarde in die aangeeft of dit cijfer gesloten is. Een gesloten figuur maakt alleen verschil als de vormen van de eerste en de laatste figuur doorlopende vormen zijn. In dat geval wordt het eerste punt van de eerste vorm verbonden door een rechte lijn vanaf het laatste punt van de laatste vorm. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Krijgt de hele figuursegmenten. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Krijgt de figuurvormen. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Voegt een vorm toe aan de figuur. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Voegt een reeks vormen toe aan de figuur. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Haalt de grenzen van het object op. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Haalt de grenzen van het object op. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Verwijdert een vorm uit de figuur. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Verwijdert een reeks vormen uit de figuur. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Keert deze vormvolgorde en puntvolgorde om. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Past de opgegeven transformatie toe op de vorm. |

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


