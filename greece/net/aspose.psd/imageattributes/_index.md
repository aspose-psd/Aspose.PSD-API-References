---
title: "Κλάση ImageAttributes"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ImageAttributes κλάση. Ένα αντικείμενο ImageAttributes περιέχει πληροφορίες σχετικά με το πώς τα χρώματα bitmap και metafile τροποποιούνται κατά τη διαδικασία απόδοσης. Ένα αντικείμενο ImageAttributes διατηρεί πολλές ρυθμίσεις προσαρμογής χρώματος, συμπεριλαμβανομένων πινάκων προσαρμογής χρώματος, πινάκων προσαρμογής γκρι κλίμακας, τιμών διόρθωσης γάμμα, πινάκων χάρτη χρωμάτων και τιμών κατωφλίου χρώματος. Κατά τη διαδικασία απόδοσης, τα χρώματα μπορούν να διορθωθούν, σκοτεινιάσουν, φωτιστούν και να αφαιρεθούν. Για να εφαρμόσετε τέτοιες τροποποιήσεις, αρχικοποιήστε ένα αντικείμενο ImageAttributes και περάστε τη διαδρομή αυτού του αντικειμένου ImageAttributes μαζί με τη διαδρομή μιας Image στη μέθοδο DrawImage."
type: docs
weight: 5080
url: /el/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Ένα αντικείμενο `ImageAttributes` περιέχει πληροφορίες σχετικά με το πώς τα χρώματα bitmap και metafile τροποποιούνται κατά τη διαδικασία απόδοσης. Ένα αντικείμενο `ImageAttributes` διατηρεί πολλές ρυθμίσεις προσαρμογής χρώματος, συμπεριλαμβανομένων πινάκων προσαρμογής χρώματος, πινάκων προσαρμογής γκρι κλίμακας, τιμών διόρθωσης γάμμα, πινάκων χάρτη χρωμάτων και τιμών κατωφλίου χρώματος. Κατά τη διαδικασία απόδοσης, τα χρώματα μπορούν να διορθωθούν, σκοτεινιάσουν, φωτιστούν και να αφαιρεθούν. Για να εφαρμόσετε τέτοιες τροποποιήσεις, αρχικοποιήστε ένα αντικείμενο `ImageAttributes` και περάστε τη διαδρομή αυτού του αντικειμένου `ImageAttributes` (μαζί με τη διαδρομή ενός [`Image`](../image/)) στη μέθοδο DrawImage.

```csharp
public sealed class ImageAttributes
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος πινέλου αυτού του αντικειμένου `ImageAttributes`. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Καθαρίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Καθαρίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Καθαρίζει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Καθαρίζει τη ρύθμιση εξόδου καναλιού CMYK (cyan-magenta-yellow-black) για την προεπιλεγμένη κατηγορία. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Καθαρίζει τη ρύθμιση εξόδου καναλιού (cyan-magenta-yellow-black) για μια καθορισμένη κατηγορία. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Καθαρίζει τη ρύθμιση προφίλ χρώματος εξόδου καναλιού για την προεπιλεγμένη κατηγορία. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Καθαρίζει τη ρύθμιση προφίλ χρώματος εξόδου καναλιού για μια καθορισμένη κατηγορία. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Καθαρίζει την τιμή κατωφλίου για την προεπιλεγμένη κατηγορία. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Καθαρίζει την τιμή κατωφλίου για μια καθορισμένη κατηγορία. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για μια καθορισμένη κατηγορία. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ορίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Απενεργοποιεί τη ρύθμιση χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Ορίζει το κατώφλι (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Ορίζει το κατώφλι (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί μια υφή σε ένα σχήμα, ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί μια υφή σε ένα σχήμα, ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί μια υφή σε ένα σχήμα, ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


