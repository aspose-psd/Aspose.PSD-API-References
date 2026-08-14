---
title: "LevlResource Klasse"
type: docs
weight: 490
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Initialisiert eine neue Instanz der [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) Klasse. |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Initialisiert eine neue Instanz der [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) Klasse.<br/>            Unterstützt in GrayScale-, Duotone-, RGB-, CMYK- und Lab-Farbmodi<br/>            2 Bytes - Version (=2)<br/>            29 * 10 Bytes - Sätze von Level-Datensätzen mit 5 kurzen Ganzzahlen<br/>            4 Bytes - Lvls-Header (Beginnt bei Index 292)<br/>            2 Bytes - Version (=3)<br/>            2 Bytes - Anzahl der gesamten Level-Datensätze<br/>            10 * (Gesamtanzahl - 29)<br/>            Das Nullende des Lvls-Resources sollte für vier ebenfalls gefaltet werden |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| version | short | r | Liefert die Version. Standard ist 2 |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Liest den Kanal. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Initialisiert eine neue Instanz der [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) Klasse.

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Initialisiert eine neue Instanz der [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) Klasse.<br/>            Unterstützt in GrayScale-, Duotone-, RGB-, CMYK- und Lab-Farbmodi<br/>            2 Bytes - Version (=2)<br/>            29 * 10 Bytes - Sätze von Level-Datensätzen mit 5 kurzen Ganzzahlen<br/>            4 Bytes - Lvls-Header (Beginnt bei Index 292)<br/>            2 Bytes - Version (=3)<br/>            2 Bytes - Anzahl der gesamten Level-Datensätze<br/>            10 * (Gesamtanzahl - 29)<br/>            Das Nullende des Lvls-Resources sollte für vier ebenfalls gefaltet werden

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | byte | Die Bytes. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Liest den Kanal.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Level-Daten des Kanals |


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

