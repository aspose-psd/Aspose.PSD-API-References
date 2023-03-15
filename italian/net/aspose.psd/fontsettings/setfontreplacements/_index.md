---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD per riferimento API .NET
description: FontSettings metodo. Imposta lelenco di sostituzione dei caratteri. Se il carattere non è consentito verrà trovata la sostituzione. Il primo carattere nellelenco verrà utilizzato per primo. Se anche questo viene limitato verrà selezionato il font successivo dallelenco. Se il font non ha sostituzioni o tutte le sostituzioni non sono consentite verrà utilizzato il primo font consentito dallelenco dei font consentiti. Se non ci sono font consentiti e disponibili la libreria lo farà prova a utilizzare il carattere predefinito del sistema anche se non è consentito.
type: docs
weight: 110
url: /it/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Imposta l'elenco di sostituzione dei caratteri. Se il carattere non è consentito, verrà trovata la sostituzione. Il primo carattere nell'elenco verrà utilizzato per primo. Se anche questo viene limitato, verrà selezionato il font successivo dall'elenco. Se il font non ha sostituzioni o tutte le sostituzioni non sono consentite, verrà utilizzato il primo font consentito dall'elenco dei font consentiti. Se non ci sono font consentiti e disponibili, la libreria lo farà prova a utilizzare il carattere predefinito del sistema anche se non è consentito.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontToReplace | String | Il carattere da sostituire. |
| fontNames | String[] | I nomi dei caratteri sostitutivi in ordine di somiglianza. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | La lunghezza di Font Array e Font Differences Array devono essere uguali |

### Esempi

Il codice seguente illustra la possibilità di limitare a livello di codice l'utilizzo dei tipi di carattere.

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

### Guarda anche

* class [FontSettings](../)
* spazio dei nomi [Aspose.PSD](../../fontsettings/)
* assemblea [Aspose.PSD](../../../)


