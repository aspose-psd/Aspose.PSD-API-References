---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD per riferimento API .NET
description: FontSettings metodo. Limita i caratteri utilizzando un elenco di caratteri. Si prega di controllare i nomi dei caratteri reali prima della limitazione Impostare lelenco dei caratteri consentiti su Nullo per rimuovere le restrizioni
type: docs
weight: 100
url: /it/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

Limita i caratteri utilizzando un elenco di caratteri. Si prega di controllare i nomi dei caratteri reali prima della limitazione Impostare l'elenco dei caratteri consentiti su Nullo per rimuovere le restrizioni

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontList | String[] | L'elenco dei caratteri. |

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


