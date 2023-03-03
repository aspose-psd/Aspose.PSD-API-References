---
title: Class FontSettings
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FontSettings τάξη. Γενικές ρυθμίσεις γραμματοσειράς απόδοσης διανυσματικών μορφών PSD.
type: docs
weight: 4290
url: /el/net/aspose.psd/fontsettings/
---
## FontSettings class

Γενικές ρυθμίσεις γραμματοσειράς απόδοσης διανυσματικών μορφών PSD.

```csharp
public static class FontSettings
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Λαμβάνει ή ορίζει το προεπιλεγμένο όνομα της γραμματοσειράς. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Διαγράφει όλες τις γραμματοσειρές αντικαταστάσεις |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Λαμβάνει το όνομα της γραμματοσειράς adobe ανά όνομα οικογένειας γραμματοσειράς. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Λαμβάνει τους προεπιλεγμένους φακέλους γραμματοσειρών. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Λαμβάνει τον πίνακα αντικατάστασης γραμματοσειρών με το όνομα γραμματοσειράς |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα των φακέλων όπου το Aspose.Words αναζητά γραμματοσειρές TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Λαμβάνει την πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν δεν επιτρέπονται όλες οι αντικαταστάσεις, τότε θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, τότε θα επιστραφεί γραμματοσειρά από το argument |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Καθορίζει εάν [επιτρέπεται η γραμματοσειρά] [το καθορισμένο όνομα γραμματοσειράς]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Επαναφέρει τον φάκελο γραμματοσειρών και το προεπιλεγμένο όνομα γραμματοσειράς στην προεπιλογή του συστήματος. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Περιορίζει τη γραμματοσειρά χρησιμοποιώντας κατά λίστα γραμματοσειρών. Ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από περιορισμό Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε limitrions |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, τότε θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτη. Εάν περιορίστηκε επίσης, τότε θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή δεν επιτρέπονται όλες οι αντικαταστάσεις, τότε θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπόμενες και διαθέσιμες γραμματοσειρές, τότε η βιβλιοθήκη θα δοκιμάστε να χρησιμοποιήσετε την προεπιλεγμένη γραμματοσειρά του συστήματος ακόμα κι αν δεν επιτρέπεται. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Αυτή είναι μια συντόμευση για[`SetFontsFolders`](./setfontsfolders/) για ρύθμιση μόνο ενός καταλόγου γραμματοσειρών. Δεν γίνονται έλεγχοι στο φάκελο γραμματοσειρών. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Ορίζει τους φακέλους από τους οποίους φορτώνονται οι γραμματοσειρές TrueType και διαγράφει όλες τις φορτωμένες γραμματοσειρές. Δεν γίνονται έλεγχοι στους φακέλους γραμματοσειρών. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Ενημερώνει την προσωρινή μνήμη γραμματοσειρών για αρχεία PSD που περιέχουν επίπεδα κειμένου. Αυτή η μέθοδος εγγυάται ότι οι γραμματοσειρές από το φάκελο fontsFolder using μέθοδος FontSettings.SetFontsFolder(fontsFolder) ή μετά την επαναφορά γραμματοσειρών χρησιμοποιώντας το FontSettings.Reset() θα ληφθούν υπόψη κατά την επεξεργασία αρχείων PSD. Χρησιμοποιήστε αυτήν τη μέθοδο κάθε φορά όταν FontSettings.SetFontsFolder(fontsFolder) ή FontSettings.Reset() καλούσε για εικόνες PSD. Χωρίς να καλέσετε αυτήν τη Μέθοδο, δεν υπάρχει καμία εγγύηση ότι οι γραμματοσειρές θα ενημερωθούν. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


