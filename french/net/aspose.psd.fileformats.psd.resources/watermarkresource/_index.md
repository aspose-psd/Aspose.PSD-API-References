---
title: "Classe WatermarkResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Resources.WatermarkResource classe. Ressource de filigrane"
type: docs
weight: 4440
url: /fr/net/aspose.psd.fileformats.psd.resources/watermarkresource/
---
{{< psd/tize >}}
## WatermarkResource class

Ressource de filigrane

```csharp
public sealed class WatermarkResource : ResourceBlock
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WatermarkResource](watermarkresource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/watermarkresource/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| [IsWatermark](../../aspose.psd.fileformats.psd.resources/watermarkresource/iswatermark/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est un filigrane. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/watermarkresource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
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


