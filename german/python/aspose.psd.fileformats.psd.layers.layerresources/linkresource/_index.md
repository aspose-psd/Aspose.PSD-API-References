---
title: "LinkResource Klasse"
type: docs
weight: 540
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---

**Summary:** Defines the LinkResource class that contains information about linked or embedded files in the PSD format image.<br/>            The link resource may contain several [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instances which can be accessed by indexers in any derived class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
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

