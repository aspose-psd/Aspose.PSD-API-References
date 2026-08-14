---
title: "Timeline-Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Timeline()](#Timeline__1) | Initialisiert eine neue Instanz der Timeline-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Liest den aktiven Frame-Index. |
| af_st | int | r/w | Liest oder setzt den AFSt-Wert. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Liest die Liste der Frames. |
| fs_id | int | r/w | Liest oder setzt den FsID-Wert. |
| loopes_count | ushort | r/w | Liest oder setzt die Anzahl der Wiederholungen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Speichert die Daten von PsdImage und Timeline an dem angegebenen Dateispeicherort im angegebenen Format gemäß den Speicheroptionen. |
| [save(output_stream, options)](#save_output_stream_options_2) | Speichert die Daten von PsdImage und Timeline in den angegebenen Stream im angegebenen Format gemäß den Speicheroptionen. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Wechselt das aktive Bild zum Ziel. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Initialisiert eine neue Instanz der Timeline-Klasse

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Speichert die Daten von PsdImage und Timeline an dem angegebenen Dateispeicherort im angegebenen Format gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Speichert die Daten von PsdImage und Timeline in den angegebenen Stream im angegebenen Format gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Der Ausgabestream. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Wechselt das aktive Bild zum Ziel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_active_frame_index | int | Der Zielbild-Index. |

