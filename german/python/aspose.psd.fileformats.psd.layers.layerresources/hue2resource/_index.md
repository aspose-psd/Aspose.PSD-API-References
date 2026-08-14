---
title: "Hue2Resource Klasse"
type: docs
weight: 350
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Initialisiert eine neue Instanz der [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) Klasse. |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Initialisiert eine neue Instanz der [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| colorize | bool | r/w | Liefert oder setzt einen Wert, der angibt, ob dieses [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) koloriert ist. |
| Farbton | short | r/w | Liefert oder setzt den Master-Farbton. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| Helligkeit | short | r/w | Liefert oder setzt die Master-Helligkeit. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Liefert die Bereiche der Farbton/Sättigung-Anpassungsebene.<br/>            Bereiche in PS können ihre Namen ändern, wenn der Bereich geändert wird, daher sollten wir nach Index arbeiten |
| Sättigung | short | r/w | Liefert oder setzt die Master-Sättigung. |
| signature | int | r | Liefert die Signatur. |
| version | short | r | Liefert die Version. Standard ist 2 |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Initialisiert eine neue Instanz der [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) Klasse.

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Initialisiert eine neue Instanz der [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Daten der Ressource. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

