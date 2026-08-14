---
title: "RawColor Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Initialisiert eine neue Instanz der [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) Klasse. |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Initialisiert eine neue Instanz der [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) Klasse aus dem Pixeldatenformat unter Verwendung vordefinierter Farbmodi. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Modus, dem die Farbe folgen soll. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Liest die Farbkomponenten. Jede Komponente ist ein separater Kanal, und wenn Sie ein nicht gängiges<br/>            Farbschema verwenden, ist es besser, mit jedem Kanal separat zu arbeiten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Liest die Farbe als int, falls sie abgerufen werden kann. |
| [get_as_long()](#get_as_long__2) | Liest die Farbe als long, falls sie abgerufen werden kann. |
| [get_bit_depth()](#get_bit_depth__3) | Liest die Bit-Tiefe von Raw Color. <br/>            Zum Beispiel hat eine ARGB-Farbe mit 8 Bit pro Kanal/Komponente 32<br/>            Bit-Tiefe einer vollen ARGB-Farbe mit 16 Bit pro Kanal/Komponente ist 64.<br/>            Die Bit-Tiefe wird aus der Summe der Bit-Tiefen der Kanäle akkumuliert. <br/>            Das ist möglich, wenn verschiedene Kanäle unterschiedliche Bit-Tiefen haben. |
| [get_color_mode_name()](#get_color_mode_name__4) | Liest den Namen des Farbmodus. Der Farbmodusname wird aus den Namen der Kanäle/Komponenten zusammengesetzt. |
| [set_as_int(value)](#set_as_int_value_5) | Setzt Daten für alle Kanäle aus einem int-Argument, falls möglich. |
| [set_as_long(value)](#set_as_long_value_6) | Setzt Daten für alle Kanäle aus einem int-Argument, falls möglich. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Initialisiert eine neue Instanz der [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Die benutzerdefinierten Farbkomponenten. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Initialisiert eine neue Instanz der [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) Klasse aus dem Pixeldatenformat unter Verwendung vordefinierter Farbmodi.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Das Pixeldatenformat. |
| color_mode | short | Modus, dem die Farbe folgen soll. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Liest die Farbe als int, falls sie abgerufen werden kann.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Kanaldaten gespeichert in Int |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Liest die Farbe als long, falls sie abgerufen werden kann.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long | Kanaldaten gespeichert in Int |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Liest die Bit-Tiefe von Raw Color. <br/>            Zum Beispiel hat eine ARGB-Farbe mit 8 Bit pro Kanal/Komponente 32<br/>            Bit-Tiefe einer vollen ARGB-Farbe mit 16 Bit pro Kanal/Komponente ist 64.<br/>            Die Bit-Tiefe wird aus der Summe der Bit-Tiefen der Kanäle akkumuliert. <br/>            Das ist möglich, wenn verschiedene Kanäle unterschiedliche Bit-Tiefen haben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Summe aller Kanal-Bit-Tiefen |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Liest den Namen des Farbmodus. Der Farbmodusname wird aus den Namen der Kanäle/Komponenten zusammengesetzt.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Zeichenkette mit dem Namen des Farbmodus |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Setzt Daten für alle Kanäle aus einem int-Argument, falls möglich.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | int | Der int-Wert, der Komponentendaten enthält |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Setzt Daten für alle Kanäle aus einem int-Argument, falls möglich.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | long | Der int-Wert, der Komponentendaten enthält |

