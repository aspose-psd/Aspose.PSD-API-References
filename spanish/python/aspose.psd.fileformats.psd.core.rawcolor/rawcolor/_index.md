---
title: "Clase RawColor"
type: docs
weight: 20
url: /es/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Inicializa una nueva instancia de la clase [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/). |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Inicializa una nueva instancia de la clase [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) a partir del formato de datos de píxel usando modos de color predefinidos |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Modo que debe seguir el color. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Obtiene los componentes del color. Cada componente es un canal separado, y si utilizas un esquema de color no popular<br/>            es mejor trabajar con cada canal por separado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Obtiene el color como entero en caso de que sea posible obtenerlo. |
| [get_as_long()](#get_as_long__2) | Obtiene el color como largo en caso de que sea posible obtenerlo. |
| [get_bit_depth()](#get_bit_depth__3) | Obtiene la profundidad de bits del Color Crudo. <br/>            Por ejemplo, para un color ARGB con 8 bits por canal/componente es 32<br/>            La profundidad de bits de un color ARGB completo con 16 bits por canal/componente es 64.<br/>            La profundidad de bits se acumula a partir de la suma de las profundidades de bits de los canales. <br/>            Es posible si diferentes canales tienen diferentes profundidades de bits. |
| [get_color_mode_name()](#get_color_mode_name__4) | Obtiene el nombre del modo de color. El nombre del modo de color se acumula a partir de los nombres de los canales/componentes. |
| [set_as_int(value)](#set_as_int_value_5) | Establece datos a todos los canales a partir de un argumento entero si es posible. |
| [set_as_long(value)](#set_as_long_value_6) | Establece datos a todos los canales a partir de un argumento entero si es posible. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Inicializa una nueva instancia de la clase [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Los componentes de color personalizados. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Inicializa una nueva instancia de la clase [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) a partir del formato de datos de píxel usando modos de color predefinidos

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | El formato de datos de píxel. |
| color_mode | short | Modo que debe seguir el color. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Obtiene el color como entero en caso de que sea posible obtenerlo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Datos de canales almacenados en entero |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Obtiene el color como largo en caso de que sea posible obtenerlo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | Datos de canales almacenados en entero |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Obtiene la profundidad de bits del Color Crudo. <br/>            Por ejemplo, para un color ARGB con 8 bits por canal/componente es 32<br/>            La profundidad de bits de un color ARGB completo con 16 bits por canal/componente es 64.<br/>            La profundidad de bits se acumula a partir de la suma de las profundidades de bits de los canales. <br/>            Es posible si diferentes canales tienen diferentes profundidades de bits.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La suma de todas las profundidades de bits de los canales |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Obtiene el nombre del modo de color. El nombre del modo de color se acumula a partir de los nombres de los canales/componentes.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Cadena con el nombre del modo de color |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Establece datos a todos los canales a partir de un argumento entero si es posible.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | int | El valor entero que contiene los datos del componente |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Establece datos a todos los canales a partir de un argumento entero si es posible.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | long | El valor entero que contiene los datos del componente |

