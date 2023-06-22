---
title: Class FontSettings
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FontSettings class. General PSD vector formats renderer font settings
type: docs
weight: 4470
url: /net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

General PSD vector formats renderer font settings.

```csharp
public static class FontSettings
```

## Properties

| Name | Description |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Gets or sets the default name of the font. |

## Methods

| Name | Description |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Clears the all fonts replacements |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Gets the adobe font name by font family name. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Gets the default fonts folders. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Gets the font replacements array by the font name |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Gets the most suitable replacement font. If all replacements are not allowed then will returned first allowed and available font. If there are no available fonts then will be returned font from argument |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Determines whether [is font allowed] [the specified font name]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Resets the fonts folder and default font name to the system default. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Restricts font using by list of fonts. Please check real font names before restriction Set Allowed font list to Null to remove restrictrions |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Sets the font replacement list. If font is not allowed then will be find replacement. The first one font in list will be used first. If it retricted too, then will be selected next font from list. If font has not replacements or all replacements are not allowed then will be used first allowed font from allowed font list. If there are no allowed and available fonts then library will try use system default font even if it is not allowed. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | This is a shortcut to [`SetFontsFolders`](./setfontsfolders/) for setting only one font directory. There are no checks performed on the fonts folder. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Sets the folders where TrueType fonts are loaded from and clears all loaded fonts. There are no checks performed on the fonts folders. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using method FontSettings.SetFontsFolder(fontsFolder) or after reset fonts using FontSettings.Reset() will be taken into consideration when processing PSD files. Please use this method each time when FontSettings.SetFontsFolder(fontsFolder) or FontSettings.Reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


