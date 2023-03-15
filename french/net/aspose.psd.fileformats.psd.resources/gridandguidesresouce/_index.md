---
title: Class GridAndGuidesResouce
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce classe. Représente la grille et guide la ressource.
type: docs
weight: 3730
url: /fr/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
## GridAndGuidesResouce class

Représente la grille et guide la ressource.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Obtient la taille des données de ressource en octets. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Obtient ou définit le cycle de grille horizontale. La valeur par défaut est 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Obtient ou définit le cycle de la grille verticale. La valeur par défaut est 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Obtient le nombre de blocs de ressources du guide. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Obtient ou définit les guides. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Obtient ou définit la version de l'en-tête. Cette valeur doit toujours être 1. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Obtient la version psd minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, rembourrée pour rendre la taille égale (un nom nul se compose de deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Devrait toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressources en octets, y compris ses données. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressources dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs des ressources. |

### Voir également

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Assemblée [Aspose.PSD](../../)


