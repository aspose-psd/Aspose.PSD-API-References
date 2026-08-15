---
title: "RawColor Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Initialiseert een nieuw exemplaar van de [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) klasse. |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Initialiseert een nieuw exemplaar van de [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) klasse vanuit pixelgegevensformaat met behulp van vooraf gedefinieerde kleurmodi. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Modus die de kleur moet volgen. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Haalt de componenten van de kleur op. Elke component is een apart kanaal, en als u een niet populair<br/>            kleurenschema gebruikt, is het beter om met elk kanaal afzonderlijk te werken. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Haalt de kleur op als int voor het geval dit mogelijk is. |
| [get_as_long()](#get_as_long__2) | Haalt de kleur op als long voor het geval dit mogelijk is. |
| [get_bit_depth()](#get_bit_depth__3) | Haalt de bitdiepte van Raw Color op. <br/>            Bijvoorbeeld voor een ARGB-kleur met 8 bits per kanaal/component is dit 32<br/>            Bitdiepte van een volledige ARGB-kleur met 16 bits per kanaal/component is 64.<br/>            Bitdiepte wordt opgeteld uit de som van de bitdieptes van de kanalen. <br/>            Dit is mogelijk als verschillende kanalen verschillende bitdieptes hebben. |
| [get_color_mode_name()](#get_color_mode_name__4) | Haalt de naam van de kleurmodus op. Kleurmodusnaam wordt opgebouwd uit de namen van kanalen/componenten. |
| [set_as_int(value)](#set_as_int_value_5) | Stelt gegevens in voor alle kanalen vanuit een int-argument indien mogelijk. |
| [set_as_long(value)](#set_as_long_value_6) | Stelt gegevens in voor alle kanalen vanuit een int-argument indien mogelijk. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Initialiseert een nieuw exemplaar van de [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | De aangepaste kleurcomponenten. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Initialiseert een nieuw exemplaar van de [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) klasse vanuit pixelgegevensformaat met behulp van vooraf gedefinieerde kleurmodi.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Het pixelgegevensformaat. |
| color_mode | short | Modus die de kleur moet volgen. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Haalt de kleur op als int voor het geval dit mogelijk is.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Kanaalgegevens opgeslagen in Int. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Haalt de kleur op als long voor het geval dit mogelijk is.

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | Kanaalgegevens opgeslagen in Int. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Haalt de bitdiepte van Raw Color op. <br/>            Bijvoorbeeld voor een ARGB-kleur met 8 bits per kanaal/component is dit 32<br/>            Bitdiepte van een volledige ARGB-kleur met 16 bits per kanaal/component is 64.<br/>            Bitdiepte wordt opgeteld uit de som van de bitdieptes van de kanalen. <br/>            Dit is mogelijk als verschillende kanalen verschillende bitdieptes hebben.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De som van alle kanaalbitdieptes. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Haalt de naam van de kleurmodus op. Kleurmodusnaam wordt opgebouwd uit de namen van kanalen/componenten.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | String met de naam van de kleurmodus. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Stelt gegevens in voor alle kanalen vanuit een int-argument indien mogelijk.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | int | De int-waarde die componentgegevens bevat. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Stelt gegevens in voor alle kanalen vanuit een int-argument indien mogelijk.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | long | De int-waarde die componentgegevens bevat. |

