---
title: "ColorRangeHsl Klasse"
type: docs
weight: 180
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Initialiseert een nieuw exemplaar van de [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) klasse. |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Initialiseert een nieuw exemplaar van de [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| tint | short | r/w | Geeft of stelt de tint in. |
| left_border | short | r/w | Geeft of stelt de linkergrens in. |
| lichtheid | short | r/w | Geeft of stelt de lichtheid in. |
| most_left_border | short | r/w | Geeft of stelt de meest linkergrens in. |
| most_right_border | short | r/w | Geeft of stelt de meest rechtergrens in. |
| right_border | short | r/w | Geeft of stelt de rechtergrens in. |
| verzadiging | short | r/w | Haalt of stelt de verzadiging in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Geeft de bereikcoëfficiënt. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Bepaalt of de tint zich in een groot bereik bevindt. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Bepaalt of de tint zich in een klein bereik bevindt. |
| [save(stream_container)](#save_stream_container_4) | Slaat gegevens op in de opgegeven streamcontainer. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Initialiseert een nieuw exemplaar van de [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) klasse.

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Initialiseert een nieuw exemplaar van de [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De kleurbereikgegevens. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Geeft de bereikcoëfficiënt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tint | double | De tintwaarde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | Verzadigingsbereikcoëfficiënt. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Bepaalt of de tint zich in een groot bereik bevindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tint | double | De tintwaarde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als tint zich in een groot bereik bevindt; anders <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Bepaalt of de tint zich in een klein bereik bevindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tint | double | De tintwaarde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als tint in klein bereik; anders <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Slaat gegevens op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |

