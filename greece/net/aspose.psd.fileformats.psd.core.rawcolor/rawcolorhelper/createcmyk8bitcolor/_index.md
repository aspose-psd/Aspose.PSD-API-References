---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "RawColorHelper μέθοδος. Δημιουργεί χρώμα CMYK 8bit ανά κανάλι"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Δημιουργεί χρώμα CMYK 8-bit ανά κανάλι.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | Byte | Η τιμή του συστατικού κυανίου (0-255). |
| m | Byte | Η τιμή του συστατικού ματζέντας (0-255). |
| y | Byte | Η τιμή του συστατικού κίτρινου (0-255). |
| k | Byte | Η τιμή του συστατικού κλειδί (μαύρο) (0-255). |

### Τιμή Επιστροφής

Μια νέα παρουσία [`RawColor`](../../rawcolor/) που αντιπροσωπεύει το χρώμα CMYK.

## Σχόλια

Τα συστατικά του χρώματος συσκευάζονται σε έναν 32-bit ακέραιο με τη σειρά: κυανό (bits 24-31), ματζέντα (bits 16-23), κίτρινο (bits 8-15) και κλειδί/μαύρο (bits 0-7).

### Δείτε επίσης

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


