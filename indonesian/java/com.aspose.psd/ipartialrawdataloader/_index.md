---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pemuat data parsial."
type: docs
weight: 133
url: /id/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Pemuat data parsial.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Memproses data yang dimuat. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Memproses data yang dimuat. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Memproses data yang dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang data. |
| data | byte[] | Data mentah. |
| start | [Point](../../com.aspose.psd/point) | Titik data awal. Jika tidak sama dengan (kiri, atas) yang berarti bahwa tidak berupa persegi panjang penuh yang kita miliki. |
| end | [Point](../../com.aspose.psd/point) | Titik data akhir. Jika tidak sama dengan (kanan, bawah) yang berarti bahwa tidak berupa persegi panjang penuh yang kita miliki. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Memproses data yang dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang data. |
| data | byte[] | Data mentah. |
| start | [Point](../../com.aspose.psd/point) | Titik data awal. Jika tidak sama dengan (kiri, atas) yang berarti bahwa tidak berupa persegi panjang penuh yang kita miliki. |
| end | [Point](../../com.aspose.psd/point) | Titik data akhir. Jika tidak sama dengan (kanan, bawah) yang berarti bahwa tidak berupa persegi panjang penuh yang kita miliki. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

