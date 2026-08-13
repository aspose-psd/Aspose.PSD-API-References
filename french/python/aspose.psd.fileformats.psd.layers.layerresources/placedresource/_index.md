---
title: "Classe PlacedResource"
type: docs
weight: 830
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| anti_alias_policy | int | r/w | Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD. |
| bottom | double | r/w | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| horizontal_mesh_points | double | r/w | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| is_custom | bool | r/w | Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé.<br/>            Si vrai, il contient des points de maillage. Si défini sur false, il supprime les points de maillage. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtient ou définit les éléments de déformation. |
| clé | int | r | Obtient la clé de ressource du calque. |
| gauche | double | r/w | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| page_number | int | r/w | Obtient ou définit le numéro de page du calque placé dans le fichier PSD. |
| perspective | double | r/w | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| perspective_other | double | r/w | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Obtient ou définit le type du calque placé dans le fichier PSD. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| droite | double | r/w | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| signature | int | r | Obtient la signature. |
| haut | double | r/w | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| total_pages | int | r/w | Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD. |
| transform_matrix | double | r/w | Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD. |
| u_order | int | r/w | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| unique_id | Guid | r/w | Obtient ou définit l'identifiant unique global du calque placé dans l'image PSD. |
| v_order | int | r/w | Obtient ou définit la valeur d'ordre V du calque placé dans le fichier PSD. |
| valeur | double | r/w | Obtient ou définit la valeur de déformation du calque placé dans l'image PSD. |
| version | int | r | Obtient la version du calque placé dans le fichier PSD, généralement 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtient ou définit l'unité de mesure des points de maillage verticaux. |
| vertical_mesh_points | double | r/w | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

