---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Deskriptor pembuat gambar yang menentukan properti pembuat."
type: docs
weight: 119
url: /id/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Deskriptor pembuat gambar yang menentukan properti pembuat. Deskriptor pembuat ini digunakan untuk mengatasi kebutuhan menyimpan setiap instance pembuat gambar dalam memori dan masalah multithreading.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Menentukan apakah pembuat gambar dapat membuat gambar baru menggunakan imageOptions. |
| [createInstance()](#createInstance--) | Membuat instance pembuat baru. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Menentukan apakah pembuat gambar dapat membuat gambar baru menggunakan imageOptions.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi gambar. |

**Returns:**
boolean - true jika pembuat gambar yang dibuat oleh deskriptor ini dapat membuat data gambar menggunakan imageOptions yang ditentukan; sebaliknya, false.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Membuat instance pembuat baru.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
