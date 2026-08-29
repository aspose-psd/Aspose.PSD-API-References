---
title: "Κλάση FontSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FontSettings class. Γενικές ρυθμίσεις γραμματοσειράς του renderer για διανυσματικές μορφές PSD."
type: docs
weight: 4760
url: /el/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Γενικές ρυθμίσεις γραμματοσειράς του αποτυπωτή διανυσματικών μορφών PSD.

```csharp
public static class FontSettings
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Λαμβάνει ή ορίζει το προεπιλεγμένο όνομα της γραμματοσειράς. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [get alternative font]. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Καθαρίζει όλες τις αντικαταστάσεις γραμματοσειρών. |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Λαμβάνει το όνομα γραμματοσειράς Adobe με βάση το όνομα οικογένειας γραμματοσειράς. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Λαμβάνει τους προεπιλεγμένους φακέλους γραμματοσειρών. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Λαμβάνει τον πίνακα αντικαταστάσεων γραμματοσειράς με βάση το όνομα της γραμματοσειράς. |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα των φακέλων όπου το Aspose.Words αναζητά γραμματοσειρές TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Λαμβάνει τη πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν όλες οι αντικαταστάσεις δεν επιτρέπονται, θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, θα επιστραφεί η γραμματοσειρά από το όρισμα. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Καθορίζει εάν [is font allowed] [το συγκεκριμένο όνομα γραμματοσειράς]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Αφαιρεί το αρχείο προσωρινής μνήμης γραμματοσειρών. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Επαναφέρει το φάκελο γραμματοσειρών και το προεπιλεγμένο όνομα γραμματοσειράς στην προεπιλογή του συστήματος. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Περιορίζει τη χρήση γραμματοσειρών με βάση λίστα γραμματοσειρών. Παρακαλώ ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από τον περιορισμό. Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε τους περιορισμούς. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτη. Εάν αυτή επίσης περιορίζεται, θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή όλες οι αντικαταστάσεις δεν επιτρέπονται, θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπόμενες και διαθέσιμες γραμματοσειρές, η βιβλιοθήκη θα προσπαθήσει να χρησιμοποιήσει τη προεπιλεγμένη γραμματοσειρά του συστήματος ακόμη και αν δεν επιτρέπεται. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Αυτή είναι μια συντόμευση προς [`SetFontsFolders`](./setfontsfolders/) για τον ορισμό ενός μόνο καταλόγου γραμματοσειρών. Δεν πραγματοποιούνται έλεγχοι στον φάκελο γραμματοσειρών. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Ορίζει τους φακέλους από τους οποίους φορτώνονται οι γραμματοσειρές TrueType και καθαρίζει όλες τις φορτωμένες γραμματοσειρές. Δεν πραγματοποιούνται έλεγχοι στους φακέλους γραμματοσειρών. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Ενημερώνει την προσωρινή μνήμη γραμματοσειρών για αρχεία PSD που περιέχουν στρώματα κειμένου. Αυτή η μέθοδος εγγυάται ότι οι γραμματοσειρές από το φάκελο fontsFolder χρησιμοποιώντας τη μέθοδο FontSettings.SetFontsFolder(fontsFolder) ή μετά την επαναφορά γραμματοσειρών με FontSettings.Reset() θα ληφθούν υπόψη κατά την επεξεργασία αρχείων PSD. Παρακαλώ χρησιμοποιήστε αυτή τη μέθοδο κάθε φορά που καλείται FontSettings.SetFontsFolder(fontsFolder) ή FontSettings.Reset() για εικόνες PSD. Χωρίς την κλήση αυτής της Μεθόδου δεν υπάρχει εγγύηση ότι οι γραμματοσειρές θα ενημερωθούν. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


