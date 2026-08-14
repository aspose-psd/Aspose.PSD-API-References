---
title: "Classe RawColor"
type: docs
weight: 20
url: /it/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Inizializza una nuova istanza della classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/). |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Inizializza una nuova istanza della classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) dal formato dati pixel utilizzando modalità colore predefinite |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Modalità da seguire per il colore. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Ottiene i componenti del colore. Ogni componente è un canale separato, e se utilizzi uno schema di colore non popolare<br/>            è meglio lavorare con ciascun canale separatamente. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Ottiene il colore come int nel caso sia possibile ottenerlo. |
| [get_as_long()](#get_as_long__2) | Ottiene il colore come long nel caso sia possibile ottenerlo. |
| [get_bit_depth()](#get_bit_depth__3) | Ottiene la profondità di bit del colore grezzo. <br/>            Ad esempio, per un colore ARGB con 8 bit per canale/componente è 32<br/>            La profondità di bit di un colore ARGB completo con 16 bit per canale/componente è 64.<br/>            La profondità di bit è accumulata dalla somma delle profondità di bit dei canali. <br/>            È possibile se i diversi canali hanno profondità di bit differenti. |
| [get_color_mode_name()](#get_color_mode_name__4) | Ottiene il nome della modalità colore. Il nome della modalità colore è accumulato dai nomi dei canali/componenti. |
| [set_as_int(value)](#set_as_int_value_5) | Imposta i dati a tutti i canali dal argomento int se è possibile. |
| [set_as_long(value)](#set_as_long_value_6) | Imposta i dati a tutti i canali dal argomento int se è possibile. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Inizializza una nuova istanza della classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | I componenti colore personalizzati. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Inizializza una nuova istanza della classe [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) dal formato dati pixel utilizzando modalità colore predefinite

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Il formato dati pixel. |
| color_mode | short | Modalità da seguire per il colore. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Ottiene il colore come int nel caso sia possibile ottenerlo.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Dati dei canali memorizzati in Int. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Ottiene il colore come long nel caso sia possibile ottenerlo.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| long | Dati dei canali memorizzati in Int. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Ottiene la profondità di bit del colore grezzo. <br/>            Ad esempio, per un colore ARGB con 8 bit per canale/componente è 32<br/>            La profondità di bit di un colore ARGB completo con 16 bit per canale/componente è 64.<br/>            La profondità di bit è accumulata dalla somma delle profondità di bit dei canali. <br/>            È possibile se i diversi canali hanno profondità di bit differenti.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La somma di tutte le profondità di bit dei canali. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Ottiene il nome della modalità colore. Il nome della modalità colore è accumulato dai nomi dei canali/componenti.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Stringa con il nome della modalità colore. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Imposta i dati a tutti i canali dal argomento int se è possibile.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | int | Il valore int che contiene i dati del componente. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Imposta i dati a tutti i canali dal argomento int se è possibile.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | long | Il valore int che contiene i dati del componente. |

