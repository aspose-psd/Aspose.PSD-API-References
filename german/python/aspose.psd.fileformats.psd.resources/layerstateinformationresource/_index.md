---
title: "LayerStateInformationResource Klasse"
type: docs
weight: 180
url: /de/python-net/aspose.psd.fileformats.psd.resources/layerstateinformationresource/
---

**Summary:** Layer state information resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.LayerStateInformationResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LayerStateInformationResource()](#LayerStateInformationResource__1) | Initialisiert eine neue Instanz der LayerStateInformationResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Die Ressourcensignatur von ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Die reguläre Photoshop‑Ressourcensignatur. |
| data_size | int | r | Gibt die Größe der Ressourcendaten in Bytes zurück. |
| id | short | r/w | Liest oder setzt die eindeutige Kennung für die Ressource. |
| layer_index | short | r/w | Liest oder setzt den Index der Ebene. |
| minimal_version | int | r | Liefert die minimal erforderliche PSD-Version. |
| name | string | r/w | Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, damit die Größe gerade ist (ein Nullname besteht aus zwei Bytes mit 0). |
| signature | int | r | Liefert die Ressourcensignatur. Sollte immer '8BIM' sein. |
| Größe | int | r | Liefert die Blockgröße der Ressource in Bytes einschließlich ihrer Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Ressourcenblock in den angegebenen Stream. |
| validate_values() | Validiert die Ressourcenwerte. |


### Constructor: LayerStateInformationResource() {#LayerStateInformationResource__1}


```
 LayerStateInformationResource() 
```

Initialisiert eine neue Instanz der LayerStateInformationResource Klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

