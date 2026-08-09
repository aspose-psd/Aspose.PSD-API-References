---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode FontSettings. Obtient la police de remplacement la plus appropriée. Si toutes les polices de remplacement ne sont pas autorisées, la première police autorisée et disponible sera renvoyée. S'il n'y a aucune police disponible, la police fournie en argument sera renvoyée"
type: docs
weight: 80
url: /fr/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Obtient la police de remplacement la plus adaptée. Si tous les remplacements ne sont pas autorisés, la première police autorisée et disponible sera retournée. S'il n'y a aucune police disponible, la police fournie en argument sera retournée.

```csharp
public static string GetReplacementFont(string fontName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | String | Nom de la police. |

### Valeur de retour

Le nom de la police remplacée

## Exemples

Le code suivant démontre la capacité de limiter les polices de façon programmatique en utilisant.

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
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

### Voir aussi

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


