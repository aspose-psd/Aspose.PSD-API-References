---
title: FontSettings.IsFontAllowed
second_title: Aspose.PSD per riferimento API .NET
description: FontSettings metodo. Determina se è consentito il font il nome del font specificato.
type: docs
weight: 80
url: /it/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

Determina se [è consentito il font] [il nome del font specificato].

```csharp
public static bool IsFontAllowed(string fontName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Nome del carattere. |

### Valore di ritorno

`VERO` if [è consentito il font] [il nome del font specificato]; Altrimenti,`falso` .

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


