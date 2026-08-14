---
title: "BlncResource Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Initialisiert eine neue Instanz der [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| highlights_cyan_red_balance | short | r/w | Liest oder setzt die Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Liest oder setzt die Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Liest oder legt das Highlights Yellow Blue Balance fest. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| midtones_cyan_red_balance | short | r/w | Liest oder legt das Midtones Cyan Red Balance fest. |
| midtones_magenta_green_balance | short | r/w | Liest oder legt das Midtones Magenta Green Balance fest. |
| midtones_yellow_blue_balance | short | r/w | Liest oder legt das Midtones Yellow Blue Balance fest. |
| preserve_luminosity | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) die Leuchtkraft beibehält. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| shadows_cyan_red_balance | short | r/w | Liest oder legt das Shadows Cyan Red Balance fest. |
| shadows_magenta_green_balance | short | r/w | Liest oder legt das Shadows Magenta Green Balance fest. |
| shadows_yellow_blue_balance | short | r/w | Liest oder setzt das Shadows Yellow Blue Balance. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Initialisiert eine neue Instanz der [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) Klasse.

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

