---
title: "VersionInfoResource Klasse"
type: docs
weight: 300
url: /de/python-net/aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Summary:** Version Info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.VersionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [VersionInfoResource()](#VersionInfoResource__1) | Initialisiert eine neue Instanz der VersionInfoResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Die Ressourcensignatur von ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Die reguläre Photoshop‑Ressourcensignatur. |
| data_size | int | r | Gibt die Größe der Ressourcendaten in Bytes zurück. |
| file_version | uint | r/w | Liest oder setzt die Dateiversion. |
| has_real_merged_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz echte zusammengeführte Daten hat. |
| id | short | r/w | Liest oder setzt die eindeutige Kennung für die Ressource. |
| minimal_version | int | r | Liefert die minimal erforderliche PSD-Version. |
| name | string | r/w | Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, damit die Größe gerade ist (ein Nullname besteht aus zwei Bytes mit 0). |
| reader_name | string | r/w | Liest oder setzt den Namen des Lesers. |
| signature | int | r | Liefert die Ressourcensignatur. Sollte immer '8BIM' sein. |
| Größe | int | r | Liefert die Blockgröße der Ressource in Bytes einschließlich ihrer Daten. |
| version | uint | r/w | Liest oder setzt die Version. |
| writer_name | string | r/w | Liest oder setzt den Namen des Schreibers. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Ressourcenblock in den angegebenen Stream. |
| validate_values() | Validiert die Ressourcenwerte. |


### Constructor: VersionInfoResource() {#VersionInfoResource__1}


```
 VersionInfoResource() 
```

Initialisiert eine neue Instanz der VersionInfoResource Klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

