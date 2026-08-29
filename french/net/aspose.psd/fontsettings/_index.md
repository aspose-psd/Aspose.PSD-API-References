---
title: "Classe FontSettings"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FontSettings. Paramètres de police du rendu des formats vectoriels PSD généraux"
type: docs
weight: 4760
url: /fr/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Paramètres de police du rendu des formats vectoriels PSD généraux.

```csharp
public static class FontSettings
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Obtient ou définit le nom par défaut de la police. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Obtient ou définit une valeur indiquant si [get alternative font]. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Efface tous les remplacements de polices |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Obtient le nom de police Adobe à partir du nom de famille de police. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Obtient les dossiers de polices par défaut. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Obtient le tableau des remplacements de police par le nom de police |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Obtient une copie du tableau contenant la liste des dossiers où Aspose.Words recherche les polices TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Obtient la police de remplacement la plus adaptée. Si tous les remplacements ne sont pas autorisés, la première police autorisée et disponible sera retournée. S'il n'y a aucune police disponible, la police fournie en argument sera retournée. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Détermine si [is font allowed] [the specified font name]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Supprime le fichier de cache de police. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Réinitialise le dossier des polices et le nom de police par défaut aux valeurs par défaut du système. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Restreint l'utilisation des polices par une liste de polices. Veuillez vérifier les noms réels des polices avant la restriction. Définissez la liste des polices autorisées sur Null pour supprimer les restrictions. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Définit la liste de remplacement des polices. Si une police n'est pas autorisée, un remplacement sera recherché. La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante de la liste sera sélectionnée. Si la police n'a aucun remplacement ou que tous les remplacements ne sont pas autorisés, la première police autorisée de la liste des polices autorisées sera utilisée. S'il n'existe aucune police autorisée et disponible, la bibliothèque tentera d'utiliser la police par défaut du système même si elle n'est pas autorisée. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Ceci est un raccourci vers [`SetFontsFolders`](./setfontsfolders/) pour définir un seul répertoire de polices. Aucun contrôle n'est effectué sur le dossier des polices. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Définit les dossiers d'où les polices TrueType sont chargées et efface toutes les polices chargées. Aucun contrôle n'est effectué sur les dossiers de polices. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Met à jour le cache des polices pour les fichiers PSD contenant des calques de texte. Cette méthode garantit que les polices du dossier fontsFolder utilisant la méthode `FontSettings.SetFontsFolder(fontsFolder)` ou après réinitialisation des polices avec `FontSettings.Reset()` seront prises en compte lors du traitement des fichiers PSD. Veuillez utiliser cette méthode chaque fois que `FontSettings.SetFontsFolder(fontsFolder)` ou `FontSettings.Reset()` est appelé pour des images PSD. Sans appeler cette méthode, aucune garantie n'est donnée que les polices seront mises à jour. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


