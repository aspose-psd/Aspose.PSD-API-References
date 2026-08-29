---
title: "Classe LspfResource"
type: docs
weight: 640
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Initialise une nouvelle instance de la classe [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
| [LspfResource(data)](#LspfResource_data_2) | Initialise une nouvelle instance de la classe [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) .<br/>            Avec une valeur personnalisée ou inconnue |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Initialise une nouvelle instance de la classe [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type 1819504742 |
| is_composite_protected | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est protégée contre la composition. |
| is_position_protected | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est protégée contre le positionnement. |
| is_transparency_protected | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est protégée contre la transparence. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Obtient ou définit le type du verrou. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Initialise une nouvelle instance de la classe [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Initialise une nouvelle instance de la classe [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) .<br/>            Avec une valeur personnalisée ou inconnue

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Initialise une nouvelle instance de la classe [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| is_transparency_protected | bool | si défini sur <c>true</c> [est protégé contre la transparence]. |
| is_composite_protected | bool | si défini sur <c>true</c> [est protégé contre le composite]. |
| is_position_protected | bool | si défini sur <c>true</c> [est protégé contre la position]. |

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

