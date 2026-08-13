---
title: "Classe ColorRangeHsl"
type: docs
weight: 180
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Initialise une nouvelle instance de la classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Initialise une nouvelle instance de la classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| hue | short | r/w | Obtient ou définit le hue. |
| left_border | short | r/w | Obtient ou définit le bord gauche. |
| lightness | short | r/w | Obtient ou définit la lightness. |
| most_left_border | short | r/w | Obtient ou définit le bord le plus à gauche. |
| most_right_border | short | r/w | Obtient ou définit le bord le plus à droite. |
| right_border | short | r/w | Obtient ou définit le bord droit. |
| saturation | short | r/w | Obtient ou définit la saturation. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Obtient le coefficient de la plage. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Détermine si la teinte est dans une grande plage. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Détermine si la teinte est dans une petite plage. |
| [save(stream_container)](#save_stream_container_4) | Enregistre les données dans le conteneur de flux spécifié. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Initialise une nouvelle instance de la classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Initialise une nouvelle instance de la classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la plage de couleur. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Obtient le coefficient de la plage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| hue | double | La valeur de la teinte. |

**Returns**

| Type | Description |
| :- | :- |
| double | Coefficient de la plage de saturation. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Détermine si la teinte est dans une grande plage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| hue | double | La valeur de la teinte. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si la teinte est dans une grande plage ; sinon, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Détermine si la teinte est dans une petite plage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| hue | double | La valeur de la teinte. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si la teinte est dans une petite plage ; sinon, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Enregistre les données dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |

