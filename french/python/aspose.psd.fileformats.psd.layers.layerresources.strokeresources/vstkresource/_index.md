---
title: "Classe VstkResource"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Initialise une nouvelle instance de la classe VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| fill_enabled | bool | r/w | Obtient ou définit une valeur indiquant si le remplissage du Stroke est activé. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Obtient ou définit les paramètres de remplissage du trait. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| stroke_enabled | bool | r/w | Obtient ou définit une valeur indiquant si l'effet de trait est activé. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Obtient ou définit le mode de fusion du Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Obtient ou définit l'entité Stroke. La propriété détermine les paramètres de remplissage du trait. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Obtient ou définit l'alignement de la ligne du style de trait. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Obtient ou définit le type du capuchon de ligne du style de trait. |
| stroke_style_line_cap_width | double | r/w | Obtient ou définit la largeur du capuchon de ligne du Stroke. |
| stroke_style_line_dash_offset | int | r/w | Obtient ou définit le décalage du tiret de ligne du style de trait. |
| stroke_style_line_dash_set | double | r/w | Obtient ou définit le tableau des tirets de ligne. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Obtient ou définit le type de jointure de ligne du style Stroke. |
| stroke_style_line_width | double | r/w | Obtient ou définit la largeur de ligne du Stroke. |
| stroke_style_miter_limit | double | r/w | Obtient ou définit la limite d'onglet du style de trait. |
| stroke_style_opacity | int | r/w | Obtient ou définit l'opacité du style Stroke (0-100%). |
| stroke_style_resolution | double | r/w | Obtient ou définit la résolution du style de trait. |
| stroke_style_scale_lock | bool | r/w | Obtient ou définit le verrouillage de l'échelle du style de trait. |
| stroke_style_stroke_adjust | bool | r/w | Obtient ou définit l'ajustement du trait. |
| stroke_style_version | int | r/w | Obtient ou définit la version du style de trait. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Initialise une nouvelle instance de la classe VstkResource

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

