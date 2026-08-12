---
title: "FontSettings.SetAllowedFonts"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FontSettings-metoden. Begränsar teckensnitt med en lista av teckensnitt. Kontrollera de faktiska teckensnittsnamnen innan begränsning. Sätt den tillåtna teckensnittlistan till Null för att ta bort begränsningarna"
type: docs
weight: 120
url: /sv/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

Begränsar teckensnittsanvändning med en lista av teckensnitt. Kontrollera de faktiska teckensnittsnamnen innan begränsning. Sätt den tillåtna teckensnittlistan till Null för att ta bort begränsningarna.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontList | String[] | Teckensnittlistan. |

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


