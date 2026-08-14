---
title: "ClblResource Klasse"
type: docs
weight: 160
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Initialisiert eine neue Instanz der Klasse [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Initialisiert eine neue Instanz der Klasse [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(data)](#ClblResource_data_3) | Initialisiert eine neue Instanz der Klasse [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).<br/>            Mit benutzerdefiniertem oder unbekanntem Wert |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| blend_clipped_elements | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [Blend abgeschnittene Elemente]. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert den angegebenen Stream-Container. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Initialisiert eine neue Instanz der Klasse [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Initialisiert eine neue Instanz der Klasse [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| blend_clipped_elements | bool | wenn auf <c>true</c> gesetzt, [Blend abgeschnittene Elemente]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Initialisiert eine neue Instanz der Klasse [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).<br/>            Mit benutzerdefiniertem oder unbekanntem Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Ressourcendaten. |

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

