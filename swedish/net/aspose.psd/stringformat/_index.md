---
title: Class StringFormat
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.StringFormat klass. Kapslar in textlayoutinformation som justering orientering och tabbstopp visningsmanipulationer som ellipsinsättning och nationell siffrorsättning och OpenTypefunktioner. Denna klass kan inte ärvas.
type: docs
weight: 5670
url: /sv/net/aspose.psd/stringformat/
---
## StringFormat class

Kapslar in textlayoutinformation (som justering, orientering och tabbstopp), visningsmanipulationer (som ellipsinsättning och nationell siffrorsättning) och OpenType-funktioner. Denna klass kan inte ärvas.

```csharp
public sealed class StringFormat : DisposableObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initierar en ny`StringFormat` objekt. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initierar en ny`StringFormat` objekt från det angivna befintliga`StringFormat` objekt. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initierar en ny`StringFormat` objekt med det angivna[`StringFormatFlags`](../stringformatflags/) uppräkning och språk. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Får en generisk standard`StringFormat` objekt. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Får en generisk typografi`StringFormat` objekt. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Hämtar eller ställer in textjusteringsinformation på det vertikala planet. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Hämtar eller ställer in språket som används när lokala siffror ersätts med västerländska siffror. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Hämtar eller ställer in metoden som ska användas för siffersubstitution. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Hämtar antalet blanksteg mellan början av en textrad och det första tabbstoppet. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Hämtar eller sätter en[`StringFormatFlags`](../stringformatflags/) uppräkning som innehåller formateringsinformation. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Hämtar eller ställer in[`HotkeyPrefix`](../hotkeyprefix/) objekt för detta`StringFormat` objekt. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Hämtar eller ställer in linjeinriktningen på horisontalplanet. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Får en rad avstånd mellan tabbstopp i de enheter som anges av[`PageUnit`](../graphics/pageunit/) egenskap. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Hämtar eller ställer in[`StringTrimming`](../stringtrimming/) uppräkning för detta`StringFormat` objekt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Skapar en djup klon av detta`StringFormat` objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Ställer in tabbstopp för detta`StringFormat` objekt. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Konverterar detta`StringFormat` objekt mot en läsbar sträng. |

### Se även

* class [DisposableObject](../disposableobject/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


