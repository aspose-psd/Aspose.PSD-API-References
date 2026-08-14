---
title: "Lr16Resource Klasse"
type: docs
weight: 610
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/
---

**Summary:** The lr16 resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lr16Resource

**Inheritance:** LrXxResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Lr16Resource()](#Lr16Resource__1) | Initialisiert eine neue Instanz der Lr16Resource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | r/w | Liest oder setzt die Ebenen. |
| Länge | int | r | Liest die Ressourcenlänge für die PSD-Header-Version des Bildes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert den Ebenendatensatz. |


### Constructor: Lr16Resource() {#Lr16Resource__1}


```
 Lr16Resource() 
```

Initialisiert eine neue Instanz der Lr16Resource Klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert den Ebenendatensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

