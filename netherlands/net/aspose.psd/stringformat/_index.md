---
title: Class StringFormat
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.StringFormat klas. Bevat tekstlayoutinformatie zoals uitlijning oriëntatie en tabstops weergavemanipulaties zoals invoeging van weglatingstekens en vervanging van nationale cijfers en OpenTypefuncties. Deze klasse kan niet worden geërfd.
type: docs
weight: 5670
url: /nl/net/aspose.psd/stringformat/
---
## StringFormat class

Bevat tekstlay-outinformatie (zoals uitlijning, oriëntatie en tabstops), weergavemanipulaties (zoals invoeging van weglatingstekens en vervanging van nationale cijfers) en OpenType-functies. Deze klasse kan niet worden geërfd.

```csharp
public sealed class StringFormat : DisposableObject
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initialiseert een nieuw`StringFormat` object. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initialiseert een nieuw`StringFormat` object van de opgegeven bestaande`StringFormat` object. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initialiseert een nieuw`StringFormat` object met het opgegeven[`StringFormatFlags`](../stringformatflags/) opsomming en taal. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Krijgt een algemene standaardwaarde`StringFormat` object. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Krijgt een algemene typografie`StringFormat` object. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Haalt tekstuitlijningsinformatie op of stelt deze in op het verticale vlak. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Hiermee wordt de taal opgehaald of ingesteld die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Hiermee wordt de methode voor cijfervervanging opgehaald of ingesteld. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Krijgt het aantal spaties tussen het begin van een regel tekst en de eerste tabstop. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Haalt of zet a[`StringFormatFlags`](../stringformatflags/) opsomming die opmaakinformatie bevat. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Haalt of stelt de[`HotkeyPrefix`](../hotkeyprefix/) bezwaar maken hiervoor`StringFormat` object. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Haalt of stelt de lijnuitlijning op het horizontale vlak in. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Krijgt een matrix van afstanden tussen tabstops in de eenheden gespecificeerd door de[`PageUnit`](../graphics/pageunit/) eigenschap. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Haalt of stelt de[`StringTrimming`](../stringtrimming/) opsomming hiervoor`StringFormat` object. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Maakt hiervan een diepe kloon`StringFormat` object. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Stelt hiervoor tabstops in`StringFormat` object. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Converteert dit`StringFormat` bezwaar maken tegen een door mensen leesbare string. |

### Zie ook

* class [DisposableObject](../disposableobject/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


