---
title: "Κλάση PsdColorPalette"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette class. Η χρωματική παλέτα PSD"
type: docs
weight: 4040
url: /el/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

Η παλέτα χρωμάτων PSD.

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette` και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette` και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette` και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette` και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PsdColorPalette`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | Λαμβάνει έναν πίνακα 32-bit χρωμάτων ARGB. |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | Λαμβάνει έναν πίνακα δομών [`Color`](../../aspose.psd/color/). |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν υπάρχει διαφανές χρώμα. |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα είναι συμπαγής. |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων της παλέτας χρωμάτων. |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων της παλέτας χρωμάτων. |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | Λαμβάνει το διαφανές χρώμα. |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | Λαμβάνει τον δείκτη του διαφανούς χρώματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | Αντιγράφει την παλέτα. |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Αντιγράφει την παλέτα. |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | Λαμβάνει το χρώμα παλέτας 32-bit ARGB κατά δείκτη. |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | Λαμβάνει το χρώμα της παλέτας κατά δείκτη. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος. |

### Δείτε επίσης

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


