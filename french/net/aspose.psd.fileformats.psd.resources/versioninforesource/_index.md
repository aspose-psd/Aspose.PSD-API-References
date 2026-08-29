---
title: "Classe VersionInfoResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Resources.VersionInfoResource classe. Ressource d'informations de version"
type: docs
weight: 4430
url: /fr/net/aspose.psd.fileformats.psd.resources/versioninforesource/
---
{{< psd/tize >}}
## VersionInfoResource class

Ressource d'information de version

```csharp
public sealed class VersionInfoResource : ResourceBlock
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VersionInfoResource](versioninforesource/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/versioninforesource/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [FileVersion](../../aspose.psd.fileformats.psd.resources/versioninforesource/fileversion/) { get; set; } | Obtient ou définit la version du fichier. |
| [HasRealMergedData](../../aspose.psd.fileformats.psd.resources/versioninforesource/hasrealmergeddata/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance possède des données fusionnées réelles. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/versioninforesource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Obtient ou définit le nom de la ressource. Chaîne Pascal, remplie pour que la taille soit paire (un nom nul consiste en deux octets de 0). |
| [ReaderName](../../aspose.psd.fileformats.psd.resources/versioninforesource/readername/) { get; set; } | Obtient ou définit le nom du lecteur. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Obtient la signature de la ressource. Doit toujours être '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Obtient la taille du bloc de ressource en octets, y compris ses données. |
| [Version](../../aspose.psd.fileformats.psd.resources/versioninforesource/version/) { get; set; } | Obtient ou définit la version. |
| [WriterName](../../aspose.psd.fileformats.psd.resources/versioninforesource/writername/) { get; set; } | Obtient ou définit le nom de l'écrivain. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Enregistre le bloc de ressource dans le flux spécifié. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valide les valeurs de la ressource. |

### Voir aussi

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


