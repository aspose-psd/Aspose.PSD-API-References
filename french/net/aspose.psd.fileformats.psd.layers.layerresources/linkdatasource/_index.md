---
title: "Classe LinkDataSource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource classe. Définit la classe LinkDataSource qui contient des informations sur un fichier lié ou un actif dans le fichier PSD."
type: docs
weight: 2990
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

Définit la classe LinkDataSource qui contient des informations sur un fichier lié ou un actif dans le fichier PSD.

```csharp
public abstract class LinkDataSource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé. L'état de verrouillage de l'actif, pour les actifs Adobe® Photoshop® СС Libraries. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Obtient ou définit la date de modification de l'actif, pour les actifs Adobe® Photoshop® СС Libraries. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD de la ressource Lnk2 / LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Obtient ou définit l'ID de la composition actuellement sélectionnée pour le document enfant, qui sera -1 si aucune n'est sélectionnée. Les compositions (comps) sont des agencements d'une mise en page que les concepteurs peuvent créer. En utilisant les compositions de calques, vous pouvez créer, gérer et visualiser plusieurs versions d'une mise en page dans un seul fichier Adobe® Photoshop®. Une composition de calque est un instantané d'un état du panneau Calques. Les compositions de calques enregistrent trois types d'options de calque mais cette propriété obtient l'identifiant de sélection de la composition de calque pour les objets dynamiques. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Obtient ou définit le créateur du fichier dans la ressource au format PSD LnkE / Lnk2. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur de fichier ouvert : CompId et OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Obtient une valeur indiquant si cette source de données de lien PSD se lie à l'élément Adobe® Photoshop® СС Library. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Obtient la longueur de la source de données de lien en octets. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Obtient l'ID original de la composition actuellement sélectionnée pour le document enfant, qui sera -1 si aucune n'est sélectionnée. Cette propriété obtient l'identifiant de sélection de la composition de calque originale pour les objets dynamiques. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Obtient le type de source de données de lien global Adobe® Photoshop® qui peut être l'un des suivants ou aucun : le fichier lié intégré liFD qui correspond à la ressource PSD Lnk2Resource, le fichier lié externe liFE qui correspond à la ressource PSD LnkeResource, l'alias de fichier lié liFA. |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Obtient la version de la source de données dans la ressource PSD LnkE / Lnk2. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


