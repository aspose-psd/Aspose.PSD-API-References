---
title: "ColorRangeHsl Klasse"
type: docs
weight: 180
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Initialisiert eine neue Instanz der [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) Klasse. |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Initialisiert eine neue Instanz der [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Farbton | short | r/w | Liest oder legt den Farbton fest. |
| left_border | short | r/w | Liest oder setzt den linken Rand. |
| Helligkeit | short | r/w | Liest oder legt die Helligkeit fest. |
| most_left_border | short | r/w | Liest oder setzt den am weitesten linken Rand. |
| most_right_border | short | r/w | Liest oder setzt den am weitesten rechten Rand. |
| right_border | short | r/w | Liest oder setzt den rechten Rand. |
| Sättigung | short | r/w | Liest oder setzt die Sättigung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Liest den Bereichskoeffizienten. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Bestimmt, ob der Farbton im großen Bereich liegt. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Bestimmt, ob der Farbton im kleinen Bereich liegt. |
| [save(stream_container)](#save_stream_container_4) | Speichert Daten in den angegebenen Stream‑Container. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Initialisiert eine neue Instanz der [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) Klasse.

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Initialisiert eine neue Instanz der [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Farbbereichsdaten. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Liest den Bereichskoeffizienten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Farbton | double | Der Farbtonwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Sättigungsbereichskoeffizient. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Bestimmt, ob der Farbton im großen Bereich liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Farbton | double | Der Farbtonwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn der Farbton im großen Bereich liegt; andernfalls <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Bestimmt, ob der Farbton im kleinen Bereich liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Farbton | double | Der Farbtonwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn der Farbton im kleinen Bereich liegt; andernfalls <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Speichert Daten in den angegebenen Stream‑Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |

