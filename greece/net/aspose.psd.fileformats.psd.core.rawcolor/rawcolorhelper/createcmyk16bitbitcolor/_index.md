---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "RawColorHelper μέθοδος. Δημιουργεί χρώμα CMYK 16bit ανά κανάλι"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Δημιουργεί χρώμα CMYK 16-bit ανά κανάλι.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | UInt16 | Η τιμή του συστατικού κυανίου (0-65535). |
| m | UInt16 | Η τιμή του συστατικού ματζέντας (0-65535). |
| y | UInt16 | Η τιμή του συστατικού κίτρινου (0-65535). |
| k | UInt16 | Η τιμή του συστατικού κλειδιού (μαύρο) (0-65535). |

### Τιμή Επιστροφής

Μια νέα παρουσία [`RawColor`](../../rawcolor/) που αντιπροσωπεύει το χρώμα CMYK.

## Σχόλια

Τα συστατικά χρώματος συσκευάζονται σε έναν 64-bit ακέραιο με τη σειρά: κυανό (bits 48-63), ματζέντα (bits 32-47), κίτρινο (bits 16-31), και κλειδί/μαύρο (bits 0-15).

### Δείτε επίσης

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


