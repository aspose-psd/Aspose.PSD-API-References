---
title: "Classe VscgResource"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Initialise une nouvelle instance de la classe VscgResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Obtient ou définit le tableau des éléments de structure.<br/>            **Warning:** Les valeurs du tableau `Items` doivent correspondre à la propriété `KeyForData`, qui détermine le type de paramètres de remplissage stockés dans les structures du `Items`. |
| clé | int | r | Obtient la clé de ressource du calque. |
| key_for_data | int | r | Obtient la clé entière qui définit le type de paramètres de remplissage stockés dans la ressource :<br/>            * Couleur - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Dégradé - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Motif - 0x5074466c - PtFlResource.TypeToolKey<br/>            Warning! La valeur de la propriété KeyForData doit correspondre au type de paramètres de remplissage stockés dans les structures Items. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Initialise une nouvelle instance de la classe VscgResource

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

