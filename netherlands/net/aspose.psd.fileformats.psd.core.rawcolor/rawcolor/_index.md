---
title: "Klasse RawColor"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor class. Raw Color Class helpt bij het opslaan van kleuren met elk aantal kanalen, elke kleermodus en elke bitdiepte. Houd er rekening mee dat sommige interne klassen problemen kunnen hebben met het converteren van RawColor naar zijn native formaat, dus als de API een CMYK‑kleur levert, is het betrouwbaarder om het geleverde formaat te gebruiken. Er kunnen ook gevallen zijn waarin Raw Color kan worden geconverteerd"
type: docs
weight: 1650
url: /nl/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class helpt bij het opslaan van kleuren met elk aantal kanalen, elke kleermodus en elke bitdiepte. Houd er rekening mee dat sommige interne klassen problemen kunnen hebben met het converteren van RawColor naar het eigen formaat, dus als de API een CMYK-kleur levert, is het betrouwbaarder om het geleverde formaat te gebruiken. Ook kunnen er gevallen zijn waarin Raw Color kan worden geconverteerd.

```csharp
public sealed class RawColor
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Initialiseert een nieuw exemplaar van de `RawColor` class. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Initialiseert een nieuw exemplaar van de `RawColor` class vanuit pixel‑dataformaat met behulp van vooraf gedefinieerde kleermodi |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Modus voor de te volgen kleur. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Haalt de componenten van de kleur op. Elke component is een afzonderlijk kanaal, en als u een niet‑populair kleurenschema gebruikt, is het beter om met elk kanaal afzonderlijk te werken. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Haalt de kleur op als int voor het geval het mogelijk is om deze te verkrijgen. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Haalt de kleur op als long voor het geval het mogelijk is om deze te verkrijgen. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Haalt de bitdiepte op van Raw Color. Bijvoorbeeld voor een ARGB-kleur met 8 bits per kanaal/component is 32 Bit Depth; van een volledige ARGB-kleur met 16 bits per kanaal/component is 64. Bit Depth wordt opgeteld uit de som van de bitdieptes van de kanalen. Het is mogelijk als verschillende kanalen verschillende bitdieptes hebben. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Haalt de naam van de kleermodus op. De naam van de kleermodus wordt opgebouwd uit de namen van kanalen/componenten. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Haal de hashcode op van het huidige object. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Stelt gegevens in voor alle kanalen vanuit een int-argument als dit mogelijk is. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Stelt gegevens in voor alle kanalen vanuit een int-argument als dit mogelijk is. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Implementeert de operator ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Implementeert de operator !=. |

## Voorbeelden

De volgende code demonstreert de ondersteuning van de RawColor-klasse in plaats van de verouderde Color-struct.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Zie ook

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


