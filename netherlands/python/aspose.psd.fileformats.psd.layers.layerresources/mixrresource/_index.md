---
title: "MixrResource Klasse"
type: docs
weight: 680
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Initialiseert een nieuw exemplaar van de [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) klasse.<br/>            PSD-formaatspecificatie bevat de volgende beschrijving:<br/>            2 Versie ( = 1)<br/>            2 Monochroom<br/>            20 RGB of CMYK kleur plus constante voor de mixerinstellingen. 4 * 2 bytes kleur met 2 bytes constante. |
| [MixrResource(data)](#MixrResource_data_2) | Initialiseert een nieuw exemplaar van de [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) klasse.<br/>            PSD-formaatspecificatie bevat de volgende beschrijving:<br/>            2 Versie ( = 1)<br/>            2 Monochroom<br/>            20 RGB of CMYK kleur plus constante voor de mixerinstellingen. 4 * 2 bytes kleur met 2 bytes constante. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| monochrome | bool | r/w | Geeft of stelt een waarde in die aangeeft of deze [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) monochroom is. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| version | short | r/w | Haalt de versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Geeft de ruwe gegevens van de kanaalinformatie. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Slaat de bron op in de opgegeven streamcontainer. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Stelt de kanaalinformatie in. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Initialiseert een nieuw exemplaar van de [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) klasse.<br/>            PSD-formaatspecificatie bevat de volgende beschrijving:<br/>            2 Versie ( = 1)<br/>            2 Monochroom<br/>            20 RGB of CMYK kleur plus constante voor de mixerinstellingen. 4 * 2 bytes kleur met 2 bytes constante.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Initialiseert een nieuw exemplaar van de [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) klasse.<br/>            PSD-formaatspecificatie bevat de volgende beschrijving:<br/>            2 Versie ( = 1)<br/>            2 Monochroom<br/>            20 RGB of CMYK kleur plus constante voor de mixerinstellingen. 4 * 2 bytes kleur met 2 bytes constante.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De gegevens van de bron. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Geeft de ruwe gegevens van de kanaalinformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | Ruwe byte-array van kanaalinformatie. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Stelt de kanaalinformatie in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |
| value | byte | De value. |

