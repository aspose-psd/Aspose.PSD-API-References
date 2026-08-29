---
title: "Klass StringFormat"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.StringFormat-klass. Inkapslar information om textlayout såsom justeringsorientering och tabbstopp samt displaymanipulationer som ellipsinfogning, nationell siffersubstitution och OpenType-funktioner. Denna klass kan inte ärvas"
type: docs
weight: 6170
url: /sv/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Inkapslar information om textlayout (såsom justering, orientering och tabbstopp), displaymanipulationer (såsom ellipsis‑infogning och nationell siffrors substitution) och OpenType‑funktioner. Denna klass kan inte ärvas.

```csharp
public sealed class StringFormat : DisposableObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initierar ett nytt `StringFormat`-objekt. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initierar ett nytt `StringFormat`-objekt från det angivna befintliga `StringFormat`-objektet. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initierar ett nytt `StringFormat`-objekt med den angivna [`StringFormatFlags`](../stringformatflags/)-enumerationen och språk. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Hämtar ett generiskt standard `StringFormat`-objekt. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Hämtar ett generiskt typografiskt `StringFormat`-objekt. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Hämtar eller anger textjusteringsinformation på den vertikala planet. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Hämtar eller anger den anpassade teckenidentifikatorn. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Hämtar eller anger språket som används när lokala siffror ersätts med västerländska siffror. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Hämtar eller anger metoden som ska användas för siffersubstitution. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Hämtar antalet mellanslag mellan början av en textrad och den första tabbstoppet. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Hämtar eller anger en [`StringFormatFlags`](../stringformatflags/)-enumeration som innehåller formateringsinformation. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Hämtar eller anger [`HotkeyPrefix`](../hotkeyprefix/)-objektet för detta `StringFormat`-objekt. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Hämtar eller anger radjusteringen på det horisontella planet. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Hämtar en array av avstånd mellan tabbstopp i de enheter som anges av egenskapen [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Hämtar eller anger [`StringTrimming`](../stringtrimming/)-enumerationen för detta `StringFormat`-objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Skapar en djup klon av detta `StringFormat`-objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Kontrollera om objekt är lika. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Hämta hashkod för det aktuella objektet. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Anger tabbstopp för detta `StringFormat`-objekt. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Konverterar detta `StringFormat`-objekt till en människoläsbar sträng. |

### Se även

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


