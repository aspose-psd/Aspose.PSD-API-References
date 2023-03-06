---
title: Class Pen
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Pen klas. Definieert een object dat wordt gebruikt om lijnen krommen en figuren te tekenen.
type: docs
weight: 5200
url: /nl/net/aspose.psd/pen/
---
## Pen class

Definieert een object dat wordt gebruikt om lijnen, krommen en figuren te tekenen.

```csharp
public class Pen : TransparencySupporter
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initialiseert een nieuw exemplaar van het`Pen` klasse met de gespecificeerde[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Initialiseert een nieuw exemplaar van het`Pen` klasse met de opgegeven kleur. |
| [Pen](pen/#constructor_1)(Brush, float) | Initialiseert een nieuw exemplaar van het`Pen` klasse met de gespecificeerde[`Brush`](./brush/) En[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Initialiseert een nieuw exemplaar van het`Pen` klasse met de gespecificeerde[`Color`](./color/) En[`Width`](./width/) eigenschappen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Haalt of stelt de uitlijning hiervoor in`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Haalt of stelt de[`Brush`](./brush/) dat bepaalt de attributen hiervan`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Haalt of stelt de kleur hiervan in`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Hiermee wordt een reeks waarden opgehaald of ingesteld die een samengestelde pen specificeert. Een samengestelde pen tekent een samengestelde lijn die bestaat uit parallelle lijnen en spaties. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Krijgt of stelt een aangepaste cap in om te gebruiken aan het einde van hiermee getekende lijnen`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Krijgt of stelt een aangepaste hoofdletter in om te gebruiken aan het begin van hiermee getekende lijnen`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Hiermee wordt de hoofdletterstijl opgehaald of ingesteld die wordt gebruikt aan het einde van de streepjes die hiermee de stippellijnen vormen`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Hiermee wordt de afstand vanaf het begin van een lijn tot het begin van een streeppatroon opgehaald of ingesteld. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Haalt of stelt een reeks aangepaste streepjes en spaties in. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Hiermee wordt de stijl opgehaald of ingesteld die wordt gebruikt voor stippellijnen die hiermee worden getekend`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Haalt of stelt de dopstijl in die wordt gebruikt aan het einde van hiermee getekende lijnen`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Hiermee wordt de verbindingsstijl voor de uiteinden van twee opeenvolgende lijnen opgehaald of ingesteld`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Haalt of stelt de limiet in van de dikte van de verbinding op een verstekhoek. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Hiermee wordt de dekking van het object opgehaald of ingesteld. De waarde moet tussen 0 en 1 liggen. De waarde 0 betekent dat het object volledig zichtbaar is, de waarde 1 betekent dat het object volledig ondoorzichtig is. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Hiermee krijgt u de stijl van getekende lijnen`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Hiermee wordt de hoofdletterstijl opgehaald of ingesteld die wordt gebruikt aan het begin van hiermee getekende lijnen`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Haalt of stelt hiervoor een kopie van de geometrische transformatie in`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Haalt of stelt de breedte hiervan in`Pen` , in eenheden van het Graphics-object gebruikt voor tekenen. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Vermenigvuldigt hiervoor de transformatiematrix`Pen` door de opgegeven[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Vermenigvuldigt hiervoor de transformatiematrix`Pen` door de opgegeven[`Matrix`](../matrix/) in de opgegeven volgorde. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Reset hiervoor de geometrische transformatiematrix`Pen` naar identiteit. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Roteert de lokale geometrische transformatie met de gespecificeerde hoek. Deze methode voegt de rotatie toe aan de transformatie. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Roteert de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Schaalt de lokale geometrische transformatie met de gespecificeerde factoren. Deze methode voegt de schaalmatrix toe aan de transformatie. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Stelt de waarden in die de stijl van de dop bepalen die wordt gebruikt om hiermee getekende lijnen te beëindigen`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Vertaalt de lokale geometrische transformatie door de gespecificeerde dimensies. Deze methode voegt de vertaling toe aan de transformatie. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Vertaalt de lokale geometrische transformatie door de opgegeven dimensies in de opgegeven volgorde. |

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

* class [TransparencySupporter](../transparencysupporter/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


