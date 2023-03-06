---
title: FontSettings.GetFontReplacements
second_title: Aspose.PSD för .NET API-referens
description: FontSettings metod. Hämtar teckensnittsersättningsmatrisen med teckensnittet name
type: docs
weight: 50
url: /sv/net/aspose.psd/fontsettings/getfontreplacements/
---
## FontSettings.GetFontReplacements method

Hämtar teckensnittsersättningsmatrisen med teckensnittet name

```csharp
public static string[] GetFontReplacements(string fontName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | Typsnittets namn. |

### Returvärde

En rad namn på ersättningar för medföljande typsnitt

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


