---
title: "ColorRangeHsl-klass"
type: docs
weight: 180
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Initierar en ny instans av klassen [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Initierar en ny instans av klassen [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| nyans | short | r/w | Hämtar eller anger nyansen. |
| left_border | short | r/w | Hämtar eller anger den vänstra gränsen. |
| ljushet | short | r/w | Hämtar eller anger ljusheten. |
| most_left_border | short | r/w | Hämtar eller anger den mest vänstra gränsen. |
| most_right_border | short | r/w | Hämtar eller anger den mest högra gränsen. |
| right_border | short | r/w | Hämtar eller anger den högra kanten. |
| mättnad | short | r/w | Hämtar eller anger mättnaden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Hämtar intervallkoefficienten. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Bestämmer om nyansen är i stort intervall. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Bestämmer om nyansen är i litet intervall. |
| [save(stream_container)](#save_stream_container_4) | Sparar data till den angivna strömbehållaren. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Initierar en ny instans av klassen [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Initierar en ny instans av klassen [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Data för färgområde. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Hämtar intervallkoefficienten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyans | double | Nyansvärdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Mättnadsintervallkoefficient. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Bestämmer om nyansen är i stort intervall.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyans | double | Nyansvärdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om nyansen är i stort intervall; annars <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Bestämmer om nyansen är i litet intervall.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyans | double | Nyansvärdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om nyansen är i litet intervall; annars <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Sparar data till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |

