---
title: "Timeline-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Timeline()](#Timeline__1) | Initierar en ny instans av Timeline-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Hämtar det aktiva ramindexet. |
| af_st | int | r/w | Hämtar eller anger AFSt‑värdet. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Hämtar listan över ramar. |
| fs_id | int | r/w | Hämtar eller anger FsID‑värdet. |
| loopes_count | ushort | r/w | Hämtar eller anger antalet slingor. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Sparar PsdImage‑s och Timeline‑data till den angivna filsökvägen i det angivna formatet enligt sparalternativ. |
| [save(output_stream, options)](#save_output_stream_options_2) | Sparar PsdImage‑s och Timeline‑data till den angivna strömmen i det angivna formatet enligt sparalternativ. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Byter den aktiva ramen till den önskade. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Initierar en ny instans av Timeline-klassen

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Sparar PsdImage‑s och Timeline‑data till den angivna filsökvägen i det angivna formatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Sparar PsdImage‑s och Timeline‑data till den angivna strömmen i det angivna formatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Utdata‑strömmen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Byter den aktiva ramen till den önskade.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_active_frame_index | int | Målramsindexet. |

