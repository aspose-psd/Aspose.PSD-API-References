---
title: FontSettings.GetReplacementFont
second_title: Aspose.PSD for .NET API Reference
description: FontSettings method. Gets the most suitable replacement font. If all replacements are not allowed then will returned first allowed and available font. If there are no available fonts then will be returned font from argument
type: docs
weight: 80
url: /net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Gets the most suitable replacement font. If all replacements are not allowed then will returned first allowed and available font. If there are no available fonts then will be returned font from argument

```csharp
public static string GetReplacementFont(string fontName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | String | Name of the font. |

### Return Value

The name of replaced font

## Examples

The following code demonstrates the ability to programmatically limit fonts using.

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

### See Also

* class [FontSettings](../)
* namespace [Aspose.PSD](../../fontsettings/)
* assembly [Aspose.PSD](../../../)


