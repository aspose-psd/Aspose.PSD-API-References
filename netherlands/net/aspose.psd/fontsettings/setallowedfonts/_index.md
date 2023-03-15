---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD voor .NET API-referentie
description: FontSettings methode. Beperkt het gebruik van lettertypen door een lijst met lettertypen. Controleer de echte lettertypenamen vóór restriction Stel de lijst met toegestane lettertypen in op Null om restrictrions te verwijderen
type: docs
weight: 100
url: /nl/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

Beperkt het gebruik van lettertypen door een lijst met lettertypen. Controleer de echte lettertypenamen vóór restriction Stel de lijst met toegestane lettertypen in op Null om restrictrions te verwijderen

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontList | String[] | De fontlijst. |

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


