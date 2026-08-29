---
title: "ImageExportersRegistry"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل سجل مصدري الصور."
type: docs
weight: 57
url: /ar/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

يمثل سجل مصدري الصور.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | ينشئ أول مُصدِّر يتم العثور عليه المناسب لخيارات الحفظ المحددة والصورة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | يحصل على أول وصف مدعوم يتم العثور عليه المناسب لخيارات الحفظ المحددة والصورة. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | يحصل على أوصاف المُصدِّرين المسجَّلة. |
| [getRegisteredFormats()](#getRegisteredFormats--) | يحصل على صيغ التصدير المسجَّلة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | يسجِّل وصف مُصدِّر الصورة المحدد. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | يسجِّل المُصدِّر. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | يلغي تسجيل المُصدِّر. |
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


ينشئ أول مُصدِّر يتم العثور عليه المناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة المراد تصديرها. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الحفظ لاستخدامها في التصدير. |

--------------------

المُصدِّر الأول سيكون في الواقع الأخير المسجَّل. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على أول وصف مدعوم يتم العثور عليه المناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة المراد تصديرها. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |

--------------------

وصف المُصدِّر الأول سيكون في الواقع الأخير المسجَّل. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


يحصل على أوصاف المُصدِّرين المسجَّلة.

القيمة: أوصاف المُصدِّرين المسجَّلة.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


يحصل على صيغ التصدير المسجَّلة.

القيمة: صيغ التصدير المسجَّلة.

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


يسجِّل وصف مُصدِّر الصورة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | وصف مُصدِّر الصورة. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


يسجِّل المُصدِّر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | وصف المُصدِّر لتسجيله. |

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


يلغي تسجيل المُصدِّر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | وصف المُصدِّر لإلغاء تسجيله. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

