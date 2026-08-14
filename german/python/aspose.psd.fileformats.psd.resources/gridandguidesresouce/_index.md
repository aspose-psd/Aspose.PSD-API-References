---
title: "GridAndGuidesResouce Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Initialisiert eine neue Instanz der GridAndGuidesResouce Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Die Ressourcensignatur von ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Die reguläre Photoshop‑Ressourcensignatur. |
| data_size | int | r | Gibt die Größe der Ressourcendaten in Bytes zurück. |
| grid_cycle_x | int | r/w | Liest oder setzt den horizontalen Gitterzyklus. Der Standardwert ist 576. |
| grid_cycle_y | int | r/w | Liest oder setzt den vertikalen Gitterzyklus. Der Standardwert ist 576. |
| guide_count | int | r | Liest die Anzahl der Leitlinien‑Ressourcenblöcke. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Liest oder setzt die Leitlinien. |
| header_version | int | r/w | Liest oder setzt die Header-Version. Dieser Wert sollte immer 1 sein. |
| id | short | r/w | Liest oder setzt die eindeutige Kennung für die Ressource. |
| minimal_version | int | r | Ruft die minimal erforderliche PSD-Version ab. |
| name | string | r/w | Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, damit die Größe gerade ist (ein Nullname besteht aus zwei Bytes mit 0). |
| signature | int | r | Liefert die Ressourcensignatur. Sollte immer '8BIM' sein. |
| Größe | int | r | Liefert die Blockgröße der Ressource in Bytes einschließlich ihrer Daten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Ressourcenblock in den angegebenen Stream. |
| validate_values() | Validiert die Ressourcenwerte. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Initialisiert eine neue Instanz der GridAndGuidesResouce Klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Ressourcenblock in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream, in den der Ressourcenblock gespeichert wird. |

