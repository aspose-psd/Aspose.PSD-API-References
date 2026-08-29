---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος RawColorHelper. Δημιουργεί ένα χρώμα ARGB 8bit ανά κανάλι"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Δημιουργεί ένα χρώμα ARGB 8-bit ανά κανάλι.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| α | Byte | Η τιμή του συστατικού άλφα (0-255). |
| r | Byte | Η τιμή του συστατικού κόκκινου (0-255). |
| g | Byte | Η τιμή του συστατικού πράσινου (0-255). |
| β | Byte | Η τιμή του συστατικού μπλε (0-255). |

### Τιμή Επιστροφής

Μια νέα παρουσία [`RawColor`](../../rawcolor/) που αντιπροσωπεύει το χρώμα ARGB.

## Σχόλια

Τα συστατικά χρώματος συσκευάζονται σε έναν 32-bit ακέραιο με τη σειρά: άλφα (bits 24-31), κόκκινο (bits 16-23), πράσινο (bits 8-15), και μπλε (bits 0-7).

### Δείτε επίσης

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Δημιουργεί ένα χρώμα ARGB 8-bit ανά κανάλι από το Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| drawingColor | Χρώμα | Το χρώμα System.Drawing |

### Τιμή Επιστροφής

Μια νέα παρουσία [`RawColor`](../../rawcolor/) που αντιπροσωπεύει το χρώμα ARGB.

## Σχόλια

Τα συστατικά χρώματος συσκευάζονται σε έναν 32-bit ακέραιο με τη σειρά: άλφα (bits 24-31), κόκκινο (bits 16-23), πράσινο (bits 8-15), και μπλε (bits 0-7).

### Δείτε επίσης

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


