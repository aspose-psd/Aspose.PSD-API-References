---
title: "LyidResource Klasse"
type: docs
weight: 660
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Initialisiert eine neue Instanz der [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) Klasse.<br/>            Mit benutzerdefiniertem oder unbekanntem Wert |
| [LyidResource(id)](#LyidResource_id_2) | Initialisiert eine neue Instanz der [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) Klasse. |
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
| Wert | int | r | Gibt den Wert zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert in den angegebenen Stream-Container. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Initialisiert eine neue Instanz der [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) Klasse.<br/>            Mit benutzerdefiniertem oder unbekanntem Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | byte | Die Bytes. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Initialisiert eine neue Instanz der [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | int | Der Bezeichner der Ebene. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert in den angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

