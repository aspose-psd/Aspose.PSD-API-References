---
title: FontSettings.ClearFontReplacements
second_title: Aspose.PSD για Αναφορά API .NET
description: FontSettings μέθοδος. Διαγράφει όλες τις γραμματοσειρές αντικαταστάσεις
type: docs
weight: 20
url: /el/net/aspose.psd/fontsettings/clearfontreplacements/
---
## FontSettings.ClearFontReplacements method

Διαγράφει όλες τις γραμματοσειρές αντικαταστάσεις

```csharp
public static void ClearFontReplacements()
```

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


