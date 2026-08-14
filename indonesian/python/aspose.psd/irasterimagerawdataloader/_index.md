---
title: "Kelas IRasterImageRawDataLoader"
type: docs
weight: 2020
url: /id/python-net/aspose.psd/irasterimagerawdataloader/
---

**Summary:** The raster image raw data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| data_mentah_tersedia | bool | r | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah didukung. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Mendapatkan pengaturan data mentah saat ini. Catatan: saat menggunakan pengaturan ini, data dimuat tanpa konversi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1) | Memuat data mentah. |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_1}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Memuat data mentah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat data mentah dari. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Pengaturan data mentah yang akan digunakan untuk data yang dimuat. Catatan: jika data tidak dalam format yang ditentukan maka konversi data akan dilakukan. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Pemuat data mentah. |

