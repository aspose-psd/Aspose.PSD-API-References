---
title: "Clase ColorRangeHsl"
type: docs
weight: 180
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Inicializa una nueva instancia de la [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) clase. |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Inicializa una nueva instancia de la [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| hue | short | r/w | Obtiene o establece el hue. |
| left_border | short | r/w | Obtiene o establece el borde izquierdo. |
| lightness | short | r/w | Obtiene o establece el lightness. |
| most_left_border | short | r/w | Obtiene o establece el borde más a la izquierda. |
| most_right_border | short | r/w | Obtiene o establece el borde más a la derecha. |
| right_border | short | r/w | Obtiene o establece el borde derecho. |
| saturación | short | r/w | Obtiene o establece la saturación. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Obtiene el coeficiente del rango. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Determina si el tono está en un rango amplio. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Determina si el tono está en un rango pequeño. |
| [save(stream_container)](#save_stream_container_4) | Guarda los datos en el contenedor de flujo especificado. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Inicializa una nueva instancia de la [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) clase.

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Inicializa una nueva instancia de la [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) clase.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos del rango de color. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Obtiene el coeficiente del rango.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| hue | double | El valor del tono. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | Coeficiente del rango de saturación. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Determina si el tono está en un rango amplio.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| hue | double | El valor del tono. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si el tono está en un rango amplio; de lo contrario, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Determina si el tono está en un rango pequeño.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| hue | double | El valor del tono. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si el matiz está en un rango pequeño; de lo contrario, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Guarda los datos en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |

