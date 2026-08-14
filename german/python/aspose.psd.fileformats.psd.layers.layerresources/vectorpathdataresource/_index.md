---
title: "VectorPathDataResource Klasse"
type: docs
weight: 1080
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---

**Summary:** Class VectorPathDataResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VectorPathDataResource

**Inheritance:** IVectorPathData, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| is_disabled | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist. |
| is_inverted | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist. |
| is_not_linked | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Liest oder setzt die Pfaddatensätze. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| version | int | r/w | Liest oder setzt die Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


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

