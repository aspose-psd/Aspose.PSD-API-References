---
title: "FilterEffectMaskData Klasse"
type: docs
weight: 310
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Initialisiert eine neue Instanz der [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Ermittelt die Kanäle. |
| guid | string | r | Ermittelt die GUID. |
| Länge | int | r | Ermittelt die Länge der Filtermaskendaten in Bytes. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Ermittelt das Rechteck der Blattmaske. |
| max_channels | int | r | Ermittelt das Maximum der Kanalanzahl. |
| pixels_depth | int | r | Ermittelt die Pixeltiefe. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Ermittelt das Rechteck der Kanäle. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Ermittelt die Blattmaske. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Ermittelt die Benutzermaske. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Initialisiert eine neue Instanz der [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Die Ressourcen-GUID. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck der Kanäle. |
| pixels_depth | int | Die Pixeltiefe. |
| max_channels | int | Der maximale Kanalwert. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Die Kanäle. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Die Benutzer-Maske. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Blattmaskenrechteck. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Die Blattmaske. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |

