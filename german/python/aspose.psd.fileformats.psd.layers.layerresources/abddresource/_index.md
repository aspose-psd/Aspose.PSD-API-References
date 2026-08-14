---
title: "AbddResource Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/
---

**Summary:** The Artboard info data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.AbddResource

**Inheritance:** BaseArtboardInfoResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [AbddResource()](#AbddResource__1) | Initialisiert eine neue Instanz der Klasse AbddResource |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt die Elemente von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | <inheritdoc /> |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: AbddResource() {#AbddResource__1}


```
 AbddResource() 
```

Initialisiert eine neue Instanz der Klasse AbddResource

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

