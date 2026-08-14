---
title: "Classe FilterEffectMaskData"
type: docs
weight: 310
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Inizializza una nuova istanza della classe [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Restituisce i canali. |
| guid | string | r | Restituisce il GUID. |
| lunghezza | int | r | Restituisce la lunghezza dei dati della maschera filtro in byte. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Restituisce il rettangolo della maschera foglio. |
| max_channels | int | r | Restituisce il valore massimo del conteggio dei canali. |
| pixels_depth | int | r | Restituisce la profondità dei pixel. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Restituisce il rettangolo dei canali. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Restituisce la maschera foglio. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Restituisce la maschera utente. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Salva la risorsa nel contenitore di flusso specificato. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Inizializza una nuova istanza della classe [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| guid | string | Il guid della risorsa. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo dei canali. |
| pixels_depth | int | La profondità dei pixel. |
| max_channels | int | Il valore massimo dei canali. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | I canali. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | La maschera utente. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo della maschera del foglio. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | La maschera del foglio. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Salva la risorsa nel contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |

