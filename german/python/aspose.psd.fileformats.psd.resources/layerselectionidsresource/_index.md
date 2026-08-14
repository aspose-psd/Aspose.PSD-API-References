---
title: "LayerSelectionIdsResource Klasse"
type: docs
weight: 170
url: /de/python-net/aspose.psd.fileformats.psd.resources/layerselectionidsresource/
---

**Summary:** Layer selection ids resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.LayerSelectionIdsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LayerSelectionIdsResource()](#LayerSelectionIdsResource__1) | Initialisiert eine neue Instanz der LayerSelectionIdsResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Die Ressourcensignatur von ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Die reguläre Photoshop‑Ressourcensignatur. |
| Anzahl | short | r/w | Liest oder setzt die Anzahl. |
| data_size | int | r | Gibt die Größe der Ressourcendaten in Bytes zurück. |
| id | short | r/w | Liest oder setzt die eindeutige Kennung für die Ressource. |
| layer_ids | int | r/w | Liest oder setzt die Layer-IDs. |
| minimal_version | int | r | Liefert die minimal erforderliche PSD-Version. |
| name | string | r/w | Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, damit die Größe gerade ist (ein Nullname besteht aus zwei Bytes mit 0). |
| signature | int | r | Liefert die Ressourcensignatur. Sollte immer '8BIM' sein. |
| Größe | int | r | Liefert die Blockgröße der Ressource in Bytes einschließlich ihrer Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Ressourcenblock in den angegebenen Stream. |
| validate_values() | Validiert die Ressourcenwerte. |


### Constructor: LayerSelectionIdsResource() {#LayerSelectionIdsResource__1}


```
 LayerSelectionIdsResource() 
```

Initialisiert eine neue Instanz der LayerSelectionIdsResource Klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

