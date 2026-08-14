---
title: "TypeToolInfo6Resource Klasse"
type: docs
weight: 990
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Initialisiert eine neue Instanz der [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| bottom | int | r/w | Liest oder setzt die untere Position. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt die Klassen‑ID. |
| class_name | string | r/w | Liest oder setzt den Klassennamen. |
| descriptor_version | int | r/w | Liest oder setzt die Deskriptors-Version. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt die Elemente. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| left | int | r/w | Liest oder setzt die linke Position. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| rechts | int | r/w | Liest oder setzt die rechte Position. |
| signature | int | r | Liefert die Signatur. |
| text_version | short | r/w | Liest oder setzt die Textversion. |
| oben | int | r/w | Liest oder setzt die obere Position. |
| transform_matrix | double | r/w | Liest oder setzt die Transformationsmatrix. |
| version | short | r/w | Liest oder setzt die Version des Typwerkzeugs. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Liest oder setzt die Klassen‑ID. |
| warp_class_name | string | r/w | Liest oder setzt den Namen der Warp-Klasse. |
| warp_descriptor_version | int | r/w | Liest oder setzt die Warp-Deskriptors-Version. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt die Warp-Elemente. |
| warp_version | short | r/w | Liest oder setzt die Warp-Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Initialisiert eine neue Instanz der [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Die Klassen-ID. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Die Warp-Klassen-ID. |

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

