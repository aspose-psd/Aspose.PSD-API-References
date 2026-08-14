---
title: "LmskResource Klasse"
type: docs
weight: 560
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | Initialisiert eine neue Instanz der [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| color_component1 | ushort | r/w | Liest die Farbkomponente 1. |
| color_component2 | ushort | r/w | Liest die Farbkomponente 2. |
| color_component3 | ushort | r/w | Liest die Farbkomponente 3. |
| color_component4 | ushort | r/w | Liest die Farbkomponente 4. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | Liest den Farbraum. |
| flag | byte | r | Liest das Flag. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| Deckkraft | short | r/w | Liest die Deckkraft. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

Initialisiert eine neue Instanz der [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) Klasse.

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

