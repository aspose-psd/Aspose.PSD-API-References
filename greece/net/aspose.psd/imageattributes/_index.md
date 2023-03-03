---
title: Class ImageAttributes
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageAttributes τάξη. ΑνImageAttributes Το αντικείμενο περιέχει πληροφορίες σχετικά με τον τρόπο χειραγώγησης των χρωμάτων bitmap και metafile κατά την απόδοση. ΕναImageAttributes Το αντικείμενο διατηρεί πολλές ρυθμίσεις προσαρμογής χρώματος συμπεριλαμβανομένων πίνακες προσαρμογής χρώματος πίνακες προσαρμογής κλίμακας του γκρι τιμές διόρθωσης γάμμα πίνακες χαρτών χρωμάτων και τιμές κατωφλίου χρώματος. Κατά τη διάρκεια της απόδοσης τα χρώματα μπορούν να διορθωθούν να σκουρύνουν να φωτιστούν και να αφαιρεθούν. Για να εφαρμόσετε τέτοιους χειρισμούς αρχικοποιήστε έναImageAttributesαντικείμενο και περάστε το μονοπάτι αυτούImageAttributes αντικείμενο μαζί με τη διαδρομή ενόςImage  στη μέθοδο DrawImage.
type: docs
weight: 4610
url: /el/net/aspose.psd/imageattributes/
---
## ImageAttributes class

Αν`ImageAttributes` Το αντικείμενο περιέχει πληροφορίες σχετικά με τον τρόπο χειραγώγησης των χρωμάτων bitmap και metafile κατά την απόδοση. Ενα`ImageAttributes` Το αντικείμενο διατηρεί πολλές ρυθμίσεις προσαρμογής χρώματος, συμπεριλαμβανομένων πίνακες προσαρμογής χρώματος, πίνακες προσαρμογής κλίμακας του γκρι, τιμές διόρθωσης γάμμα, πίνακες χαρτών χρωμάτων και τιμές κατωφλίου χρώματος. Κατά τη διάρκεια της απόδοσης, τα χρώματα μπορούν να διορθωθούν, να σκουρύνουν, να φωτιστούν και να αφαιρεθούν. Για να εφαρμόσετε τέτοιους χειρισμούς, αρχικοποιήστε ένα`ImageAttributes`αντικείμενο και περάστε το μονοπάτι αυτού`ImageAttributes` αντικείμενο (μαζί με τη διαδρομή ενός[`Image`](../image/) ) στη μέθοδο DrawImage.

```csharp
public sealed class ImageAttributes
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Καθαρίζει τον πίνακα χρωματικής αντιστοίχισης πινέλου από αυτό`ImageAttributes` αντικείμενο. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Διαγράφει το έγχρωμο πλήκτρο (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Διαγράφει το πλήκτρο χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Διαγράφει τη μήτρα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Διαγράφει τη μήτρα προσαρμογής χρώματος για μια καθορισμένη κατηγορία. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Διαγράφει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Διαγράφει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Διαγράφει τη ρύθμιση καναλιού εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Διαγράφει τη ρύθμιση του καναλιού εξόδου (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Διαγράφει τη ρύθμιση προφίλ χρώματος καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Διαγράφει τη ρύθμιση προφίλ χρώματος καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Διαγράφει τον πίνακα color-remap για την προεπιλεγμένη κατηγορία. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Διαγράφει τον πίνακα χρωματικής αναπαράστασης για μια καθορισμένη κατηγορία. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Διαγράφει την τιμή κατωφλίου για την προεπιλεγμένη κατηγορία. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Διαγράφει την τιμή κατωφλίου για μια καθορισμένη κατηγορία. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Ορίζει τον πίνακα color-remap για την κατηγορία πινέλου. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Ορίζει το πλήκτρο χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Ορίζει το πλήκτρο χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ορίζει τον πίνακα προσαρμογής χρώματος και τον πίνακα προσαρμογής κλίμακας του γκρι για μια καθορισμένη κατηγορία. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Ορίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Ορίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ορίζει τη μήτρα προσαρμογής χρώματος για μια καθορισμένη κατηγορία. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Απενεργοποιεί τη ρύθμιση χρώματος για την προεπιλεγμένη κατηγορία. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Ορίζει το αρχείο προφίλ χρώματος καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Ορίζει το αρχείο προφίλ χρώματος καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Ορίζει τον πίνακα color-remap για την προεπιλεγμένη κατηγορία. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Ορίζει τον πίνακα color-remap για μια καθορισμένη κατηγορία. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Ορίζει το όριο (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Ορίζει το όριο (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Ρυθμίζει τη λειτουργία αναδίπλωσης που χρησιμοποιείται για να αποφασίσει πώς να πλακώσει μια υφή σε ένα σχήμα ή στα όρια σχήματος. Μια υφή τοποθετείται με πλακάκια σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Ρυθμίζει τη λειτουργία αναδίπλωσης και το χρώμα που χρησιμοποιούνται για να αποφασίσετε πώς να πλακώσετε μια υφή σε ένα σχήμα ή στα όρια σχήματος. Μια υφή τοποθετείται με πλακάκια σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Ρυθμίζει τη λειτουργία αναδίπλωσης και το χρώμα που χρησιμοποιούνται για να αποφασίσετε πώς να πλακώσετε μια υφή σε ένα σχήμα ή στα όρια σχήματος. Μια υφή τοποθετείται με πλακάκια σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


