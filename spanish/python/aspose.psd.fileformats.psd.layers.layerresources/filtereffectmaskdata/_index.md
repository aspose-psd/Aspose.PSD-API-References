---
title: "Clase FilterEffectMaskData"
type: docs
weight: 310
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Inicializa una nueva instancia de la clase [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Obtiene los canales. |
| guid | string | r | Obtiene el GUID. |
| longitud | int | r | Obtiene la longitud de los datos de la máscara de filtro en bytes. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtiene el rectángulo de la máscara de hoja. |
| max_channels | int | r | Obtiene el máximo del recuento de canales. |
| pixels_depth | int | r | Obtiene la profundidad de los píxeles. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtiene el rectángulo de los canales. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Obtiene la máscara de hoja. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Obtiene la máscara de usuario. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Inicializa una nueva instancia de la clase [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| guid | string | El guid del recurso. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de los canales. |
| pixels_depth | int | La profundidad de los píxeles. |
| max_channels | int | El valor máximo de canales. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Los canales. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | La máscara de usuario. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de máscara de hoja. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | La máscara de hoja. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |

