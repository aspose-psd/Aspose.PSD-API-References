---
title: FontSettings.GetReplacementFont
second_title: Aspose.PSD per riferimento API .NET
description: FontSettings metodo. Ottiene il carattere sostitutivo più adatto. Se non sono consentite tutte le sostituzioni verrà restituito per primo il carattere consentito e disponibile. Se non ci sono caratteri disponibili verrà restituito il carattere dallargomento
type: docs
weight: 70
url: /it/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

Ottiene il carattere sostitutivo più adatto. Se non sono consentite tutte le sostituzioni, verrà restituito per primo il carattere consentito e disponibile. Se non ci sono caratteri disponibili, verrà restituito il carattere dall'argomento

```csharp
public static string GetReplacementFont(string fontName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Nome del carattere. |

### Valore di ritorno

Il nome del carattere sostituito

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


