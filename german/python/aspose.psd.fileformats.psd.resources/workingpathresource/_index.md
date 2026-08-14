---
title: "WorkingPathResource Klasse"
type: docs
weight: 320
url: /de/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Initialisiert eine neue Instanz der [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Die Ressourcensignatur von ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Die reguläre Photoshop‑Ressourcensignatur. |
| data_size | int | r | Gibt die Größe der Ressourcendaten in Bytes zurück. |
| id | short | r/w | Liest oder setzt die eindeutige Kennung für die Ressource. |
| is_disabled | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz deaktiviert ist. |
| is_inverted | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz invertiert ist. |
| is_not_linked | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz nicht verknüpft ist. |
| minimal_version | int | r | Liefert die minimal erforderliche PSD-Version. |
| name | string | r/w | Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, damit die Größe gerade ist (ein Nullname besteht aus zwei Bytes mit 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Liest oder setzt die Pfaddatensätze. |
| signature | int | r | Liefert die Ressourcensignatur. Sollte immer '8BIM' sein. |
| Größe | int | r | Liefert die Blockgröße der Ressource in Bytes einschließlich ihrer Daten. |
| version | int | r/w | Liest oder setzt die Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Ressourcenblock in den angegebenen Stream. |
| validate_values() | Validiert die Ressourcenwerte. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Initialisiert eine neue Instanz der [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_bytes | byte | Die Daten des Vektorpfads. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

