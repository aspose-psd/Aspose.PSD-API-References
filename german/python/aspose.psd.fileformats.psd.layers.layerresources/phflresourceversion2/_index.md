---
title: "PhflResourceVersion2 Klasse"
type: docs
weight: 800
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Initialisiert eine neue Instanz der [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) Klasse. |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Initialisiert eine neue Instanz der [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| color_space | short | r | Liest den Farbraum. |
| component_a | short | r/w | Liest oder setzt die A-Komponente der Farbe |
| component_b | short | r/w | Liest oder setzt die B-Komponente |
| component_l | short | r/w | Liest oder setzt die L-Komponente der Farbe |
| Dichte | int | r/w | Liest oder setzt die Dichte. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| preserve_luminosity | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [preserve luminosity] erhalten wird. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| version | short | r | Liest die Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Liest die Farbe. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Speichert die Ressource im angegebenen Stream-Container. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Setzt die RGB-Farbe. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Initialisiert eine neue Instanz der [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) Klasse.

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Initialisiert eine neue Instanz der [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Daten der Ressource. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Liest die Farbe.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Die RGB-Farbe |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Setzt die RGB-Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Die Farbe. |

