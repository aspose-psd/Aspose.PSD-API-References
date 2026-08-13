---
title: "Classe LiFeDataSource"
type: docs
weight: 520
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | Initialise une nouvelle instance de la classe [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Initialise une nouvelle instance de la classe [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adobe_stock_id | chaîne | r/w | Obtient ou définit la bibliothèque graphique AdobeStockId, pour les bibliothèques Adobe® Photoshop® CC. |
| adobe_stock_license_state | chaîne | r | Obtient l'état de la licence Adobe Stock si disponible, pour les bibliothèques Adobe® Photoshop® CC. |
| asset_locked_state | bool | r/w | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé.<br/>            L'état de verrouillage de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® СС. |
| child_doc_id | chaîne | r/w | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD de la ressource Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Obtient ou définit l'ID du comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné.<br/>            Les comps sont des compositions d'une mise en page que les concepteurs peuvent créer. En utilisant les comps de calque, vous pouvez créer, gérer et afficher plusieurs versions<br/>            d'une mise en page dans un seul fichier Adobe® Photoshop®. Un comp de calque est un instantané d'un état du panneau Calques. Les comps de calque enregistrent trois types d'options de calque mais<br/>            cette propriété obtient l'identifiant de sélection du comp de calque pour les objets dynamiques.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Comps de calque dans les objets dynamiques</see> |
| date | datetime | r/w | Obtient ou définit la date et l'heure de la dernière écriture du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| element_name | chaîne | r/w | Obtient ou définit le nom de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| element_ref | chaîne | r/w | Obtient ou définit la référence de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| file_creator | chaîne | r/w | Obtient ou définit le créateur du fichier dans la ressource au format PSD LnkE / Lnk2. |
| file_name | chaîne | r/w | Obtient ou définit le nom du fichier externe ou intégré dans la ressource de lien PSD . |
| file_size | long | r/w | Obtient ou définit la taille du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| file_type | chaîne | r/w | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| full_path | chaîne | r/w | Obtient ou définit le chemin complet du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| has_file_open_descriptor | bool | r/w | Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId. |
| is_library_link | bool | r | Obtient une valeur indiquant si cette source de données de lien PSD pointe vers l'élément de la bibliothèque Adobe® Photoshop® СС |
| longueur | long | r | Obtient la longueur de la source de données du lien en octets. |
| original_comp_id | int | r | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné.<br/>            Cette propriété obtient l'identifiant de sélection du Comp de calque original pour les Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Calques de composition dans les Smart Objects</see> |
| original_file_name | chaîne | r | Obtient le nom de fichier original de la source de données dans la ressource de lien global d'Adobe® Photoshop®. |
| relative_path | chaîne | r/w | Obtient ou définit le chemin relatif du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Obtient le type de source de données du lien global d'Adobe® Photoshop®, qui peut être l'un des suivants ou aucun :<br/>            Le fichier lié incorporé liFD qui correspond à la ressource PSD Lnk2Resource<br/>            Le fichier lié externe liFE qui correspond à la ressource PSD LnkeResource<br/>            L'alias de fichier lié liFA |
| unique_id | Guid | r | Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD. |
| version | int | r | Obtient la version de la source de données dans la ressource PSD LnkE / Lnk2. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

Initialise une nouvelle instance de la classe [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Initialise une nouvelle instance de la classe [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| version | int | La version. |
| unique_id | Guid | L'identifiant unique. |
| original_file_name | chaîne | Nom du fichier original. |
| file_type | chaîne | Type du fichier. |
| file_creator | chaîne | Le créateur du fichier. |

