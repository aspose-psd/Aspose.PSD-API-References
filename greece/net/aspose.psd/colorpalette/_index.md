---
title: "Κλάση ColorPalette"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.ColorPalette. Ορίζει έναν πίνακα χρωμάτων που σχηματίζουν μια παλέτα χρωμάτων. Τα χρώματα είναι 32-bit ARGB χρώματα. Δεν είναι κληρονομήσιμη"
type: docs
weight: 370
url: /el/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Ορίζει έναν πίνακα χρωμάτων που αποτελούν μια παλέτα χρωμάτων. Τα χρώματα είναι 32-bit ARGB χρώματα. Δεν είναι κληρονομήσιμη.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ColorPalette` και το IsCompactPalette είναι ψευδές. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ColorPalette` και το IsCompactPalette είναι ψευδές. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ColorPalette`. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ColorPalette`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Λαμβάνει έναν πίνακα δομών 32-bit ARGB. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Λαμβάνει έναν πίνακα δομών [`Color`](../color/). |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται συμπαγής παλέτα. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Αντιγράφει την παλέτα. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Αντιγράφει την παλέτα. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Λαμβάνει το χρώμα παλέτας 32-bit ARGB κατά δείκτη. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Λαμβάνει το χρώμα της παλέτας κατά δείκτη. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος. |

### Δείτε επίσης

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


