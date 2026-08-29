---
title: "Timeline Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Timeline()](#Timeline__1) | Timeline sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Aktif çerçeve indeksini alır. |
| af_st | int | r/w | AFSt değerini alır veya ayarlar. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Çerçevelerin listesini alır. |
| fs_id | int | r/w | FsID değerini alır veya ayarlar. |
| loopes_count | ushort | r/w | Döngü sayısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen dosya konumuna belirtilen formatta kaydeder. |
| [save(output_stream, options)](#save_output_stream_options_2) | PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen akışa belirtilen formatta kaydeder. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Aktif çerçeveyi hedefe değiştirir. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Timeline sınıfının yeni bir örneğini başlatır.

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen dosya konumuna belirtilen formatta kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

PsdImage ve Timeline verilerini, kaydetme seçeneklerine göre belirtilen akışa belirtilen formatta kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Çıktı akışı. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Aktif çerçeveyi hedefe değiştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_active_frame_index | int | Hedef çerçeve indeksi. |

