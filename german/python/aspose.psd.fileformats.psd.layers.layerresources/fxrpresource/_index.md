---
title: "FxrpResource Klasse"
type: docs
weight: 320
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Initialisiert eine neue Instanz der [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) Klasse. |
| [FxrpResource(data)](#FxrpResource_data_2) | Initialisiert eine neue Instanz der [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) Klasse.<br/>            Mit benutzerdefiniertem oder unbekanntem Wert |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Initialisiert eine neue Instanz der [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) Klasse. |
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
| x | double | r/w | Liest oder setzt das x des Referenzpunkts |
| y | double | r/w | Liest oder setzt das y des Referenzpunkts |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert in den angegebenen Stream-Container. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Initialisiert eine neue Instanz der [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) Klasse.

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Initialisiert eine neue Instanz der [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) Klasse.<br/>            Mit benutzerdefiniertem oder unbekanntem Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Ressourcendaten. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Initialisiert eine neue Instanz der [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double | Die x-Koordinate des Referenzpunkts |
| y | double | Die y-Koordinate des Referenzpunkts |

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

