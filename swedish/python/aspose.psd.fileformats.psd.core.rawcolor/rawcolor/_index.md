---
title: "RawColor-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Initierar en ny instans av klassen [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/). |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Initierar en ny instans av klassen [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) från pixeldatatyp med fördefinierade färglägen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Läge för färgen att följa. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Hämtar färgens komponenter. Varje komponent är en separat kanal, och om du använder ett mindre vanligt<br/>            färgschema är det bättre att arbeta med varje kanal separat. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Hämtar färgen som int om det är möjligt att få den. |
| [get_as_long()](#get_as_long__2) | Hämtar färgen som long om det är möjligt att få den. |
| [get_bit_depth()](#get_bit_depth__3) | Hämtar bitdjupet för Raw Color. <br/>            Till exempel för ARGB-färg med 8 bitar per kanal/komponent är det 32<br/>            Bitdjupet för full ARGB-färg med 16 bitar per kanal/komponent är 64.<br/>            Bitdjupet ackumuleras från summan av kanalernas bitdjup. <br/>            Detta är möjligt om olika kanaler har olika bitdjup. |
| [get_color_mode_name()](#get_color_mode_name__4) | Hämtar namnet på färgläget. Färglägesnamnet ackumuleras från kanalernas/komponenternas namn. |
| [set_as_int(value)](#set_as_int_value_5) | Ställer in data till alla kanaler från ett int-argument om det är möjligt |
| [set_as_long(value)](#set_as_long_value_6) | Ställer in data till alla kanaler från ett int-argument om det är möjligt |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Initierar en ny instans av klassen [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | De anpassade färgkomponenterna. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Initierar en ny instans av klassen [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) från pixeldatatyp med fördefinierade färglägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Pixeldataformatet. |
| color_mode | short | Läge för färgen att följa. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Hämtar färgen som int om det är möjligt att få den.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Kanaldata lagrad i Int |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Hämtar färgen som long om det är möjligt att få den.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | Kanaldata lagrad i Int |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Hämtar bitdjupet för Raw Color. <br/>            Till exempel för ARGB-färg med 8 bitar per kanal/komponent är det 32<br/>            Bitdjupet för full ARGB-färg med 16 bitar per kanal/komponent är 64.<br/>            Bitdjupet ackumuleras från summan av kanalernas bitdjup. <br/>            Detta är möjligt om olika kanaler har olika bitdjup.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Summan av alla kanalers bitdjup |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Hämtar namnet på färgläget. Färglägesnamnet ackumuleras från kanalernas/komponenternas namn.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Sträng med färglägets namn |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Ställer in data till alla kanaler från ett int-argument om det är möjligt

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | int | int‑värdet som innehåller komponentdata |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Ställer in data till alla kanaler från ett int-argument om det är möjligt

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | long | int‑värdet som innehåller komponentdata |

