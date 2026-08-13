---
title: "FilterEffectMaskData Classe"
type: docs
weight: 310
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Initialise une nouvelle instance de la classe [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Obtient les canaux. |
| guid | chaîne | r | Obtient le GUID. |
| longueur | int | r | Obtient la longueur des données du masque de filtre en octets. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtient le rectangle du masque de feuille. |
| max_channels | int | r | Obtient le maximum du nombre de canaux. |
| pixels_depth | int | r | Obtient la profondeur des pixels. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtient le rectangle des canaux. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Obtient le masque de feuille. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Obtient le masque utilisateur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Initialise une nouvelle instance de la classe [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | chaîne | Le guid de la ressource. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle des canaux. |
| pixels_depth | int | La profondeur des pixels. |
| max_channels | int | La valeur maximale des canaux. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Les canaux. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Le masque utilisateur. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle du masque de feuille. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Le masque de feuille. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |

