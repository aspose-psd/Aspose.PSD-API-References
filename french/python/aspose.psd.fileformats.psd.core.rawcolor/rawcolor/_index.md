---
title: "Classe RawColor"
type: docs
weight: 20
url: /fr/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Initialise une nouvelle instance de la classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/). |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Initialise une nouvelle instance de la classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) à partir du format de données de pixel en utilisant des modes de couleur prédéfinis. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Mode que la couleur doit suivre. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Obtient les composants de la couleur. Chaque composant est un canal séparé, et si vous utilisez un schéma de couleur peu répandu<br/>            il est préférable de travailler avec chaque canal séparément. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Obtient la couleur sous forme d'entier si cela est possible. |
| [get_as_long()](#get_as_long__2) | Obtient la couleur sous forme de long si cela est possible. |
| [get_bit_depth()](#get_bit_depth__3) | Obtient la profondeur de bits de Raw Color. <br/>            Par exemple, pour une couleur ARGB avec 8 bits par canal/composant, la profondeur est de 32<br/>            La profondeur de bits d'une couleur ARGB complète avec 16 bits par canal/composant est de 64.<br/>            La profondeur de bits est accumulée à partir de la somme des profondeurs de bits des canaux. <br/>            C'est possible si différents canaux ont des profondeurs de bits différentes. |
| [get_color_mode_name()](#get_color_mode_name__4) | Obtient le nom du mode couleur. Le nom du mode couleur est accumulé à partir des noms des canaux/composants. |
| [set_as_int(value)](#set_as_int_value_5) | Définit les données de tous les canaux à partir d'un argument entier si possible. |
| [set_as_long(value)](#set_as_long_value_6) | Définit les données de tous les canaux à partir d'un argument entier si possible. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Initialise une nouvelle instance de la classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Les composants de couleur personnalisés. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Initialise une nouvelle instance de la classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) à partir du format de données de pixel en utilisant des modes de couleur prédéfinis.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Le format de données de pixel. |
| color_mode | short | Mode que la couleur doit suivre. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Obtient la couleur sous forme d'entier si cela est possible.

**Returns**

| Type | Description |
| :- | :- |
| int | Données des canaux stockées dans un Int. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Obtient la couleur sous forme de long si cela est possible.

**Returns**

| Type | Description |
| :- | :- |
| long | Données des canaux stockées dans un Int. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Obtient la profondeur de bits de Raw Color. <br/>            Par exemple, pour une couleur ARGB avec 8 bits par canal/composant, la profondeur est de 32<br/>            La profondeur de bits d'une couleur ARGB complète avec 16 bits par canal/composant est de 64.<br/>            La profondeur de bits est accumulée à partir de la somme des profondeurs de bits des canaux. <br/>            C'est possible si différents canaux ont des profondeurs de bits différentes.

**Returns**

| Type | Description |
| :- | :- |
| int | La somme des profondeurs de bits de tous les canaux. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Obtient le nom du mode couleur. Le nom du mode couleur est accumulé à partir des noms des canaux/composants.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Chaîne contenant le nom du mode couleur. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Définit les données de tous les canaux à partir d'un argument entier si possible.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | int | La valeur int qui contient les données du composant. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Définit les données de tous les canaux à partir d'un argument entier si possible.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | long | La valeur int qui contient les données du composant. |

