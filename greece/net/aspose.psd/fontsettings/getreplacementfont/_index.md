---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FontSettings. Λαμβάνει τη πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν όλες οι αντικαταστάσεις δεν επιτρέπονται, τότε θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, τότε θα επιστραφεί η γραμματοσειρά από το όρισμα."
type: docs
weight: 80
url: /el/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Λαμβάνει τη πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν όλες οι αντικαταστάσεις δεν επιτρέπονται, θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, θα επιστραφεί η γραμματοσειρά από το όρισμα.

```csharp
public static string GetReplacementFont(string fontName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα της γραμματοσειράς. |

### Τιμή Επιστροφής

Το όνομα της αντικατεστημένης γραμματοσειράς

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


