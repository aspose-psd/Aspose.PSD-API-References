---
title: "BlwhResource Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Initialisiert eine neue Instanz der Klasse BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| black_and_white_preset_file_name | string | r/w | Liest oder setzt den Dateinamen der Schwarzweiß-Voreinstellung. |
| Blauwerte | int | r/w | Liest oder setzt den Blauwert. |
| bw_preset_kind | int | r/w | Liest oder setzt den Wert der Schwarzweiß-Voreinstellungsart. |
| Cyanwerte | int | r/w | Liest oder setzt den Cyanwert. |
| Grünwerte | int | r/w | Liest oder setzt den Grünwert. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| magentas | int | r/w | Liest oder setzt den Wert von magentas. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| reds | int | r/w | Liest oder setzt den Wert von reds. |
| signature | int | r | Liefert die Signatur. |
| tint_color | int | r/w | Liest oder setzt den ARGB-Wert der Tönungsfarbe. |
| use_tint | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird. |
| yellows | int | r/w | Liest oder setzt den Wert von yellows. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Initialisiert eine neue Instanz der Klasse BlwhResource

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

