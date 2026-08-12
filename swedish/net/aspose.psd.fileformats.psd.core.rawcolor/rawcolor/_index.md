---
title: "Klass RawColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor klass. Raw Color-klass hjälper till att lagra färger med valfritt antal kanaler, valfritt färgläge och valfri bitdjup. Observera att vissa interna klasser kan ha problem med att konvertera RawColor till dess ursprungsformat, så om API:t tillhandahåller en CMYK-färg är det mer pålitligt att använda det angivna formatet. Det kan också finnas fall där Raw Color kan konverteras."
type: docs
weight: 1650
url: /sv/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class hjälper till att lagra färger med valfritt antal kanaler, valfritt färgläge och valfri bitdjup. Observera att vissa interna klasser kan ha problem med att konvertera RawColor till dess inhemska format, så om API:t tillhandahåller en CMYK‑färg är det mer pålitligt att använda det angivna formatet. Dessutom kan det finnas vissa fall då Raw Color kan konverteras.

```csharp
public sealed class RawColor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Initierar en ny instans av klassen `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Initierar en ny instans av klassen `RawColor` från pixeldataformat med fördefinierade färglägen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Läge för färgen att följa. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Hämtar färgens komponenter. Varje komponent är en separat kanal, och om du använder ett mindre vanligt färgschema är det bättre att arbeta med varje kanal separat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Bestämmer om det angivna objektet är lika med den här instansen. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Hämtar färgen som int om det är möjligt att få den. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Hämtar färgen som long om det är möjligt att få den. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Hämtar bitdjupet för Raw Color. Till exempel för en ARGB-färg med 8 bitar per kanal/komponent är bitdjupet 32. Bitdjupet för en full ARGB-färg med 16 bitar per kanal/komponent är 64. Bitdjupet ackumuleras från summan av kanalernas bitdjup. Det är möjligt att olika kanaler har olika bitdjup. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Hämtar namnet på färgläget. Färglägesnamnet är sammansatt av kanalernas/komponenternas namn. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Hämta hashkod för det aktuella objektet. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Sätter data till alla kanaler från ett int-argument om det är möjligt. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Sätter data till alla kanaler från ett int-argument om det är möjligt. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Implementerar operatorn ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Implementerar operatorn !=. |

## Exempel

Följande kod demonstrerar stödet för RawColor-klassen istället för den föråldrade Color-strukturen.

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

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


