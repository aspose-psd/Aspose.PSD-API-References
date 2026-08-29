---
title: "ImageExportersRegistry"
second_title: "Java için Aspose.PSD API Referansı"
description: "Görüntü dışa aktarıcıların kayıt defterini temsil eder."
type: docs
weight: 57
url: /tr/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Görüntü dışa aktarıcıların kayıt defterini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Kayıtlı dışa aktarıcı tanımlayıcılarını alır. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Kayıtlı dışa aktarma biçimlerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Dışa aktarıcıyı kaydeder. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Dışa aktarıcı kaydını siler. |
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


Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan dışa aktarıcıyı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Dışa aktarılacak görüntü. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Dışa aktarma için kullanılacak kaydetme seçenekleri. |

--------------------

İlk dışa aktarıcı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Belirtilen kaydetme seçenekleri ve görüntü için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Dışa aktarılacak görüntü. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçenekler. |

--------------------

İlk dışa aktarıcı tanımlayıcı aslında son kaydedilen olacaktır. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Kayıtlı dışa aktarıcı tanımlayıcılarını alır.

Değer: Kayıtlı dışa aktarıcı tanımlayıcıları.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Kayıtlı dışa aktarma biçimlerini alır.

Değer: Kayıtlı dışa aktarma biçimleri.

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


Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Görüntü dışa aktarıcı tanımlayıcısı. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Dışa aktarıcıyı kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Kaydedilecek dışa aktarıcı tanımlayıcısı. |

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


Dışa aktarıcı kaydını siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Kaydı silinecek dışa aktarıcı tanımlayıcısı. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

