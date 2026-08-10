---
title: "FontSettings.SetAllowedFonts"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FontSettings. Περιορίζει τη χρήση γραμματοσειρών με λίστα γραμματοσειρών. Παρακαλώ ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από τον περιορισμό. Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε τους περιορισμούς"
type: docs
weight: 120
url: /el/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

Περιορίζει τη χρήση γραμματοσειρών με βάση λίστα γραμματοσειρών. Παρακαλώ ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από τον περιορισμό. Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε τους περιορισμούς.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontList | String[] | Η λίστα γραμματοσειρών. |

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


