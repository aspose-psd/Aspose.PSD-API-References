---
title: "Klass Font"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Font-klass. Definierar ett specifikt format för text inklusive teckensnittets storlek och stilattribut. Denna klass kan inte ärvas"
type: docs
weight: 4750
url: /sv/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas.

```csharp
public sealed class Font
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initierar en ny `Font` som använder den angivna befintliga `Font` och [`FontStyle`](../fontstyle/)‑uppräkningen. |
| [Font](font/#constructor_1)(string, float) | Initierar en ny `Font` med en angiven storlek. Teckenuppsättningen sätts till Default, grafik‑enheten till Point, teckensnittsstilen till Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initierar en ny `Font` med en angiven storlek och stil. Teckenuppsättningen sätts till Default, grafik‑enheten till Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initierar en ny `Font` med en angiven storlek och enhet. Teckenuppsättningen sätts till Default, stilen sätts till Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initierar en ny `Font` med en angiven storlek, stil och enhet. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initierar en ny `Font` med en angiven storlek, stil, enhet och teckenuppsättning. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Hämtar ett värde som indikerar om denna `Font` är fet. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Hämtar ett byte‑värde som specificerar teckenuppsättningen som denna `Font` använder. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Hämtar ett värde som indikerar om denna `Font` är kursiv. |
| [Name](../../aspose.psd/font/name/) { get; } | Hämtar teckensnittets namn för denna `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | Hämtar em‑storleken för denna `Font` mätt i de enheter som anges av egenskapen [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Hämtar ett värde som indikerar om denna `Font` specificerar ett horisontellt streck genom teckensnittet. |
| [Style](../../aspose.psd/font/style/) { get; } | Hämtar stilinformation för denna `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Hämtar ett värde som indikerar om denna `Font` är understruken. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Hämtar måttenheten för denna `Font`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Skapar en exakt djup kopia av detta `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indikerar om det angivna objektet är en `Font` och har samma egenskapsvärden som denna `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Hämtar hash‑koden för denna `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | Returnerar en människoläsbar strängrepresentation av denna `Font`. |

## Exempel

Detta exempel demonstrerar användningen av Font- och SolidBrush-klassen för att rita strängar på Image-ytan. Exemplet skapar en ny Image och ritar former med Figures och GraphicsPath.

```csharp
[C#]

//Skapar en instans av Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapar och initierar en instans av Graphics-klass
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensar Graphics-ytan
    graphics.Clear(Color.Wheat);

    //Skapar en instans av Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Rita en sträng
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // skapa exportalternativ.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // spara alla ändringar
    image.Save("C:\\temp\\output.gif", options);
}
```

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


