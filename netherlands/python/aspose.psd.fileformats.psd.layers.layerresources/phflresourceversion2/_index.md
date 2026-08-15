---
title: "PhflResourceVersion2 klasse"
type: docs
weight: 800
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Initialiseert een nieuw exemplaar van de [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) klasse. |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Initialiseert een nieuw exemplaar van de [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| color_space | short | r | Haalt de kleurenruimte op. |
| component_a | short | r/w | Haalt op of stelt de A-component van de kleur in |
| component_b | short | r/w | Haalt op of stelt de B-component in |
| component_l | short | r/w | Haalt op of stelt de L-component van de kleur in |
| density | int | r/w | Haalt de dichtheid op of stelt deze in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| preserve_luminosity | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [preserve luminosity]. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| version | short | r | Haalt de versie op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Haalt de kleur op. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Slaat de bron op in de opgegeven streamcontainer. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Stelt de RGB-kleur in. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Initialiseert een nieuw exemplaar van de [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) klasse.

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Initialiseert een nieuw exemplaar van de [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De gegevens van de bron. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Haalt de kleur op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De RGB-kleur |


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

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Stelt de RGB-kleur in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | De kleur. |

