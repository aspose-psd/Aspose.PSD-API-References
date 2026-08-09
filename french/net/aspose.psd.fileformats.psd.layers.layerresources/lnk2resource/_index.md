---
title: "Classe Lnk2Resource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource. Définit la classe qui contient des informations sur les fichiers incorporés dans l'image au format PSD. La ressource de lien peut contenir plusieurs instances de LiFdDataSource qui peuvent être accessibles via l'indexeur"
type: docs
weight: 3030
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

Définit la classe qui contient des informations sur les fichiers incorporés dans l'image au format PSD. La ressource de lien peut contenir plusieurs instances de [`LiFdDataSource`](../lifddatasource/) qui peuvent être accessibles via l'indexeur.

```csharp
public class Lnk2Resource : LinkResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | Initialise une nouvelle instance de la classe `Lnk2Resource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtient le nombre de sources de données de lien qui peuvent être accessibles via l'indexeur. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtient une valeur indiquant si cette instance de ressource de lien est vide. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Obtient le [`LiFdDataSource`](../lifddatasource/) à l'index spécifié. (2 indexeurs) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtient la longueur de la ressource de lien globale PSD en octets. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Enregistre les données du bloc de ressources. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | La clé d'information de l'outil de type. |

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


