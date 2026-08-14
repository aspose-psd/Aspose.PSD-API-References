---
title: "IopaResource Klasse"
type: docs
weight: 440
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Initialisiert eine neue Instanz der Klasse [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
| [IopaResource(data)](#IopaResource_data_2) | Initialisiert eine neue Instanz der Klasse [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| fill_opacity | byte | r/w | Liest oder setzt die Füll‑Deckkraft. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Initialisiert eine neue Instanz der Klasse [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Initialisiert eine neue Instanz der Klasse [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die rohen Byte-Daten. |

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

