---
title: FontSettings.ClearFontReplacements
second_title: Aspose.PSD voor .NET API-referentie
description: FontSettings methode. Wist alle lettertypevervangingen
type: docs
weight: 20
url: /nl/net/aspose.psd/fontsettings/clearfontreplacements/
---
## FontSettings.ClearFontReplacements method

Wist alle lettertypevervangingen

```csharp
public static void ClearFontReplacements()
```

### Voorbeelden

De volgende code demonstreert de mogelijkheid om lettertypen programmatisch te beperken met behulp van.

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

### Zie ook

* class [FontSettings](../)
* naamruimte [Aspose.PSD](../../fontsettings/)
* montage [Aspose.PSD](../../../)


