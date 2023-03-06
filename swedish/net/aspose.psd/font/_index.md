---
title: Class Font
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Font klass. Definierar ett visst format för text inklusive teckensnitt storlek och stilattribut. Denna klass kan inte ärvas.
type: docs
weight: 4280
url: /sv/net/aspose.psd/font/
---
## Font class

Definierar ett visst format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas.

```csharp
public sealed class Font
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initierar en ny`Font` som använder den angivna befintliga`Font` och[`FontStyle`](../fontstyle/) uppräkning. |
| [Font](font/#constructor_1)(string, float) | Initierar en ny`Font` med en angiven storlek. Teckenuppsättningen är inställd påDefault , grafikenheten tillPoint , teckensnittsstilen tillRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initierar en ny`Font` med en specificerad storlek och stil. Teckenuppsättningen är inställd påDefault , grafikenheten tillPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initierar en ny`Font` med en specificerad storlek och enhet. Teckenuppsättningen är inställd påDefault är stilen inställd påRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initierar en ny`Font` använder en specificerad storlek, stil och enhet. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initierar en ny`Font` med en specificerad storlek, stil, enhet och teckenuppsättning. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Får ett värde som indikerar om detta`Font` är fetstil. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Får ett bytevärde som specificerar teckenuppsättningen som detta`Font` använder. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Får ett värde som indikerar om detta`Font`är kursiv. |
| [Name](../../aspose.psd/font/name/) { get; } | Får ansiktsnamnet på detta`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Får em-storleken på detta`Font` mätt i de enheter som anges av[`Unit`](./unit/) egenskap. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Får ett värde som indikerar om detta`Font` anger en horisontell linje genom teckensnittet. |
| [Style](../../aspose.psd/font/style/) { get; } | Får stilinformation för detta`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Får ett värde som indikerar om detta`Font` är understruken. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Hämtar måttenheten för detta`Font` . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Skapar en exakt djup kopia av detta`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indikerar om det angivna objektet är ett`Font` och har samma fastighetsvärden som denna`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Hämtar hashkoden för detta`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Returnerar en mänsklig läsbar strängrepresentation av detta`Font` . |

### Exempel

Det här exemplet visar användningen av klassen Font och SolidBrush för att rita strängar på bildytan. Exemplet skapar en ny bild och ritar former med hjälp av Figurer och GraphicsPath

```csharp
[C#]

//Skapar en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapar och initierar en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensar grafikytan
    graphics.Clear(Color.Wheat);

    //Skapar en instans av Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Rita ett snöre
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // skapa exportalternativ.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // spara alla ändringar
    image.Save("C:\\temp\\output.gif", options);
}
```

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


