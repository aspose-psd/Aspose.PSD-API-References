---
title: "ImageExportersRegistry"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili registri pengekspor gambar."
type: docs
weight: 57
url: /id/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Mewakili registri pengekspor gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Membuat exporter pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Mendapatkan deskriptor yang didukung pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Mendapatkan deskriptor exporter yang terdaftar. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Mendapatkan format ekspor yang terdaftar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Mendaftarkan deskriptor exporter gambar yang ditentukan. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Mendaftarkan exporter. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Membatalkan pendaftaran exporter. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageExportersRegistry() {#ImageExportersRegistry--}
```
public ImageExportersRegistry()
```


### createFirstSupportedExporter(Image image, ImageOptionsBase options) {#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporter createFirstSupportedExporter(Image image, ImageOptionsBase options)
```


Membuat exporter pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan diekspor. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan yang akan digunakan untuk ekspor. |

--------------------

Exporter pertama sebenarnya akan menjadi yang terakhir terdaftar. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFirstSupportedDescriptor(Image image, ImageOptionsBase options) {#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public static IImageExporterDescriptor getFirstSupportedDescriptor(Image image, ImageOptionsBase options)
```


Mendapatkan deskriptor yang didukung pertama yang ditemukan yang cocok untuk opsi penyimpanan dan gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan diekspor. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |

--------------------

Deskriptor exporter pertama sebenarnya akan menjadi yang terakhir terdaftar. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Mendapatkan deskriptor exporter yang terdaftar.

Nilai: Deskriptor exporter yang terdaftar.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Mendapatkan format ekspor yang terdaftar.

Nilai: Format ekspor yang terdaftar.

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### register(IImageExporterDescriptor imageExporterDescriptor) {#register-com.aspose.psd.IImageExporterDescriptor-}
```
public static void register(IImageExporterDescriptor imageExporterDescriptor)
```


Mendaftarkan deskriptor exporter gambar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Deskriptor exporter gambar. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Mendaftarkan exporter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Deskriptor exporter untuk didaftarkan. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterExporter(IImageExporterDescriptor exporterDescriptor) {#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void unregisterExporter(IImageExporterDescriptor exporterDescriptor)
```


Membatalkan pendaftaran exporter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Deskriptor exporter untuk dibatalkan pendaftarannya. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

