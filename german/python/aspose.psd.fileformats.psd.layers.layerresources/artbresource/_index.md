---
title: "ArtBResource Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---

**Summary:** The Artboard info data for [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ArtBResource

**Inheritance:** BaseArtboardInfoResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ArtBResource()](#ArtBResource__1) | Initialisiert eine neue Instanz der ArtBResource‑Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| artboard_background_type | int | r/w | Liest oder setzt den [ArtBResource.artboard_background_type](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt den [ArtBResource.color](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt die Elemente von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | <inheritdoc /> |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: ArtBResource() {#ArtBResource__1}


```
 ArtBResource() 
```

Initialisiert eine neue Instanz der ArtBResource‑Klasse.

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

