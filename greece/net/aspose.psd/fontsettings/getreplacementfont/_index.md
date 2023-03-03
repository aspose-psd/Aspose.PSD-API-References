---
title: FontSettings.GetReplacementFont
second_title: Aspose.PSD για Αναφορά API .NET
description: FontSettings μέθοδος. Λαμβάνει την πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν δεν επιτρέπονται όλες οι αντικαταστάσεις τότε θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές τότε θα επιστραφεί γραμματοσειρά από το argument
type: docs
weight: 70
url: /el/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

Λαμβάνει την πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν δεν επιτρέπονται όλες οι αντικαταστάσεις, τότε θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, τότε θα επιστραφεί γραμματοσειρά από το argument

```csharp
public static string GetReplacementFont(string fontName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα της γραμματοσειράς. |

### Επιστρεφόμενη Αξία

Το όνομα της γραμματοσειράς που αντικαταστάθηκε

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


