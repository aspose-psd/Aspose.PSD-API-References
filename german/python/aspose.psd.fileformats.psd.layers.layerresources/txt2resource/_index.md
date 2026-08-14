---
title: "Klasse Txt2Resource"
type: docs
weight: 970
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Initialisiert eine neue Instanz der Klasse Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| data | byte | r/w | Liest oder setzt die Daten. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Fügt den Textdatensatz zu Resource hinzu und gibt die ID des Textdatensatzes zurück. |
| [get_text_data()](#get_text_data__2) | Liest den Textdatensatz aus den Ressourcendaten. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Speichert den angegebenen Stream-Container. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Initialisiert eine neue Instanz der Klasse Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Fügt den Textdatensatz zu Resource hinzu und gibt die ID des Textdatensatzes zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | string | Der Aufzeichnungstext. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die Grenzen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Gibt die ID des Textdatensatzes für die Ressource zurück |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Liest den Textdatensatz aus den Ressourcendaten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Array von Textdatensätzen |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Speichert den angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

