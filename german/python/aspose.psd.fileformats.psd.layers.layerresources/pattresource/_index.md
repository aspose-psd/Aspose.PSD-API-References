---
title: "PattResource Klasse"
type: docs
weight: 770
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PattResource()](#PattResource__1) | Initialisiert eine neue Instanz der Klasse [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Initialisiert eine neue Instanz der Klasse [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der 'Patt'-Typ-Tool-Info-Schlüssel für 8-Bit. |
| TYPE_TOOL_KEY2 [statisch] | int | r | Der 'Pat2'-Typ-Tool-Info-Schlüssel für 16-Bit. |
| TYPE_TOOL_KEY3 [statisch] | int | r | Der 'Pat3'-Typ-Tool-Info-Schlüssel für 32-Bit. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Liest oder setzt die Musterdaten; |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressourcenblockdaten. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Initialisiert eine neue Instanz der Klasse [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Initialisiert eine neue Instanz der Klasse [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | int | Der Ressourcentyp-Schlüssel. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Die Musterdaten. |

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

