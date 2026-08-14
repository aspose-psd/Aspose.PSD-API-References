---
title: "LnkeResource Klasse"
type: docs
weight: 590
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/
---

**Summary:** Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image.<br/>            The link resource may contain several [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instances which can be accessed by indexer.<br/>            This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnkeResource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LnkeResource()](#LnkeResource__1) | Initialisiert eine neue Instanz der [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) Klasse. |
| [LnkeResource(data_sources)](#LnkeResource_data_sources_2) | Initialisiert eine neue Instanz der [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| data_source_count | int | r | Liest die Anzahl der Link-Datenquellen, die über den Indexer zugänglich sind. |
| is_empty | bool | r | Liest einen Wert, der angibt, ob diese Link-Ressourceninstanz leer ist. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die globale Link-Ressourcenlänge der PSD in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressourcenblockdaten. |


### Constructor: LnkeResource() {#LnkeResource__1}


```
 LnkeResource() 
```

Initialisiert eine neue Instanz der [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) Klasse.

### Constructor: LnkeResource(data_sources) {#LnkeResource_data_sources_2}


```
 LnkeResource(data_sources) 
```

Initialisiert eine neue Instanz der [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_sources | [LinkDataSource[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) | Die Datenquellen. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert die Ressourcenblockdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

