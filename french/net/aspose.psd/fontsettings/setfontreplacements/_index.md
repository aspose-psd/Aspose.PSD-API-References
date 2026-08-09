---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode FontSettings. Définit la liste de remplacement des polices. Si une police n'est pas autorisée, un remplacement sera recherché. La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante de la liste sera sélectionnée. Si une police n'a pas de remplacements ou que tous les remplacements sont interdits, la première police autorisée de la liste des polices autorisées sera utilisée. S'il n'existe aucune police autorisée et disponible, la bibliothèque essaiera d'utiliser la police système par défaut même si elle n'est pas autorisée"
type: docs
weight: 130
url: /fr/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Définit la liste de remplacement des polices. Si une police n'est pas autorisée, un remplacement sera recherché. La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante de la liste sera sélectionnée. Si la police n'a aucun remplacement ou que tous les remplacements ne sont pas autorisés, la première police autorisée de la liste des polices autorisées sera utilisée. S'il n'existe aucune police autorisée et disponible, la bibliothèque tentera d'utiliser la police par défaut du système même si elle n'est pas autorisée.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontToReplace | String | La police à remplacer. |
| fontNames | String[] | Les noms des polices de remplacement par ordre de similarité. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | La longueur du tableau des polices et du tableau des différences de polices doit être égale |

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


