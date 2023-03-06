---
title: Class StreamSource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Sources.StreamSource klas. Vertegenwoordigt een streambron.
type: docs
weight: 5620
url: /nl/net/aspose.psd.sources/streamsource/
---
## StreamSource class

Vertegenwoordigt een streambron.

```csharp
public sealed class StreamSource : Source
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Initialiseert een nieuw exemplaar van het`StreamSource` klasse. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Initialiseert een nieuw exemplaar van het`StreamSource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Krijgt een waarde die aangeeft of de stream moet worden verwijderd wanneer de container wordt verwijderd. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Krijgt de stream. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Haalt de streamcontainer op. |

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

* class [Source](../../aspose.psd/source/)
* naamruimte [Aspose.PSD.Sources](../../aspose.psd.sources/)
* montage [Aspose.PSD](../../)


