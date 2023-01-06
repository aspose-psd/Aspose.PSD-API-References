---
title: SetAllowedFonts
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Limita lutilizzo dei caratteri in base allelenco dei caratteri. Si prega di controllare i nomi dei caratteri reali prima della restrizione Impostare lelenco dei caratteri consentiti su Null per rimuovere le restrizioni
type: docs
weight: 100
url: /it/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

Limita l'utilizzo dei caratteri in base all'elenco dei caratteri. Si prega di controllare i nomi dei caratteri reali prima della restrizione Impostare l'elenco dei caratteri consentiti su Null per rimuovere le restrizioni

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontList | String[] | L'elenco dei caratteri. |

### Esempi

Il codice seguente illustra la possibilità di limitare a livello di codice i caratteri utilizzando.

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

* class [FontSettings](../../fontsettings)
* spazio dei nomi [Aspose.PSD](../../fontsettings)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->