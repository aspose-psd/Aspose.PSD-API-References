---
title: FontSettings.IsFontAllowed
second_title: Aspose.PSD για Αναφορά API .NET
description: FontSettings μέθοδος. Καθορίζει εάν επιτρέπεται η γραμματοσειρά το καθορισμένο όνομα γραμματοσειράς.
type: docs
weight: 80
url: /el/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

Καθορίζει εάν [επιτρέπεται η γραμματοσειρά] [το καθορισμένο όνομα γραμματοσειράς].

```csharp
public static bool IsFontAllowed(string fontName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | String | Όνομα της γραμματοσειράς. |

### Επιστρεφόμενη Αξία

`αληθής` εάν [επιτρέπεται η γραμματοσειρά] [το καθορισμένο όνομα γραμματοσειράς]; σε διαφορετική περίπτωση,`ψευδής` .

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


