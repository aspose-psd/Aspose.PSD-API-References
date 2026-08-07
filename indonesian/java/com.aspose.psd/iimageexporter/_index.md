---
title: "IImageExporter"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pengekspor gambar."
type: docs
weight: 121
url: /id/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

Pengekspor gambar. Dapat mengekspor data dari format internal Aspose.Imaging ke format data yang ditentukan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Mengekspor data gambar yang ditentukan ke format data yang ditentukan. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Mengekspor data gambar yang ditentukan ke format data yang ditentukan. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Mengekspor data gambar yang ditentukan ke format data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Data gambar yang akan diekspor. |
| stream | java.io.OutputStream | Aliran untuk mengekspor data ke. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi untuk ekspor gambar |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Mengekspor data gambar yang ditentukan ke format data yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Data gambar yang akan diekspor. |
| stream | java.io.OutputStream | Aliran untuk mengekspor data ke. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi untuk ekspor gambar |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas. |

