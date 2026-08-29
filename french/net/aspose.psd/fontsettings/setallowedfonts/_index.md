---
title: "FontSettings.SetAllowedFonts"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode FontSettings. Restreint les polices en utilisant une liste de polices. Veuillez vérifier les noms réels des polices avant la restriction. Définissez la liste de polices autorisées sur Null pour supprimer les restrictions"
type: docs
weight: 120
url: /fr/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

Restreint l'utilisation des polices par une liste de polices. Veuillez vérifier les noms réels des polices avant la restriction. Définissez la liste des polices autorisées sur Null pour supprimer les restrictions.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontList | String[] | La liste des polices. |

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


