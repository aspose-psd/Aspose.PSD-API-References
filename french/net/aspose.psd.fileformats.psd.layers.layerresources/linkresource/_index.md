---
title: "Classe LinkResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource class. Définit la classe LinkResource qui contient des informations sur les fichiers liés ou incorporés dans l'image au format PSD. La ressource de lien peut contenir plusieurs instances de LinkDataSource qui peuvent être accessibles via des indexeurs dans toute classe dérivée."
type: docs
weight: 3010
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Définit la classe LinkResource qui contient des informations sur les fichiers liés ou incorporés dans l'image au format PSD. La ressource de lien peut contenir plusieurs instances de [`LinkDataSource`](../linkdatasource/) qui peuvent être accessibles via des indexeurs dans toute classe dérivée.

```csharp
public abstract class LinkResource : LayerResource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtient le nombre de sources de données de lien qui peuvent être accessibles via l'indexeur. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtient une valeur indiquant si cette instance de ressource de lien est vide. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Obtient le [`LinkDataSource`](../linkdatasource/) à l'index spécifié, qui est l'identifiant unique de la source de données du lien. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtient la longueur de la ressource de lien globale PSD en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Enregistre les données du bloc de ressources. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


