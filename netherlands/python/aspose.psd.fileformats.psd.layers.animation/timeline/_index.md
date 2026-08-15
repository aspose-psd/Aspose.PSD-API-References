---
title: "Timeline Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Timeline()](#Timeline__1) | Initialiseert een nieuwe instantie van de Timeline klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Haalt de actieve frame-index op. |
| af_st | int | r/w | Haalt of stelt de AFSt-waarde in. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Haalt de lijst met frames op. |
| fs_id | int | r/w | Haalt of stelt de FsID-waarde in. |
| loopes_count | ushort | r/w | Haalt of stelt het aantal lussen in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Slaat de PsdImage- en Timeline-gegevens op naar de opgegeven bestandslocatie in het opgegeven formaat volgens de opslagopties. |
| [save(output_stream, options)](#save_output_stream_options_2) | Slaat de PsdImage- en Timeline-gegevens op naar de opgegeven stream in het opgegeven formaat volgens de opslagopties. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Schakelt het actieve frame naar het doelwit. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Initialiseert een nieuwe instantie van de Timeline klasse

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Slaat de PsdImage- en Timeline-gegevens op naar de opgegeven bestandslocatie in het opgegeven formaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Slaat de PsdImage- en Timeline-gegevens op naar de opgegeven stream in het opgegeven formaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | De uitvoerstroom. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Schakelt het actieve frame naar het doelwit.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_active_frame_index | int | De doel‑frame‑index. |

