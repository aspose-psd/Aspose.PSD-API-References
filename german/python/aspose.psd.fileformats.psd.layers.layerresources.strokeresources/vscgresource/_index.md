---
title: "VscgResource Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Initialisiert eine neue Instanz der VscgResource-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Liest oder setzt das Array von Struktur-Elementen.<br/>            **Warning:** Die `Items`-Array-Werte müssen mit der `KeyForData`-Eigenschaft übereinstimmen, die den Typ der in den Strukturen innerhalb von `Items` gespeicherten Fill-Einstellungen bestimmt. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| key_for_data | int | r | Liest den ganzzahligen Schlüssel, der definiert, welche Art von Fill-Einstellungen in der Ressource gespeichert ist:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradient - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Pattern - 0x5074466c - PtFlResource.TypeToolKey<br/>            Warning! Der Wert der Eigenschaft KeyForData sollte dem Typ der in Items-Strukturen gespeicherten Fill-Einstellungen entsprechen. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Initialisiert eine neue Instanz der VscgResource-Klasse

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

