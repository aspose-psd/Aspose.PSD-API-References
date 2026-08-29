---
title: "LinkDataSource Classe"
type: docs
weight: 530
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---

**Summary:** Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé.<br/>            L'état de verrouillage de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® СС. |
| child_doc_id | chaîne | r/w | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD de la ressource Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | Obtient ou définit l'ID du comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné.<br/>            Les comps sont des compositions d'une mise en page que les concepteurs peuvent créer. En utilisant les comps de calque, vous pouvez créer, gérer et afficher plusieurs versions<br/>            d'une mise en page dans un seul fichier Adobe® Photoshop®. Un comp de calque est un instantané d'un état du panneau Calques. Les comps de calque enregistrent trois types d'options de calque mais<br/>            cette propriété obtient l'identifiant de sélection du comp de calque pour les objets dynamiques.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Comps de calque dans les objets dynamiques</see> |
| file_creator | chaîne | r/w | Obtient ou définit le créateur du fichier dans la ressource au format PSD LnkE / Lnk2. |
| file_type | chaîne | r/w | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| has_file_open_descriptor | bool | r/w | Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId. |
| is_library_link | bool | r | Obtient une valeur indiquant si cette source de données de lien PSD pointe vers l'élément de la bibliothèque Adobe® Photoshop® СС |
| longueur | long | r | Obtient la longueur de la source de données du lien en octets. |
| original_comp_id | int | r | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné.<br/>            Cette propriété obtient l'identifiant de sélection du Comp de calque original pour les Smart Objects.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Calques de composition dans les Smart Objects</see> |
| original_file_name | chaîne | r | Obtient le nom de fichier original de la source de données dans la ressource de lien global d'Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Obtient le type de source de données du lien global d'Adobe® Photoshop®, qui peut être l'un des suivants ou aucun :<br/>            Le fichier lié incorporé liFD qui correspond à la ressource PSD Lnk2Resource<br/>            Le fichier lié externe liFE qui correspond à la ressource PSD LnkeResource<br/>            L'alias de fichier lié liFA |
| unique_id | Guid | r | Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD. |
| version | int | r | Obtient la version de la source de données dans la ressource PSD LnkE / Lnk2. |


