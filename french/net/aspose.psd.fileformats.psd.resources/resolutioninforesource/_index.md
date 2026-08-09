---
title: "Classe ResolutionInfoResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource classe. La ressource d'informations de résolution"
type: docs
weight: 4350
url: /fr/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
{{< psd/tize >}}
## ResolutionInfoResource class

La ressource d'information de résolution

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | DPI horizontal. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Obtient ou définit l'unité d'affichage de la hauteur. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Unités d'affichage pour la résolution horizontale. Cela n'affecte que l'interface utilisateur ; la résolution est toujours stockée dans le fichier PSD en pixels/pouce. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | DPI vertical. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Unités d'affichage pour la résolution verticale. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Obtient ou définit l'unité d'affichage de la largeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressource dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs de la ressource. |

### Voir aussi

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


