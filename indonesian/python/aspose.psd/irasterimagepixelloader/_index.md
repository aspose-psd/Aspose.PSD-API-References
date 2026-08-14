---
title: "Kelas IRasterImagePixelLoader"
type: docs
weight: 2010
url: /id/python-net/aspose.psd/irasterimagepixelloader/
---

**Summary:** The raster image pixel loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImagePixelLoader

**Inheritance:** IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| data_mentah_tersedia | bool | r | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah didukung. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Mendapatkan pengaturan data mentah saat ini. Catatan: saat menggunakan pengaturan ini, data dimuat tanpa konversi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [load_partial_pixels(rectangle, partial_pixel_loader)](#load_partial_pixels_rectangle_partial_pixel_loader_1) | Memuat piksel secara parsial (per blok). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Memuat data mentah. |


### Method: load_partial_pixels(rectangle, partial_pixel_loader) {#load_partial_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_pixels(rectangle, partial_pixel_loader) 
```

Memuat piksel secara parsial (per blok).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |
| partial_pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Pemuat piksel parsial. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2}


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

