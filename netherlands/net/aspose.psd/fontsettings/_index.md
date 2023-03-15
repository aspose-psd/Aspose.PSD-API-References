---
title: Class FontSettings
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FontSettings klas. Algemene PSDvectorindelingen rendererlettertypeinstellingen.
type: docs
weight: 4290
url: /nl/net/aspose.psd/fontsettings/
---
## FontSettings class

Algemene PSD-vectorindelingen renderer-lettertype-instellingen.

```csharp
public static class FontSettings
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Haalt de standaardnaam van het lettertype op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Wist alle lettertypevervangingen |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Haalt de naam van het adobe-lettertype op naam van de lettertypefamilie. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Haalt de standaard mappen met lettertypen op. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Haalt de array voor lettertypevervangingen op met de lettertypenaam |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Haalt een kopie op van de array die de lijst met mappen bevat waarin Aspose.Words zoekt naar TrueType-lettertypen. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Haalt het meest geschikte vervangende lettertype op. Als alle vervangingen niet zijn toegestaan, wordt het eerst toegestane en beschikbare lettertype geretourneerd. Als er geen beschikbare lettertypen zijn, wordt het lettertype geretourneerd van argument |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Bepaalt of [lettertype is toegestaan] [de opgegeven lettertypenaam]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Herstelt de map met lettertypen en de naam van het standaardlettertype naar de systeemstandaard. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Beperkt het gebruik van lettertypen door een lijst met lettertypen. Controleer de echte lettertypenamen vóór restriction Stel de lijst met toegestane lettertypen in op Null om restrictrions te verwijderen |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Stelt de lettertypevervangingslijst in. Als lettertype niet is toegestaan, wordt vervanging gezocht. Het eerste lettertype in de lijst wordt als eerste gebruikt. Als het ook beperkt is, wordt het volgende lettertype uit de lijst geselecteerd. Als het lettertype geen vervangingen heeft of alle vervangingen niet zijn toegestaan, wordt het eerste toegestane lettertype uit de lijst met toegestane lettertypen gebruikt. Als er geen toegestane en beschikbare lettertypen zijn, zal de bibliotheek dat doen probeer het standaardlettertype van het systeem te gebruiken, zelfs als dit niet is toegestaan. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Dit is een snelkoppeling naar[`SetFontsFolders`](./setfontsfolders/) voor het instellen van slechts één map met lettertypen. Er worden geen controles uitgevoerd op de map met lettertypen. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Stelt de mappen in waaruit TrueType-lettertypen worden geladen en wist alle geladen lettertypen. Er worden geen controles uitgevoerd op de mappen met lettertypen. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Werkt lettertypecache bij voor PSD-bestanden die tekstlagen bevatten. Deze methode garandeert dat lettertypen uit de map fontsFolder met behulp van de -methode FontSettings.SetFontsFolder(fontsFolder) of na het opnieuw instellen van lettertypen met FontSettings.Reset() in aanmerking worden genomen bij het verwerken van PSD-bestanden. Gebruik deze methode telkens wanneer FontSettings.SetFontsFolder(fontsFolder) of FontSettings.Reset() PSD-afbeeldingen aanriep. Zonder deze methode aan te roepen, is er geen garantie dat lettertypen worden bijgewerkt. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


