---
title: "Klass Pen"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Pen-klass. Definierar ett objekt som används för att rita linjer, kurvor och figurer"
type: docs
weight: 5690
url: /sv/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Definierar ett objekt som används för att rita linjer, kurvor och figurer.

```csharp
public class Pen : TransparencySupporter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initierar en ny instans av `Pen`-klassen med den angivna [`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | Initierar en ny instans av `Pen`-klassen med den angivna färgen. |
| [Pen](pen/#constructor_1)(Brush, float) | Initierar en ny instans av `Pen`-klassen med den angivna [`Brush`](./brush/) och [`Width`](./width/). |
| [Pen](pen/#constructor_3)(Color, float) | Initierar en ny instans av `Pen`-klassen med de angivna egenskaperna [`Color`](./color/) och [`Width`](./width/). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Hämtar eller anger justeringen för denna `Pen`. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Hämtar eller anger [`Brush`](./brush/) som bestämmer attributen för denna `Pen`. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Hämtar eller anger färgen på denna `Pen`. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Hämtar eller anger en array av värden som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Hämtar eller anger en anpassad spets som används i slutet av linjer som ritas med denna `Pen`. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Hämtar eller anger en anpassad spets som används i början av linjer som ritas med denna `Pen`. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Hämtar eller anger spetsstilen som används i slutet av strecken som utgör streckade linjer ritas med denna `Pen`. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Hämtar eller anger avståndet från början av en linje till starten av ett streckmönster. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Hämtar eller anger en array av anpassade streck och mellanrum. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Hämtar eller anger stilen som används för streckade linjer ritas med denna `Pen`. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Hämtar eller anger spetsstilen som används i slutet av linjer ritas med denna `Pen`. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Hämtar eller anger fogstilen för ändarna på två på varandra följande linjer som ritas med denna `Pen`. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Hämtar eller anger gränsen för tjockleken på fogen i ett snedställt hörn. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Hämtar eller anger objektets opacitet. Värdet bör vara mellan 0 och 1. Värde 0 betyder att objektet är helt synligt, värde 1 betyder att objektet är helt ogenomskinligt. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Hämtar stilen på linjer som ritas med denna `Pen`. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Hämtar eller anger spetsstilen som används i början av linjer ritas med denna `Pen`. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Hämtar eller anger en kopia av den geometriska transformationen för denna `Pen`. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Hämtar eller anger bredden på denna `Pen`, i enheter av Graphics-objektet som används för ritning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplicerar transformationsmatrisen för denna `Pen` med den angivna [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar transformationsmatrisen för denna `Pen` med den angivna [`Matrix`](../matrix/) i den angivna ordningen. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Återställer den geometriska transformationsmatrisen för denna `Pen` till identitet. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Rotera den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger rotationen först i transformationen. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Rotera den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger till skalningsmatrisen först i transformationen. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Anger värdena som bestämmer stilen på ändkappen som används för att avsluta linjer ritade med denna `Pen`. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till översättningen först i transformationen. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |

## Exempel

Detta exempel visar skapandet och användningen av Pen‑objekt. Exemplet skapar en ny Image och ritar rektanglar på Image‑ytan.

```csharp
[C#]

//Skapa en instans av Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapa en instans av Graphics och initiera den med ett Image‑objekt
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensa Graphics‑ytan med vit färg.
    graphics.Clear(Aspose.PSD.Color.White);

    //Skapa en instans av Pen med färgen röd och bredd 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Skapa en instans av HatchBrush och ange dess egenskaper
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Skapa en instans av Pen
    //initiera den med HatchBrush‑objektet och bredden
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen‑objektet
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Rita rektanglar genom att ange Pen‑objektet
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Skapa exportalternativ och initiera dem.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // spara alla ändringar.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Se även

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


