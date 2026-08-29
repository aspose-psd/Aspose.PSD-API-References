---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili deskriptor pengekspor gambar."
type: docs
weight: 122
url: /id/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Mewakili deskriptor pengekspor gambar. Deskriptor pengekspor digunakan untuk mengatasi kebutuhan menampung setiap instance pengekspor dalam memori dan masalah multithreading.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Menentukan apakah pengekspor gambar dapat mengekspor gambar yang ditentukan ke format gambar yang ditentukan oleh opsi penyimpanan. |
| [createInstance()](#createInstance--) | Membuat instance pengekspor baru. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Menentukan apakah pengekspor gambar dapat mengekspor gambar yang ditentukan ke format gambar yang ditentukan oleh opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan diekspor. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Basis opsi. |

**Returns:**
boolean -  true  jika pengekspor yang dibuat oleh deskriptor ini dapat mengekspor gambar yang ditentukan ke format file yang ditentukan; jika tidak,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Membuat instance pengekspor baru.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
