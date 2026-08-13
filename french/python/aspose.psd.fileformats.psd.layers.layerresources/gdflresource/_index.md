---
title: "Classe GdFlResource"
type: docs
weight: 330
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Initialise une nouvelle instance de la classe GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| align_with_layer | bool | r/w | Obtient ou définit une valeur indiquant si [align with layer]. |
| angle | double | r/w | Obtient ou définit l'angle. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient la couleur du RGB. |
| color_model | chaîne | r/w | Modèle de couleur - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Obtient les points de couleur. |
| dither | bool | r/w | Obtient ou définit une valeur indiquant si ce [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) est dither. |
| gradient_interval | double | r/w | Obtient ou définit l'intervalle du dégradé. |
| gradient_mode | chaîne | r/w | Mode pour ce dégradé.<br/>            Détermine 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\". |
| gradient_name | chaîne | r/w | Obtient ou définit le nom du dégradé. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Obtient ou définit le type du dégradé. |
| horizontal_offset | double | r/w | Obtient ou définit le décalage horizontal. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Couleur maximale du PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Couleur minimale du PixelDataFormat. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| reverse | bool | r/w | Obtient ou définit une valeur indiquant si ce [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) est inversé. |
| rnd_number_seed | int | r/w | La graine aléatoire utilisée pour générer les couleurs du dégradé Noise. |
| roughness | int | r/w | Facteur de rugosité. |
| scale | int | r/w | Obtient ou définit l'échelle. |
| show_transparency | bool | r/w | Indicateur d'affichage de la transparence. |
| signature | int | r | Obtient la signature. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Obtient les points de transparence. |
| use_vector_color | bool | r/w | Indicateur d'utilisation de la couleur vectorielle. |
| vertical_offset | double | r/w | Obtient ou définit le décalage vertical. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Initialise une nouvelle instance de la classe GdFlResource

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

