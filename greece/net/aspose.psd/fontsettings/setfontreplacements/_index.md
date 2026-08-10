---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FontSettings. Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν είναι επιτρεπτή, θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτα. Εάν αυτή επίσης είναι περιορισμένη, θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή όλες οι αντικαταστάσεις δεν είναι επιτρεπτές, θα χρησιμοποιηθεί η πρώτη επιτρεπτή γραμματοσειρά από τη λίστα επιτρεπτών γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπτές και διαθέσιμες γραμματοσειρές, η βιβλιοθήκη θα προσπαθήσει να χρησιμοποιήσει την προεπιλεγμένη γραμματοσειρά του συστήματος ακόμη και αν δεν είναι επιτρεπτή."
type: docs
weight: 130
url: /el/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτη. Εάν αυτή επίσης περιορίζεται, θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή όλες οι αντικαταστάσεις δεν επιτρέπονται, θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπόμενες και διαθέσιμες γραμματοσειρές, η βιβλιοθήκη θα προσπαθήσει να χρησιμοποιήσει τη προεπιλεγμένη γραμματοσειρά του συστήματος ακόμη και αν δεν επιτρέπεται.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontToReplace | String | Η γραμματοσειρά προς αντικατάσταση. |
| fontNames | String[] | Τα ονόματα των γραμματοσειρών αντικατάστασης με σειρά ομοιότητας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Το μήκος του Font Array και του Font Differences Array πρέπει να είναι ίσο. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα περιορισμού των γραμματοσειρών προγραμματιστικά χρησιμοποιώντας.

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


