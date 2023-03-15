---
title: Class FontSettings
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FontSettings classe. Impostazioni dei caratteri del renderer dei formati vettoriali PSD generali.
type: docs
weight: 4290
url: /it/net/aspose.psd/fontsettings/
---
## FontSettings class

Impostazioni dei caratteri del renderer dei formati vettoriali PSD generali.

```csharp
public static class FontSettings
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Ottiene o imposta il nome predefinito del font. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Cancella tutte le sostituzioni di font |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Ottiene il nome del font Adobe in base al nome della famiglia di font. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Ottiene le cartelle dei font predefinite. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Ottiene l'array di sostituzione dei caratteri in base al nome del carattere |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Words cerca i font TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Ottiene il carattere sostitutivo più adatto. Se non sono consentite tutte le sostituzioni, verrà restituito per primo il carattere consentito e disponibile. Se non ci sono caratteri disponibili, verrà restituito il carattere dall'argomento |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Determina se [è consentito il font] [il nome del font specificato]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Ripristina la cartella dei caratteri e il nome del carattere predefinito sui valori predefiniti del sistema. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Limita i caratteri utilizzando un elenco di caratteri. Si prega di controllare i nomi dei caratteri reali prima della limitazione Impostare l'elenco dei caratteri consentiti su Nullo per rimuovere le restrizioni |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Imposta l'elenco di sostituzione dei caratteri. Se il carattere non è consentito, verrà trovata la sostituzione. Il primo carattere nell'elenco verrà utilizzato per primo. Se anche questo viene limitato, verrà selezionato il font successivo dall'elenco. Se il font non ha sostituzioni o tutte le sostituzioni non sono consentite, verrà utilizzato il primo font consentito dall'elenco dei font consentiti. Se non ci sono font consentiti e disponibili, la libreria lo farà prova a utilizzare il carattere predefinito del sistema anche se non è consentito. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Questa è una scorciatoia per[`SetFontsFolders`](./setfontsfolders/) per l'impostazione di una sola directory dei font. Non vengono eseguiti controlli sulla cartella dei font. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati. Non vengono eseguiti controlli sulle cartelle dei font. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Aggiorna la cache dei caratteri per i file PSD che contengono livelli di testo. Questo metodo garantisce che i caratteri dalla cartella fontsFolder using method FontSettings.SetFontsFolder(fontsFolder) o dopo il ripristino dei font utilizzando FontSettings.Reset() verranno presi in considerazione durante l'elaborazione dei file PSD. Utilizza questo metodo ogni volta che FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() ha richiamato immagini PSD. Senza chiamare questo metodo non vi è alcuna garanzia che i caratteri verranno aggiornati. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


