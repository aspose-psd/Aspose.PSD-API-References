---
title: "CurvResource Klasse"
type: docs
weight: 190
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Initialisiert eine neue Instanz der [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) Klasse. |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Initialisiert eine neue Instanz der [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| is_data_stored_discretely | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz Daten diskret speichert. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Liest den aktiven Manager. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Liest die Kanaldaten. |
| [get_curve_manager()](#get_curve_manager__3) | Liest den Kurven-Manager. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Initialisiert eine neue Instanz der [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | byte | Die Bytes. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Initialisiert eine neue Instanz der [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| max_channel_count | int | Die maximale Kanalanzahl. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Liest den aktiven Manager.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Aktiver Manager |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Liest die Kanaldaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Kanaldaten |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Liest den Kurven-Manager.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) or [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

