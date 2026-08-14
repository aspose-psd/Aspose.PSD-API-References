---
title: "PattResourceData Klasse"
type: docs
weight: 780
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Initialisiert eine neue Instanz der PattResourceData Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| height | short | r | Ermittelt die Höhe. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Liefert den Bildmodus. |
| Länge | int | r | Liefert die Länge des Musters. |
| name | string | r/w | Liefert oder setzt den Namen. |
| pattern_data | int | r | Liefert die Musterdaten. |
| pattern_id | string | r/w | Liest oder setzt die Musterkennung. |
| version | int | r | Liest die Version. |
| width | short | r | Ermittelt die Breite. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Speichert die Musterdaten. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Setzt das Muster. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Initialisiert eine neue Instanz der PattResourceData Klasse

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Speichert die Musterdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Setzt das Muster.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | int | Die Pixel. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die Grenzen. |

