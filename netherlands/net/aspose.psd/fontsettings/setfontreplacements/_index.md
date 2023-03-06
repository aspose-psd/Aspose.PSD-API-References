---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD voor .NET API-referentie
description: FontSettings methode. Stelt de lettertypevervangingslijst in. Als lettertype niet is toegestaan wordt vervanging gezocht. Het eerste lettertype in de lijst wordt als eerste gebruikt. Als het ook beperkt is wordt het volgende lettertype uit de lijst geselecteerd. Als het lettertype geen vervangingen heeft of alle vervangingen niet zijn toegestaan wordt het eerste toegestane lettertype uit de lijst met toegestane lettertypen gebruikt. Als er geen toegestane en beschikbare lettertypen zijn zal de bibliotheek dat doen probeer het standaardlettertype van het systeem te gebruiken zelfs als dit niet is toegestaan.
type: docs
weight: 110
url: /nl/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Stelt de lettertypevervangingslijst in. Als lettertype niet is toegestaan, wordt vervanging gezocht. Het eerste lettertype in de lijst wordt als eerste gebruikt. Als het ook beperkt is, wordt het volgende lettertype uit de lijst geselecteerd. Als het lettertype geen vervangingen heeft of alle vervangingen niet zijn toegestaan, wordt het eerste toegestane lettertype uit de lijst met toegestane lettertypen gebruikt. Als er geen toegestane en beschikbare lettertypen zijn, zal de bibliotheek dat doen probeer het standaardlettertype van het systeem te gebruiken, zelfs als dit niet is toegestaan.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontToReplace | String | Het lettertype dat moet worden vervangen. |
| fontNames | String[] | De vervangende lettertypenamen in volgorde van overeenkomst. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Lengte van Font Array en Font Differences Array moeten gelijk zijn |

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


