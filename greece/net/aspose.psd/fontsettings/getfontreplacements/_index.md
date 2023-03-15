---
title: FontSettings.GetFontReplacements
second_title: Aspose.PSD για Αναφορά API .NET
description: FontSettings μέθοδος. Λαμβάνει τον πίνακα αντικατάστασης γραμματοσειρών με το όνομα γραμματοσειράς
type: docs
weight: 50
url: /el/net/aspose.psd/fontsettings/getfontreplacements/
---
## FontSettings.GetFontReplacements method

Λαμβάνει τον πίνακα αντικατάστασης γραμματοσειρών με το όνομα γραμματοσειράς

```csharp
public static string[] GetFontReplacements(string fontName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα της γραμματοσειράς. |

### Επιστρεφόμενη Αξία

Σειρά ονομάτων αντικαταστάσεων για τις παρεχόμενες γραμματοσειρές

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


