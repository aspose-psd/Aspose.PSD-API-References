---
title: "CgEdResource Klasse"
type: docs
weight: 130
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Initialisiert eine neue Instanz der CgEdResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| auto | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) automatisch ist. |
| Helligkeit | int | r/w | Liest oder setzt die Helligkeit. |
| Kontrast | int | r/w | Liest oder setzt den Kontrast. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| lab_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [lab color] verwendet wird. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| mean_value_for_brightness_and_contrast | int | r/w | Liest oder setzt den Mittelwert für Helligkeit und Kontrast. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
| use_legacy | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [use legacy] verwendet wird. |
| version | int | r/w | Liest oder setzt die Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Initialisiert eine neue Instanz der CgEdResource Klasse

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

