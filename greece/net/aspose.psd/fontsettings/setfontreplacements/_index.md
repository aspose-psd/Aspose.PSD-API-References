---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD για Αναφορά API .NET
description: FontSettings μέθοδος. Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται τότε θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτη. Εάν περιορίστηκε επίσης τότε θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή δεν επιτρέπονται όλες οι αντικαταστάσεις τότε θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπόμενες και διαθέσιμες γραμματοσειρές τότε η βιβλιοθήκη θα δοκιμάστε να χρησιμοποιήσετε την προεπιλεγμένη γραμματοσειρά του συστήματος ακόμα κι αν δεν επιτρέπεται.
type: docs
weight: 110
url: /el/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, τότε θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτη. Εάν περιορίστηκε επίσης, τότε θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή δεν επιτρέπονται όλες οι αντικαταστάσεις, τότε θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπόμενες και διαθέσιμες γραμματοσειρές, τότε η βιβλιοθήκη θα δοκιμάστε να χρησιμοποιήσετε την προεπιλεγμένη γραμματοσειρά του συστήματος ακόμα κι αν δεν επιτρέπεται.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontToReplace | String | Η γραμματοσειρά προς αντικατάσταση. |
| fontNames | String[] | Τα ονόματα των γραμματοσειρών αντικατάστασης κατά σειρά ομοιότητας. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Το μήκος του πίνακα γραμματοσειρών και του πίνακα διαφορών γραμματοσειρών πρέπει να είναι ίσα |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα προγραμματισμού περιορισμού γραμματοσειρών με χρήση.

```csharp
[C#]

string srcFile = "fonts_com_updated.psd";
string output = "etalon_fonts_com_updated.psd.png";

try
{
    var fontList = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    FontSettings.SetAllowedFonts(fontList);

    var myriadReplacement = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    var calibriReplacement = new string[] { "Webdings", "Courier New", "Bookman Old Style" };
    var arialReplacement = new string[] { "Bookman Old Style", "Courier New", "Webdings" };
    var timesReplacement = new string[] { "Arial", "NotExistedFont", "Courier New" };

    FontSettings.SetFontReplacements("MyriadPro-Regular", myriadReplacement);
    FontSettings.SetFontReplacements("Calibri", calibriReplacement);
    FontSettings.SetFontReplacements("Arial", arialReplacement);
    FontSettings.SetFontReplacements("Times New Roman", timesReplacement);

    using (PsdImage image = (PsdImage)Image.Load(srcFile))
    {
        image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
finally
{
    FontSettings.SetAllowedFonts(null);
    FontSettings.ClearFontReplacements();
}
```

### Δείτε επίσης

* class [FontSettings](../)
* χώρος ονομάτων [Aspose.PSD](../../fontsettings/)
* συνέλευση [Aspose.PSD](../../../)


