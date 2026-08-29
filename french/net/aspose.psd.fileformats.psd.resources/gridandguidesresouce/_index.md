---
title: "Classe GridAndGuidesResouce"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce. Représente la ressource de grille et de repères"
type: docs
weight: 4200
url: /fr/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
{{< psd/tize >}}
## GridAndGuidesResouce class

Représente la ressource de grille et de repères.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Obtient ou définit le cycle de grille horizontal. La valeur par défaut est 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Obtient ou définit le cycle de grille vertical. La valeur par défaut est 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Obtient le nombre de blocs de ressource de repères. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Obtient ou définit les guides. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Obtient ou définit la version de l'en-tête. Cette valeur doit toujours être 1. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressource en octets, y compris ses données. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressource dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs de la ressource. |

### Voir aussi

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


