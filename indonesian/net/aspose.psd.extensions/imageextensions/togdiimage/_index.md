---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode ImageExtensions. Mengonversi Image ke Image"
type: docs
weight: 10
url: /id/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Mengonversi Image menjadi Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | Image | Image untuk dikonversi. |

### Nilai Kembalian

Image yang telah dikonversi.

## Catatan

Peringatan, gambar GDI mungkin memiliki batas bawah lebih rendah daripada *image* yang ada. Untuk mendapatkan semua bagian gambar gunakan metode ekstensi yang lebih aman ToGdiImageFull.

### Lihat Juga

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


