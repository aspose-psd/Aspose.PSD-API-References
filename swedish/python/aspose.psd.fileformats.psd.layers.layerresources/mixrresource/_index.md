---
title: "MixrResource-klass"
type: docs
weight: 680
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Initierar en ny instans av klassen [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            PSD-formatsspecifikationen innehåller följande beskrivning:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB- eller CMYK-färg plus konstant för mixerinställningarna. 4 * 2 byte färg med 2 byte konstant. |
| [MixrResource(data)](#MixrResource_data_2) | Initierar en ny instans av klassen [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            PSD-formatsspecifikationen innehåller följande beskrivning:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB- eller CMYK-färg plus konstant för mixerinställningarna. 4 * 2 byte färg med 2 byte konstant. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| monochrome | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) är monokrom. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| version | short | r/w | Hämtar eller anger versionen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Hämtar kanalinformationens rådata |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Sparar resursen till den angivna strömbehållaren. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Ställer in kanalinformationen. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Initierar en ny instans av klassen [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            PSD-formatsspecifikationen innehåller följande beskrivning:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB- eller CMYK-färg plus konstant för mixerinställningarna. 4 * 2 byte färg med 2 byte konstant.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Initierar en ny instans av klassen [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            PSD-formatsspecifikationen innehåller följande beskrivning:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB- eller CMYK-färg plus konstant för mixerinställningarna. 4 * 2 byte färg med 2 byte konstant.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Data för resursen. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Hämtar kanalinformationens rådata

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Rå byte-array för kanalinfo. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Ställer in kanalinformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |
| värde | byte | Värdet. |

