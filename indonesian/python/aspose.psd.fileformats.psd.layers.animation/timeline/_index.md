---
title: "Kelas Timeline"
type: docs
weight: 40
url: /id/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Timeline()](#Timeline__1) | Menginisialisasi instansi baru dari kelas Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Mendapatkan indeks frame aktif. |
| af_st | int | r/w | Mendapatkan atau mengatur nilai AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Mendapatkan daftar frame. |
| fs_id | int | r/w | Mendapatkan atau mengatur nilai FsID. |
| loopes_count | ushort | r/w | Mendapatkan atau mengatur jumlah loop. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Menyimpan data PsdImage dan Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan. |
| [save(output_stream, options)](#save_output_stream_options_2) | Menyimpan data PsdImage dan Timeline ke aliran yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Mengalihkan frame aktif ke yang ditargetkan. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Menginisialisasi instansi baru dari kelas Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Menyimpan data PsdImage dan Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Menyimpan data PsdImage dan Timeline ke aliran yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Aliran keluaran. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Mengalihkan frame aktif ke yang ditargetkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_active_frame_index | int | Indeks frame target. |

