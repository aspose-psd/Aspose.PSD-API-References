---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Deskriptor pemuat gambar yang menentukan properti pemuat."
type: docs
weight: 124
url: /id/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Deskriptor pemuat gambar yang menentukan properti pemuat. Deskriptor pemuat digunakan untuk mengatasi kebutuhan menyimpan setiap instance pemuat gambar dalam memori dan masalah multithreading.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Menentukan apakah pemuat gambar dapat membaca gambar baru dari aliran yang ditentukan dan secara opsional menggunakan  loadOptions . |
| [createInstance()](#createInstance--) | Membuat instance pemuat baru. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Menentukan apakah pemuat gambar dapat membaca gambar baru dari aliran yang ditentukan dan secara opsional menggunakan  loadOptions .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Detail format file yang ditentukan oleh  loadOptions .  loadOptions  mungkin null. |

**Returns:**
boolean -  true  jika pemuat gambar yang dibuat oleh deskriptor ini dapat membaca gambar dari aliran; jika tidak,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Membuat instance pemuat baru.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
