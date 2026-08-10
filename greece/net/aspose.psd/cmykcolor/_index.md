---
title: "Δομή CmykColor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Δομή Aspose.PSD.CmykColor. Το χρώμα CMYK του pixel"
type: docs
weight: 270
url: /el/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

Το χρώμα CMYK του pixel.

```csharp
public struct CmykColor
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Λαμβάνει το κενό. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Λαμβάνει την τιμή του κυανίου στοιχείου αυτής της δομής [`Color`](../color/). |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [`Color`](../color/) δεν είναι αρχικοποιημένη. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Λαμβάνει την τιμή του μαύρου συστατικού αυτής της δομής [`Color`](../color/). |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Λαμβάνει την τιμή του συστατικού ματζέντα αυτής της δομής [`Color`](../color/). |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Λαμβάνει την τιμή του κίτρινου συστατικού αυτής της δομής [`Color`](../color/). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Δημιουργεί μια δομή `CmykColor` από τιμές 32-bit κυανής, ματζέντα, κίτρινου και μαύρου. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | Η μετατροπή από ARGB 32-bit σε CMYKColor. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Η λήψη του κώδικα κατακερματισμού. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Η τιμή προορισμού. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | Η μετατροπή από CMYKColor σε χρώμα ARGB 32-bit χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | Η μετατροπή από χρώμα ARGB 32-bit σε CMYKColor. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | Η μετατροπή από CMYKColor σε Color. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματικό το [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


