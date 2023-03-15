---
title: Graphics.DrawPath
second_title: Aspose.PSD voor .NET API-referentie
description: Graphics methode. Tekent eenGraphicsPath .
type: docs
weight: 270
url: /nl/net/aspose.psd/graphics/drawpath/
---
## Graphics.DrawPath method

Tekent een[`GraphicsPath`](../../graphicspath/) .

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) die de kleur, breedte en stijl van het pad bepaalt. |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/) tekenen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *pen* is nul. -of- *path* is niets. |

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

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)


