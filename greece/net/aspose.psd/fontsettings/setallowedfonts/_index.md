---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD για Αναφορά API .NET
description: FontSettings μέθοδος. Περιορίζει τη γραμματοσειρά χρησιμοποιώντας κατά λίστα γραμματοσειρών. Ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από περιορισμό Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε limitrions
type: docs
weight: 100
url: /el/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

Περιορίζει τη γραμματοσειρά χρησιμοποιώντας κατά λίστα γραμματοσειρών. Ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από περιορισμό Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε limitrions

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontList | String[] | Η λίστα γραμματοσειρών. |

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


