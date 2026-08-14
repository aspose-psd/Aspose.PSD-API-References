---
title: "Classe ColorRangeHsl"
type: docs
weight: 180
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Inizializza una nuova istanza della classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Inizializza una nuova istanza della classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| hue | short | r/w | Ottiene o imposta la tonalità. |
| left_border | short | r/w | Ottiene o imposta il bordo sinistro. |
| lightness | short | r/w | Ottiene o imposta la luminosità. |
| most_left_border | short | r/w | Ottiene o imposta il bordo più a sinistra. |
| most_right_border | short | r/w | Ottiene o imposta il bordo più a destra. |
| right_border | short | r/w | Ottiene o imposta il bordo destro. |
| saturazione | short | r/w | Ottiene o imposta la saturazione. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Ottiene il coefficiente di intervallo. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Determina se la tonalità è in un intervallo ampio. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Determina se la tonalità è in un intervallo piccolo. |
| [save(stream_container)](#save_stream_container_4) | Salva i dati nel contenitore di flusso specificato. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Inizializza una nuova istanza della classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Inizializza una nuova istanza della classe [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | byte | I dati dell'intervallo di colore. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Ottiene il coefficiente di intervallo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| hue | double | Il valore della tonalità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Coefficiente dell'intervallo di saturazione. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Determina se la tonalità è in un intervallo ampio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| hue | double | Il valore della tonalità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se la tonalità è in un intervallo ampio; altrimenti, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Determina se la tonalità è in un intervallo piccolo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| hue | double | Il valore della tonalità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se la tonalità è in un intervallo piccolo; altrimenti, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Salva i dati nel contenitore di flusso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |

