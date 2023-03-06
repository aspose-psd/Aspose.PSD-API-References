---
title: Class HatchBrush
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Brushes.HatchBrush klas. Definieert een rechthoekig penseel met een arceerstijl een voorgrondkleur en een achtergrondkleur. Deze klasse kan niet worden geërfd.
type: docs
weight: 130
url: /nl/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Definieert een rechthoekig penseel met een arceerstijl, een voorgrondkleur en een achtergrondkleur. Deze klasse kan niet worden geërfd.

```csharp
public sealed class HatchBrush : Brush
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [HatchBrush](hatchbrush/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Hiermee wordt de kleur van ruimtes tussen de arceerlijnen opgehaald of ingesteld. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Hiermee wordt de kleur van arceerlijnen opgehaald of ingesteld. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Hiermee wordt de arceerstijl van dit penseel opgehaald of ingesteld. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hiermee wordt de dekking van het penseel opgehaald of ingesteld. De waarde moet tussen 0 en 1 liggen. De waarde 0 betekent dat het penseel volledig zichtbaar is, de waarde 1 betekent dat het penseel volledig dekkend is. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Maakt een nieuwe diepe kloon van de huidige[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |

### Voorbeelden

Dit voorbeeld toont het maken en gebruiken van Pen-objecten. Het voorbeeld maakt een nieuwe afbeelding aan en tekent rechthoeken op het afbeeldingsoppervlak.

```csharp
[C#]

//Maak een exemplaar van Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Maak een instantie van Graphics en initialiseer deze met het Image-object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Wis het grafische oppervlak met witte kleur
    graphics.Clear(Aspose.PSD.Color.White);

    //Maak een instantie van Pen met kleur Rood en breedte 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Maak een instantie van HatchBrush en stel de eigenschappen ervan in
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Maak een instantie van Pen
    // initialiseer het met HatchBrush-object en breedte
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Teken rechthoeken door een Pen-object op te geven
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Teken rechthoeken door een Pen-object op te geven
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Maak exportopties en initialiseer ze.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // sla alle veranderingen op.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Zie ook

* class [Brush](../../aspose.psd/brush/)
* naamruimte [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* montage [Aspose.PSD](../../)


