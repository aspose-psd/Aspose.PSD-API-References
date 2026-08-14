---
title: "Lnk3Resource Klasse"
type: docs
weight: 580
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---

**Summary:** Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk3Resource

**Inheritance:** Lnk2Resource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Lnk3Resource()](#Lnk3Resource__1) | Initialisiert eine neue Instanz der Klasse [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/). |
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


### Constructor: Lnk3Resource() {#Lnk3Resource__1}


```
 Lnk3Resource() 
```

Initialisiert eine neue Instanz der Klasse [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/).

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

