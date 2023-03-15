---
title: Class Pen
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Pen klass. Definierar ett objekt som används för att rita linjer kurvor och figurer.
type: docs
weight: 5200
url: /sv/net/aspose.psd/pen/
---
## Pen class

Definierar ett objekt som används för att rita linjer, kurvor och figurer.

```csharp
public class Pen : TransparencySupporter
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initierar en ny instans av`Pen` klass med den angivna[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Initierar en ny instans av`Pen` klass med den angivna färgen. |
| [Pen](pen/#constructor_1)(Brush, float) | Initierar en ny instans av`Pen` klass med den angivna[`Brush`](./brush/) och[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Initierar en ny instans av`Pen` klass med den angivna[`Color`](./color/) och[`Width`](./width/) egenskaper. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Hämtar eller ställer in justeringen för detta`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Hämtar eller ställer in[`Brush`](./brush/) som bestämmer attributen för detta`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Hämtar eller ställer in färgen på detta`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Hämtar eller ställer in en matris med värden som anger en sammansatt penna. En sammansatt penna ritar en sammansatt linje som består av parallella linjer och mellanslag. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Får eller ställer in ett anpassat tak som ska användas i slutet av linjer som ritas med detta`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Får eller ställer in ett anpassat tak som ska användas i början av linjer som ritas med detta`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Hämtar eller ställer in kapsylstilen som används i slutet av strecken som utgör streckade linjer ritade med detta`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Hämtar eller ställer in avståndet från början av en linje till början av ett streckmönster. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Hämtar eller ställer in en rad anpassade bindestreck och blanksteg. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Hämtar eller ställer in stilen som används för streckade linjer som ritas med detta`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Hämtar eller ställer in cap-stilen som används i slutet av linjer som ritas med detta`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Hämtar eller ställer in kopplingsstilen för ändarna av två på varandra följande linjer ritade med detta`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Hämtar eller ställer in gränsen för fogtjockleken på ett geringshörn. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Hämtar eller ställer in objektets opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att objektet är helt synligt, värdet 1 betyder att objektet är helt ogenomskinligt. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Får stilen på linjer ritade med detta`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Hämtar eller ställer in cap-stilen som används i början av linjer som ritas med detta`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Hämtar eller ställer in en kopia av den geometriska transformationen för detta`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Hämtar eller ställer in bredden på detta`Pen` , i enheter av grafikobjektet som används för att rita. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplicerar transformationsmatrisen för detta`Pen` av den angivna[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar transformationsmatrisen för detta`Pen` av den angivna[`Matrix`](../matrix/) i angiven ordning. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Återställer den geometriska transformationsmatrisen för detta`Pen` till identitet. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna vinkeln i angiven ordning. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod förbereder skalningsmatrisen till transformationen. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna faktorerna i angiven ordning. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Ställer in värdena som bestämmer stilen på taket som används för att avsluta linjer som ritas av denna`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformationen. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Exempel

Det här exemplet visar skapande och användning av Pen-objekt. Exemplet skapar en ny bild och ritar rektanglar på bildytan.

```csharp
[C#]

//Skapa en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa en instans av Graphics och initiera den med Image object
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa grafikytan med vit färg
    graphics.Clear(Aspose.PSD.Color.White);

    //Skapa en instans av Pen med färgen Röd och bredd 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Skapa en instans av HatchBrush och ställ in dess egenskaper
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Skapa en instans av Pen
    //initiera det med HatchBrush-objekt och bredd
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Se även

* class [TransparencySupporter](../transparencysupporter/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


