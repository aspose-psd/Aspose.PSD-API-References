---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD för .NET API-referens
description: FontSettings metod. Ställer in teckensnittsersättningslistan. Om teckensnitt inte tillåts kommer det att hittas som ersättning. Det första teckensnittet i listan kommer att användas först. Om det också begränsas kommer nästa teckensnitt att väljas från listan. Om teckensnittet inte har ersättningar eller alla ersättningar inte är tillåtna kommer det att användas först tillåtna teckensnitt från listan med tillåtna teckensnitt. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att använda försök använda systemets standardteckensnitt även om det inte är tillåtet.
type: docs
weight: 110
url: /sv/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Ställer in teckensnittsersättningslistan. Om teckensnitt inte tillåts kommer det att hittas som ersättning. Det första teckensnittet i listan kommer att användas först. Om det också begränsas, kommer nästa teckensnitt att väljas från listan. Om teckensnittet inte har ersättningar eller alla ersättningar inte är tillåtna kommer det att användas först tillåtna teckensnitt från listan med tillåtna teckensnitt. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att använda försök använda systemets standardteckensnitt även om det inte är tillåtet.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontToReplace | String | Teckensnittet som ska ersättas. |
| fontNames | String[] | Ersättningsteckensnittets namn i likhetsordning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Längden på Font Array och Font Differences Array måste vara lika |

### Exempel

Följande kod demonstrerar förmågan att programmässigt begränsa teckensnitt med hjälp av.

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

### Se även

* class [FontSettings](../)
* namnutrymme [Aspose.PSD](../../fontsettings/)
* hopsättning [Aspose.PSD](../../../)


