---
title: "Classe SoLdResource"
type: docs
weight: 930
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---

**Summary:** Defines the SoLdResource class that contains information about a smart object layer in a PSD file.<br/>            Is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLdResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SoLdResource()](#SoLdResource__1) | Initialise une nouvelle instance de la classe [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) .<br/>            Ce constructeur par défaut est conçu pour être utilisé par [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/).<br/>            Utilisez [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) pour créer des classes SoLdResource. |
| [SoLdResource(unique_id, is_custom, has_comp_info)](#SoLdResource_unique_id_is_custom_has_comp_info_2) | Initialise une nouvelle instance de la classe [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) .<br/>            Il est nécessaire de définir la propriété Items ou d'appeler InitializeItems() pour obtenir une instance prête.<br/>            Ce constructeur est conçu pour être utilisé par [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            et dans les tests unitaires.<br/>            Utilisez [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) pour créer des classes SoLdResource. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type : 'SoLd'. |
| anti_alias_policy | int | r/w | Obtient ou définit la politique d'anticrénelage des données de calque d'objet intelligent dans l'image PSD. |
| bottom | double | r/w | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| comp | int | r/w | Obtient ou définit la valeur comp des données de calque d'objet intelligent dans le fichier PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Compositions de calques dans les objets intelligents</see> |
| comp_id | int | r/w | Obtient ou définit l'ID du comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné.<br/>            Les comps sont des compositions d'une mise en page que les concepteurs peuvent créer. En utilisant les compositions de calques, vous pouvez créer, gérer et visualiser plusieurs versions<br/>            d'une mise en page dans un seul fichier Adobe® Photoshop® . Une composition de calque est un instantané d'un état du panneau Calques. Les compositions de calques enregistrent trois types d'options de calque mais<br/>            cette propriété obtient l'identifiant de sélection de la composition de calque pour le calque d'objet intelligent dans le fichier PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Compositions de calques dans les objets intelligents</see> |
| crop | int | r/w | Obtient ou définit le recadrage des données de calque d'objet intelligent dans l'image PSD. |
| duration_denominator | int | r/w | Obtient ou définit le dénominateur de la durée. |
| duration_numerator | int | r/w | Obtient ou définit le numérateur de la durée. |
| frame_count | int | r/w | Obtient ou définit le nombre d'images de la smart object layer data dans le fichier PSD. |
| frame_step_denominator | int | r/w | Obtient ou définit le dénominateur du pas d'image. |
| frame_step_numerator | int | r/w | Obtient ou définit le numérateur du pas d'image. |
| hauteur | double | r/w | Obtient ou définit la hauteur. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| horizontal_mesh_points | double | r/w | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| is_custom | bool | r/w | Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé.<br/>            Si vrai, il contient des points de maillage. Si défini sur false, il supprime les points de maillage. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtient ou définit les éléments de descripteur de la smart object layer data dans le fichier PSD. |
| clé | int | r | Obtient la clé de ressource du calque. |
| gauche | double | r/w | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| longueur | int | r | Obtient la longueur de la ressource d'objet dynamique en octets. |
| non_affine_transform_matrix | double | r/w | Obtient ou définit la matrice de transformation non affine de la smart object layer data dans le fichier PSD. |
| original_comp_id | int | r | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné.<br/>            Cette propriété obtient l'identifiant de sélection du Comp de calque original pour le smart object layer dans le fichier PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Composants de calque dans les objets dynamiques</see> |
| page_number | int | r/w | Obtient ou définit le numéro de page de la smart object layer data dans le fichier PSD. |
| perspective | double | r/w | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| perspective_other | double | r/w | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| placed_id | Guid | r/w | Obtient ou définit l'identifiant unique de cette smart object layer data dans l'image PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Obtient ou définit le type de la smart object layer data dans le fichier PSD. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| resolution | double | r/w | Obtient ou définit la résolution de la smart object layer data dans le fichier PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtient ou définit l'unité de mesure de la résolution de la smart object layer data dans le fichier PSD. |
| droite | double | r/w | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| signature | int | r | Obtient la signature. |
| haut | double | r/w | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| total_pages | int | r/w | Obtient ou définit le nombre total de pages de la smart object layer data dans le fichier PSD. |
| transform_matrix | double | r/w | Obtient ou définit la matrice de transformation de la smart object layer data dans le fichier PSD. |
| u_order | int | r/w | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| unique_id | Guid | r/w | Obtient ou définit l'identifiant unique global de la smart object layer data [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) dans l'image PSD. |
| v_order | int | r/w | Obtient ou définit la valeur d'ordre V du calque placé dans le fichier PSD. |
| valeur | double | r/w | Obtient ou définit la valeur de déformation du calque placé dans l'image PSD. |
| version | int | r | Obtient la version du calque placé dans le fichier PSD, généralement 3-5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Obtient ou définit l'unité de mesure des points de maillage verticaux. |
| vertical_mesh_points | double | r/w | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| width | double | r/w | Obtient ou définit la largeur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource d'objet intelligent dans le conteneur de flux spécifié. |


### Constructor: SoLdResource() {#SoLdResource__1}


```
 SoLdResource() 
```

Initialise une nouvelle instance de la classe [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) .<br/>            Ce constructeur par défaut est conçu pour être utilisé par [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/).<br/>            Utilisez [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) pour créer des classes SoLdResource.

### Constructor: SoLdResource(unique_id, is_custom, has_comp_info) {#SoLdResource_unique_id_is_custom_has_comp_info_2}


```
 SoLdResource(unique_id, is_custom, has_comp_info) 
```

Initialise une nouvelle instance de la classe [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) .<br/>            Il est nécessaire de définir la propriété Items ou d'appeler InitializeItems() pour obtenir une instance prête.<br/>            Ce constructeur est conçu pour être utilisé par [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/)<br/>            et dans les tests unitaires.<br/>            Utilisez [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) pour créer des classes SoLdResource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| unique_id | Guid | L'identifiant unique des données du calque d'objet dynamique [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |
| is_custom | bool | si défini sur <c>true</c> [is custom]. |
| has_comp_info | bool | si défini sur <c>true</c> [has comp information]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre la ressource d'objet intelligent dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

