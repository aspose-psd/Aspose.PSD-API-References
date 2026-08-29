---
title: "Klasse StringFormat"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.StringFormat Klasse. Kapselt Informationen zur Textlayout, wie Ausrichtungsorientierung und Tabulatoren, Anzeige-Manipulationen wie das Einfügen von Auslassungszeichen, nationale Ziffernersetzung und OpenType‑Funktionen. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 6170
url: /de/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Kapselt Textlayout-Informationen (wie Ausrichtung, Orientierung und Tabulatoren), Anzeige-Manipulationen (wie Ellipsen-Einfügung und nationale Ziffernersetzung) und OpenType-Funktionen. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class StringFormat : DisposableObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initialisiert ein neues `StringFormat`‑Objekt. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initialisiert ein neues `StringFormat`‑Objekt aus dem angegebenen vorhandenen `StringFormat`‑Objekt. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initialisiert ein neues `StringFormat`‑Objekt mit der angegebenen [`StringFormatFlags`](../stringformatflags/)‑Aufzählung und Sprache. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Ruft ein generisches Standard‑`StringFormat`‑Objekt ab. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Ruft ein generisches typografisches `StringFormat`‑Objekt ab. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Ruft Textausrichtungsinformationen in der Vertikalebene ab oder legt sie fest. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Ruft die benutzerdefinierte Zeichen‑Identität ab oder legt sie fest. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Ruft die Sprache ab oder legt sie fest, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Ruft die Methode ab oder legt sie fest, die für die Ziffernersetzung verwendet wird. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Ruft die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulator ab. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Ruft eine [`StringFormatFlags`](../stringformatflags/)‑Aufzählung ab oder legt sie fest, die Formatierungsinformationen enthält. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Ruft das [`HotkeyPrefix`](../hotkeyprefix/)‑Objekt für dieses `StringFormat`‑Objekt ab oder legt es fest. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Ruft die Zeilenausrichtung in der Horizontalebene ab oder legt sie fest. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Ruft ein Array von Abständen zwischen Tabulatoren in den durch die [`PageUnit`](../graphics/pageunit/)‑Eigenschaft angegebenen Einheiten ab. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Ruft die [`StringTrimming`](../stringtrimming/)‑Aufzählung für dieses `StringFormat`‑Objekt ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Erstellt eine tiefe Kopie dieses `StringFormat`-Objekts. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Prüfen, ob Objekte gleich sind. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Hashcode des aktuellen Objekts abrufen. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Setzt Tabulatoren für dieses `StringFormat`-Objekt. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Konvertiert dieses `StringFormat`-Objekt in eine menschenlesbare Zeichenkette. |

### Siehe auch

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


