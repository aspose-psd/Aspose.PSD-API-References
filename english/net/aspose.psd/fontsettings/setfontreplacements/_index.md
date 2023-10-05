---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD for .NET API Reference
description: FontSettings method. Sets the font replacement list. If font is not allowed then will be find replacement. The first one font in list will be used first. If it retricted too then will be selected next font from list. If font has not replacements or all replacements are not allowed then will be used first allowed font from allowed font list. If there are no allowed and available fonts then library will try use system default font even if it is not allowed
type: docs
weight: 120
url: /net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Sets the font replacement list. If font is not allowed then will be find replacement. The first one font in list will be used first. If it retricted too, then will be selected next font from list. If font has not replacements or all replacements are not allowed then will be used first allowed font from allowed font list. If there are no allowed and available fonts then library will try use system default font even if it is not allowed.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fontToReplace | String | The font to replace. |
| fontNames | String[] | The replacement font names in order of similarity. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Length of Font Array and Font Differences Array must be equal |

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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


