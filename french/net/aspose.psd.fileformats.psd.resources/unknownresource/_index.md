---
title: "Classe UnknownResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Resources.UnknownResource. La ressource inconnue. Lorsqu'un bloc de ressource n'est pas reconnu, ce bloc de ressource est créé."
type: docs
weight: 4410
url: /fr/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
{{< psd/tize >}}
## UnknownResource class

La ressource inconnue. Lorsqu'un bloc de ressource n'est pas reconnu, ce bloc de ressource est créé.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Obtient les données de la ressource. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Obtient la taille des données de la ressource en octets. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Obtient ou définit l'identifiant unique de la ressource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Obtient la version PSD minimale requise. |
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


