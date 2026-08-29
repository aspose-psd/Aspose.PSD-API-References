---
title: "Κλάση CmykColorHelper"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.CmykColorHelper κλάση. Βοηθητικές μέθοδοι για εργασία με χρώμα CMYK που παρουσιάζεται ως υπογεγραμμένη τιμή 32bit ακέραιου. Παρέχει παρόμοιο API με τη δομή CmykColor. Είναι πιο ελαφρύ επειδή το χρώμα CMYK παρουσιάζεται μόνο ως Int32 αντί για δομή με εσωτερικά πεδία. Παρακαλώ προτιμήστε τη χρήση στατικών μεθόδων αυτής της κλάσης όταν είναι δυνατόν αντί της παρωχημένης δομής CmykColor."
type: docs
weight: 280
url: /el/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

Βοηθητικές μέθοδοι για εργασία με χρώμα CMYK που παρουσιάζεται ως υπογεγραμμένη τιμή 32-bit ακέραιου. Παρέχει παρόμοιο API με τη δομή [`CmykColor`](../cmykcolor/). Είναι πιο ελαφρύ επειδή το χρώμα CMYK παρουσιάζεται μόνο ως Int32 αντί για δομή με εσωτερικά πεδία. Παρακαλώ προτιμήστε τη χρήση στατικών μεθόδων όταν είναι δυνατόν αντί της παρωχημένης δομής [`CmykColor`](../cmykcolor/).

```csharp
public static class CmykColorHelper
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Δημιουργεί CMYK από 32-bit τιμές κυανίου, ματζέντας, κίτρινης και μαύρης. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Λαμβάνει την τιμή του συστατικού κυανίου. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Λαμβάνει την τιμή του συστατικού μαύρου. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Λαμβάνει την τιμή του συστατικού ματζέντας. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Λαμβάνει την τιμή του συστατικού κίτρινου. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | Η μετατροπή από χρώμα CMYK σε χρώμα ARGB. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | Η μετατροπή από χρώμα CMYK σε χρώμα ARGB χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | Η μετατροπή από χρώμα CMYK σε χρώμα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένο προφίλ. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Μετατρέπει RGB σε CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


