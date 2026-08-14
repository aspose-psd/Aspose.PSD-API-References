---
title: "LspfResource Klasse"
type: docs
weight: 640
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Initialisiert eine neue Instanz der [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) Klasse. |
| [LspfResource(data)](#LspfResource_data_2) | Initialisiert eine neue Instanz der [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) Klasse.<br/>            Mit benutzerdefiniertem oder unbekanntem Wert |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Initialisiert eine neue Instanz der [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Tool-Info-Schlüssel 1819504742 |
| is_composite_protected | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz zusammengesetzt geschützt ist. |
| is_position_protected | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz positionsgeschützt ist. |
| is_transparency_protected | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz transparent geschützt ist. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Liest oder setzt den Typ der Sperre. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Initialisiert eine neue Instanz der [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) Klasse.

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Initialisiert eine neue Instanz der [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) Klasse.<br/>            Mit benutzerdefiniertem oder unbekanntem Wert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Ressourcendaten. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Initialisiert eine neue Instanz der [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_transparency_protected | bool | wenn auf <c>true</c> gesetzt, [ist transparent geschützt]. |
| is_composite_protected | bool | wenn auf <c>true</c> gesetzt, [ist zusammengesetzt geschützt]. |
| is_position_protected | bool | wenn auf <c>true</c> gesetzt, [ist positionsgeschützt]. |

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

