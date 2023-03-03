---
title: Class LinkResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource classe. Définit la classe LinkResource qui contient des informations sur les fichiers liés ou intégrés dans limage au format PSD. La ressource de lien peut contenir plusieursLinkDataSource instances accessibles par les indexeurs dans nimporte quelle classe dérivée.
type: docs
weight: 2710
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Définit la classe LinkResource qui contient des informations sur les fichiers liés ou intégrés dans l'image au format PSD. La ressource de lien peut contenir plusieurs[`LinkDataSource`](../linkdatasource/) instances accessibles par les indexeurs dans n'importe quelle classe dérivée.

```csharp
public abstract class LinkResource : LayerResource
```

## Propriétés

| Nom | La description |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Obtient le nombre de sources de données de liens accessibles par l'indexeur. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Obtient une valeur indiquant si cette instance de ressource de lien est vide. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Obtient le[`LinkDataSource`](../linkdatasource/) à l'index spécifié qui est l'identifiant unique de la source de données du lien.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Obtient la longueur de ressource de lien global PSD en octets. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Obtient la version du format PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Obtient la signature de ressource de lien global PSD. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Enregistre les données du bloc de ressources. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie unString qui représente cette instance. |

### Voir également

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Assemblée [Aspose.PSD](../../)


