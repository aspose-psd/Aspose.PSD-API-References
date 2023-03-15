---
title: Class FontSettings
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FontSettings classe. Paramètres généraux des polices de rendu des formats vectoriels PSD.
type: docs
weight: 4290
url: /fr/net/aspose.psd/fontsettings/
---
## FontSettings class

Paramètres généraux des polices de rendu des formats vectoriels PSD.

```csharp
public static class FontSettings
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Obtient ou définit le nom par défaut de la police. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Efface tous les remplacements de polices |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Obtient le nom de la police Adobe par nom de famille de polices. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Obtient les dossiers de polices par défaut. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Obtient le tableau des remplacements de polices par le nom de la police |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Obtient une copie du tableau qui contient la liste des dossiers où Aspose.Words recherche les polices TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Obtient la police de remplacement la plus appropriée. Si tous les remplacements ne sont pas autorisés, la première police autorisée et disponible sera renvoyée. S'il n'y a pas de polices disponibles, la police de l'argument sera renvoyée. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Détermine si [la police est autorisée] [le nom de police spécifié]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Réinitialise le dossier des polices et le nom de la police par défaut à la valeur par défaut du système. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Restreint l'utilisation des polices par liste de polices. Veuillez vérifier les noms de police réels avant restriction Définir la liste des polices autorisées sur Null pour supprimer les restrictions |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Définit la liste de remplacement des polices. Si la police n'est pas autorisée, elle sera remplacée. La première police de la liste sera utilisée en premier. Si elle est également restreinte, la police suivante sera sélectionnée dans la liste. Si la police n'a pas de remplacements ou si tous les remplacements ne sont pas autorisés, la première police autorisée de la liste des polices autorisées sera utilisée. S'il n'y a pas de polices autorisées et disponibles, la bibliothèque le fera. essayez d'utiliser la police par défaut du système même si elle n'est pas autorisée. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Ceci est un raccourci vers[`SetFontsFolders`](./setfontsfolders/) pour définir un seul répertoire de polices. Aucune vérification n'est effectuée sur le dossier des polices. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Définit les dossiers à partir desquels les polices TrueType sont chargées et efface toutes les polices chargées. Aucune vérification n'est effectuée sur les dossiers de polices. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Met à jour le cache des polices pour les fichiers PSD contenant des calques de texte. Cette méthode garantit que les polices du dossier fontsFolder using method FontSettings.SetFontsFolder(fontsFolder) ou après la réinitialisation des polices à l'aide de FontSettings.Reset() seront prises en compte lors du traitement des fichiers PSD. Veuillez utiliser cette méthode chaque fois que FontSettings.SetFontsFolder(fontsFolder) ou FontSettings.Reset() appelle des images PSD. Sans appeler cette méthode, il n'y a aucune garantie que les polices seront mises à jour. |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


