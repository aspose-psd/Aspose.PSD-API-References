---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FontSettings-metoden. Ställer in listan för teckensnittsersättningar. Om ett teckensnitt inte är tillåtet kommer en ersättning att hittas. Det första teckensnittet i listan används först. Om det också är begränsat väljs nästa teckensnitt i listan. Om teckensnittet saknar ersättningar eller alla ersättningar är otillåtna används det första tillåtna teckensnittet från den tillåtna teckensnittlistan. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att försöka använda systemstandardteckensnittet även om det inte är tillåtet."
type: docs
weight: 130
url: /sv/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Ställer in listan för teckensnittsersättning. Om ett teckensnitt inte är tillåtet kommer en ersättning att hittas. Det första teckensnittet i listan används först. Om det också är begränsat, väljs nästa teckensnitt från listan. Om teckensnittet saknar ersättningar eller alla ersättningar inte är tillåtna, används det första tillåtna teckensnittet från den tillåtna teckensnittlistan. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att försöka använda systemets standardteckensnitt även om det inte är tillåtet.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontToReplace | String | Teckensnittet att ersätta. |
| fontNames | String[] | De ersättande teckensnittsnamnen i ordning efter likhet. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Längden på Font Array och Font Differences Array måste vara lika. |

## Exempel

Följande kod demonstrerar möjligheten att programatiskt begränsa teckensnitt med hjälp av.

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

### Se även

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


