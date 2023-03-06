---
title: Class FontSettings
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FontSettings klass. Allmänna PSD vektorformat renderer teckensnittsinställningar.
type: docs
weight: 4290
url: /sv/net/aspose.psd/fontsettings/
---
## FontSettings class

Allmänna PSD vektorformat renderer teckensnittsinställningar.

```csharp
public static class FontSettings
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Hämtar eller ställer in standardnamnet på teckensnittet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Rensar alla teckensnittsersättningar |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Hämtar Adobe-teckensnittsnamnet efter teckensnittets efternamn. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Hämtar standardmapparna för teckensnitt. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Hämtar teckensnittsersättningsmatrisen med teckensnittet name |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Får en kopia av arrayen som innehåller listan över mappar där Aspose.Words letar efter TrueType-teckensnitt. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Får det mest lämpliga ersättningsteckensnittet. Om alla ersättningar inte är tillåtna kommer det att returneras först tillåtna och tillgängliga teckensnitt. Om det inte finns några tillgängliga teckensnitt returneras typsnitt från argument |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Avgör om [är teckensnitt tillåtet] [det angivna teckensnittsnamnet]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Återställer teckensnittsmappen och standardteckensnittsnamnet till systemets standard. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Begränsar teckensnitt med en lista med teckensnitt. Kontrollera riktiga teckensnittsnamn innan restriction Ställ in listan över tillåtna teckensnitt till Null för att ta bort restrictrions |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Ställer in teckensnittsersättningslistan. Om teckensnitt inte tillåts kommer det att hittas som ersättning. Det första teckensnittet i listan kommer att användas först. Om det också begränsas, kommer nästa teckensnitt att väljas från listan. Om teckensnittet inte har ersättningar eller alla ersättningar inte är tillåtna kommer det att användas först tillåtna teckensnitt från listan med tillåtna teckensnitt. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att använda försök använda systemets standardteckensnitt även om det inte är tillåtet. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Detta är en genväg till[`SetFontsFolders`](./setfontsfolders/) för att endast ställa in en typsnittskatalog. Det görs inga kontroller av mappen teckensnitt. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Ställer in mapparna där TrueType-teckensnitt laddas från och rensar alla inlästa teckensnitt. Det görs inga kontroller av typsnittsmapparna. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Uppdaterar typsnittscache för PSD-filer som innehåller textlager. Denna metod garanterar att typsnitt från mappen fontsFolder using -metoden FontSettings.SetFontsFolder(fontsFolder) eller efter återställning av teckensnitt med FontSettings.Reset() kommer att beaktas vid bearbetning av PSD-filer. Använd den här metoden varje gång FontSettings.SetFontsFolder(fontsFolder) eller FontSettings.Reset() begärde PSD-bilder. Utan att anropa denna metod finns det ingen garanti för att teckensnitt kommer att uppdateras. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


