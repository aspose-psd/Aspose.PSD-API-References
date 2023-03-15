---
title: Class StringFormat
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.StringFormat klas. Kapselt Textlayoutinformationen z. B. Ausrichtung Ausrichtung und Tabstopps Anzeigemanipulationen z. B. Einfügen von Auslassungspunkten und nationale Ziffernersetzung und OpenTypeFunktionen. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 5670
url: /de/net/aspose.psd/stringformat/
---
## StringFormat class

Kapselt Textlayoutinformationen (z. B. Ausrichtung, Ausrichtung und Tabstopps), Anzeigemanipulationen (z. B. Einfügen von Auslassungspunkten und nationale Ziffernersetzung) und OpenType-Funktionen. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class StringFormat : DisposableObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initialisiert eine neue`StringFormat` Objekt. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initialisiert eine neue`StringFormat` Objekt aus dem angegebenen vorhandenen`StringFormat` Objekt. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initialisiert eine neue`StringFormat` Objekt mit dem angegebenen[`StringFormatFlags`](../stringformatflags/) Aufzählung und Sprache. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Ruft einen generischen Standardwert ab`StringFormat` Objekt. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Ruft eine generische Typografie ab`StringFormat` Objekt. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Ruft Informationen zur Textausrichtung auf der vertikalen Ebene ab oder legt sie fest. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Ruft die Sprache ab oder legt sie fest, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Ruft die für die Ziffernersetzung zu verwendende Methode ab oder legt sie fest. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Ruft die Anzahl der Leerzeichen zwischen dem Anfang einer Textzeile und dem ersten Tabstopp ab. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Holt oder setzt a[`StringFormatFlags`](../stringformatflags/) Aufzählung, die Formatierungsinformationen enthält. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Ruft ab oder setzt die[`HotkeyPrefix`](../hotkeyprefix/) Objekt dazu`StringFormat` Objekt. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Ruft die Linienausrichtung auf der horizontalen Ebene ab oder legt sie fest. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Ruft ein Array von Abständen zwischen Tabstopps in den Einheiten ab, die von angegeben wurden[`PageUnit`](../graphics/pageunit/) Eigentum. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Ruft ab oder setzt die[`StringTrimming`](../stringtrimming/) Aufzählung dazu`StringFormat` Objekt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Erstellt einen tiefen Klon davon`StringFormat` Objekt. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Setzt dafür Tabstopps`StringFormat` Objekt. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Konvertiert dies`StringFormat` Objekt in eine für Menschen lesbare Zeichenfolge. |

### Siehe auch

* class [DisposableObject](../disposableobject/)
* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


