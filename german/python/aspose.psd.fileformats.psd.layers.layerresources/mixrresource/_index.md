---
title: "MixrResource Klasse"
type: docs
weight: 680
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Initialisiert eine neue Instanz der [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) Klasse.<br/>            Die PSD-Formatspezifikation enthält die folgende Beschreibung:<br/>            2 Version ( = 1)<br/>            2 Monochrom<br/>            20 RGB- oder CMYK-Farbe plus Konstante für die Mixer‑Einstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante. |
| [MixrResource(data)](#MixrResource_data_2) | Initialisiert eine neue Instanz der [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) Klasse.<br/>            Die PSD-Formatspezifikation enthält die folgende Beschreibung:<br/>            2 Version ( = 1)<br/>            2 Monochrom<br/>            20 RGB- oder CMYK-Farbe plus Konstante für die Mixer‑Einstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| monochrome | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) monochrom ist. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| version | short | r/w | Liest oder setzt die Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Liest die Rohdaten der Kanalinformation |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Speichert die Ressource im angegebenen Stream-Container. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Setzt die Kanalinformation. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Initialisiert eine neue Instanz der [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) Klasse.<br/>            Die PSD-Formatspezifikation enthält die folgende Beschreibung:<br/>            2 Version ( = 1)<br/>            2 Monochrom<br/>            20 RGB- oder CMYK-Farbe plus Konstante für die Mixer‑Einstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Initialisiert eine neue Instanz der [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) Klasse.<br/>            Die PSD-Formatspezifikation enthält die folgende Beschreibung:<br/>            2 Version ( = 1)<br/>            2 Monochrom<br/>            20 RGB- oder CMYK-Farbe plus Konstante für die Mixer‑Einstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Daten der Ressource. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Liest die Rohdaten der Kanalinformation

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Roh‑Byte‑Array der Kanalinformation. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Setzt die Kanalinformation.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| channel_index | int | Index des Kanals. |
| Wert | byte | Der Wert. |

