---
title: LiFdDataSource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Définit la classe de source de données liFD dans le fichier PSD qui contient des informations sur un fichier intégré. Ceci fait partie de lAPI de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe Photoshop
type: docs
weight: 2650
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
## LiFdDataSource class

Définit la classe de source de données liFD dans le fichier PSD qui contient des informations sur un fichier intégré. Ceci fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop®

```csharp
public class LiFdDataSource : LinkDataSource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LiFdDataSource](lifddatasource#constructor)() | Initialise une nouvelle instance du[`LiFdDataSource`](../lifddatasource) classe. |
| [LiFdDataSource](lifddatasource#constructor_1)(int, Guid, string, string, string) | Initialise une nouvelle instance du[`LiFdDataSource`](../lifddatasource) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate) { get; set; } | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé. L'état verrouillé de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® СС. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime) { get; set; } | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® СС. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid) { get; set; } | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD de la ressource Lnk2 / LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid) { get; set; } | Obtient ou définit l'ID de la composition actuellement sélectionnée pour le document enfant, qui sera -1 si aucune n'est sélectionnée. Les compositions sont des compositions d'une mise en page que les concepteurs peuvent créer. Grâce aux compositions de calques, vous pouvez créer, gérer et afficher plusieurs versions d'une mise en page dans un seul fichier Adobe® Photoshop®. Une composition de calque est un instantané d'un état du panneau Calques. Les compositions de calque enregistrent trois types d'options de calque mais cette propriété obtient l'identifiant de sélection de la composition de calque pour les objets intelligents. [Compositions de calques dans les objets intelligents](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data) { get; set; } | Obtient ou définit les données d'objet intelligent intégrées dans le fichier PSD. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator) { get; set; } | Obtient ou définit le créateur de fichier au format PSD LnkE / Lnk2 ressource. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype) { get; set; } | Obtient ou définit le type de fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou relie. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor) { get; set; } | Obtient ou définit une valeur indiquant si cette source de données de lien a le descripteur de fichier ouvert : CompId et OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) { get; } | Obtient une valeur indiquant si cette source de données de lien PSD est liée à l'élément de la bibliothèque Adobe® Photoshop® СС. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length) { get; } | Obtient la longueur de la source de données du lien en octets. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid) { get; } | Obtient l'ID d'origine de la composition actuellement sélectionnée pour le document enfant, qui sera -1 si aucune n'est sélectionnée. Cette propriété obtient l'identifiant de sélection de la couche d'origine pour les objets dynamiques. [Compositions de calques dans les objets intelligents](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename) { get; } | Obtient le nom de fichier d'origine de la source de données dans la ressource de lien global Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type) { get; } | Obtient le type de source de données de lien global Adobe® Photoshop® qui peut être l'un des suivants ou aucun : Le fichier lié intégré liFD qui correspond à PSD Lnk2Resource Le fichier lié externe liFE qui correspond à PSD LnkeResource L'alias de fichier lié liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid) { get; } | Obtient l'identifiant global unique de la source de données dans la ressource de lien PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version) { get; } | Obtient la version de la source de données dans la ressource PSD LnkE / Lnk2. |

### Voir également

* class [LinkDataSource](../linkdatasource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
