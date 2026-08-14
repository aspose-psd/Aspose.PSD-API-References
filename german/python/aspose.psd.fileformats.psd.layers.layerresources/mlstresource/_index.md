---
title: "MlstResource Klasse"
type: docs
weight: 690
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---

**Summary:** The mlst resource.<br/>            This class, among other things, contains information about the position of the layer on the timeline.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MlstResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MlstResource()](#MlstResource__1) | Initialisiert eine neue Instanz der MlstResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| descriptor_version | int | r | Liest oder setzt die Deskriptors-Version. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Liest oder setzt die Strukturen. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert den angegebenen Stream-Container. |


### Constructor: MlstResource() {#MlstResource__1}


```
 MlstResource() 
```

Initialisiert eine neue Instanz der MlstResource Klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert den angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

