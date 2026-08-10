---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "RawColorHelper μέθοδος. Δημιουργεί χρώμα ARGB 16bit ανά κανάλι"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Δημιουργεί ένα χρώμα ARGB 16-bit ανά κανάλι.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| α | UInt16 | Η τιμή του συστατικού άλφα (0-65535). |
| r | UInt16 | Η τιμή του συστατικού κόκκινου (0-65535). |
| g | UInt16 | Η τιμή του συστατικού πράσινου (0-65535). |
| β | UInt16 | Η τιμή του συστατικού μπλε (0-65535). |

### Τιμή Επιστροφής

Μια νέα παρουσία [`RawColor`](../../rawcolor/) που αντιπροσωπεύει το χρώμα ARGB.

## Σχόλια

Τα συστατικά του χρώματος συσκευάζονται σε έναν 64-bit ακέραιο με τη σειρά: άλφα (bits 48-63), κόκκινο (bits 32-47), πράσινο (bits 16-31) και μπλε (bits 0-15).

### Δείτε επίσης

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


