---
title: "LclrResource Klasse"
type: docs
weight: 470
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | Initialisiert eine neue Instanz der [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) Klasse. |
| [LclrResource(color)](#LclrResource_color_2) | Initialisiert eine neue Instanz der [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) Klasse. |
| [LclrResource(data)](#LclrResource_data_3) | Initialisiert eine neue Instanz der [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Liest oder setzt die Farbe des Layers. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

Initialisiert eine neue Instanz der [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) Klasse.

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

Initialisiert eine neue Instanz der [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | Die Farbe. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

Initialisiert eine neue Instanz der [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Ressourcendaten. |

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

