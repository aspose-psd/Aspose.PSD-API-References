---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pemuat data mentah raster image."
type: docs
weight: 137
url: /id/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Pemuat data mentah raster image.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Mendapatkan pengaturan data mentah saat ini. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah didukung. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Memuat data mentah. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Mendapatkan pengaturan data mentah saat ini. Catatan: ketika menggunakan pengaturan ini data dimuat tanpa konversi.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah didukung.

**Returns:**
boolean -  true  jika pemuatan data mentah didukung; jika tidak,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Memuat data mentah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat data mentah dari. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Pengaturan data mentah yang digunakan untuk data yang dimuat. Catatan: jika data tidak dalam format yang ditentukan maka konversi data akan dilakukan. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Pemuat data mentah. |

