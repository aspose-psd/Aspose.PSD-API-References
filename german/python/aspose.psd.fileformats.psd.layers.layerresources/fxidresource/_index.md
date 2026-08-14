---
title: "FXidResource Klasse"
type: docs
weight: 290
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---

**Summary:** The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FXidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [FXidResource(key, version, filter_effect_masks)](#FXidResource_key_version_filter_effect_masks_1) | Initialisiert eine neue Instanz der [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| F_EID_TYPE_TOOL_KEY [static] | int | r | Der Typwerkzeug‑Info‑Schlüssel FEid. |
| F_XID_TYPE_TOOL_KEY [static] | int | r | Der Typwerkzeug‑Info‑Schlüssel FXid. |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | r | Ruft die Filtereffektmasken ab. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| version | int | r | Liest die Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: FXidResource(key, version, filter_effect_masks) {#FXidResource_key_version_filter_effect_masks_1}


```
 FXidResource(key, version, filter_effect_masks) 
```

Initialisiert eine neue Instanz der [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüssel | int | Der Ressourcenschlüssel. |
| version | int | Die Version. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | Die Filtereffektmasken. |

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

