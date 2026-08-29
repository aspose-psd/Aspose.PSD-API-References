---
title: "FontSettings.IsFontAllowed"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FontSettings. Καθορίζει εάν είναι επιτρεπτή η καθορισμένη γραμματοσειρά."
type: docs
weight: 90
url: /el/net/aspose.psd/fontsettings/isfontallowed/
---
{{< psd/tize >}}
## FontSettings.IsFontAllowed method

Καθορίζει εάν [is font allowed] [το συγκεκριμένο όνομα γραμματοσειράς].

```csharp
public static bool IsFontAllowed(string fontName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα της γραμματοσειράς. |

### Τιμή Επιστροφής

`true` εάν [is font allowed] [the specified font name]; διαφορετικά, `false`.

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


