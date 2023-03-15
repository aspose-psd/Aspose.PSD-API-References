---
title: Class CmykColorHelper
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.CmykColorHelper τάξη. Μέθοδοι βοήθειας για εργασία με χρώμα CMYK που παρουσιάζεται ως υπογεγραμμένη ακέραια τιμή 32 bit. Παρέχει το παρόμοιο API με τοCmykColorstruct. Είναι πιο ελαφρύ επειδή το χρώμα CMYK παρουσιάζεται ακριβώς ως Int32 παρά ως δομή με εσωτερικά πεδία. Προτιμήστε να χρησιμοποιείτε στατικές μεθόδους αυτής της κλάσης όταν είναι δυνατόν αντί για το deprecated CmykColor struct.
type: docs
weight: 280
url: /el/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

Μέθοδοι βοήθειας για εργασία με χρώμα CMYK που παρουσιάζεται ως υπογεγραμμένη ακέραια τιμή 32 bit. Παρέχει το παρόμοιο API με το[`CmykColor`](../cmykcolor/)struct. Είναι πιο ελαφρύ επειδή το χρώμα CMYK παρουσιάζεται ακριβώς ως Int32 παρά ως δομή με εσωτερικά πεδία. Προτιμήστε να χρησιμοποιείτε στατικές μεθόδους αυτής της κλάσης όταν είναι δυνατόν αντί για το deprecated [`CmykColor`](../cmykcolor/) struct.

```csharp
public static class CmykColorHelper
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Δημιουργεί CMYK από τιμές κυανό, ματζέντα, κίτρινο και μαύρο 32 bit. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Λαμβάνει την τιμή κυανού στοιχείου. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Λαμβάνει την τιμή μαύρου στοιχείου. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Λαμβάνει την τιμή του ματζέντα στοιχείου. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Λαμβάνει την κίτρινη τιμή στοιχείου. |
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
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Μετατρέπει το RGB σε CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Η μετατροπή από χρώμα ARGB σε χρώμα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Μετατρέπει το RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


