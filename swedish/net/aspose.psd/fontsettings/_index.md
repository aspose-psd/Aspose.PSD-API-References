---
title: "Klass FontSettings"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FontSettings-klass. Allmänna teckensnittinställningar för renderaren av PSD-vektormat."
type: docs
weight: 4760
url: /sv/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Allmänna teckensnittsinställningar för PSD-vektorrenderare.

```csharp
public static class FontSettings
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Hämtar eller anger standardnamnet på teckensnittet. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Hämtar eller anger ett värde som indikerar om [get alternative font]. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Rensar alla teckensnittsersättningar |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Hämtar Adobe-teckensnittsnamnet via teckensnittsfamiljens namn. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Hämtar standardmapparna för teckensnitt. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Hämtar teckensnittsersättningsarrayen via teckensnittsnamnet |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Words söker efter TrueType-teckensnitt. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Hämtar det mest lämpliga ersättningsteckensnittet. Om alla ersättningar inte är tillåtna returneras det första tillåtna och tillgängliga teckensnittet. Om det inte finns några tillgängliga teckensnitt returneras teckensnittet från argumentet. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Bestämmer om [is font allowed] [the specified font name]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Tar bort teckensnittscache-filen. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Återställer teckensnittsmappen och standardteckensnittets namn till systemets standard. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Begränsar teckensnittsanvändning med en lista av teckensnitt. Kontrollera de faktiska teckensnittsnamnen innan begränsning. Sätt den tillåtna teckensnittlistan till Null för att ta bort begränsningarna. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Ställer in listan för teckensnittsersättning. Om ett teckensnitt inte är tillåtet kommer en ersättning att hittas. Det första teckensnittet i listan används först. Om det också är begränsat, väljs nästa teckensnitt från listan. Om teckensnittet saknar ersättningar eller alla ersättningar inte är tillåtna, används det första tillåtna teckensnittet från den tillåtna teckensnittlistan. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att försöka använda systemets standardteckensnitt även om det inte är tillåtet. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Detta är en genväg till [`SetFontsFolders`](./setfontsfolders/) för att ange endast en teckensnittskatalog. Det utförs inga kontroller på teckensnittsmappen. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Ställer in katalogerna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt. Det utförs inga kontroller på teckensnittskatalogerna. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Uppdaterar teckensnittscache för PSD-filer som innehåller textrager. Denna metod garanterar att teckensnitt från katalogen fontsFolder som används med metoden FontSettings.SetFontsFolder(fontsFolder) eller efter återställning av teckensnitt med FontSettings.Reset() tas i beaktande vid bearbetning av PSD-filer. Använd denna metod varje gång FontSettings.SetFontsFolder(fontsFolder) eller FontSettings.Reset() anropas för PSD-bilder. Utan att anropa denna metod finns ingen garanti för att teckensnitt uppdateras. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


