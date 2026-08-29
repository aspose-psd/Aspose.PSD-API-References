---
title: "ImageExportersRegistry"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt het register van afbeeldingsexporteurs voor"
type: docs
weight: 57
url: /nl/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Stelt het register van afbeeldingsexporteurs voor
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Maakt de eerst gevonden exporter die geschikt is voor de opgegeven opslagopties en afbeelding. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven opslagopties en afbeelding. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Haalt de geregistreerde exporter-descriptoren op. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Haalt de geregistreerde exportformaten op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Registreert de opgegeven afbeelding-exporter-descriptor. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Registreert de exporter. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Deregistreert de exporter. |
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


Maakt de eerst gevonden exporter die geschikt is voor de opgegeven opslagopties en afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te exporteren. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties om te gebruiken voor export. |

--------------------

De eerste exporter zal eigenlijk de laatst geregistreerde zijn. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven opslagopties en afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | De afbeelding om te exporteren. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

--------------------

De eerste exporter-descriptor zal eigenlijk de laatst geregistreerde zijn. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Haalt de geregistreerde exporter-descriptoren op.

Waarde: De geregistreerde exporter-descriptoren.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Haalt de geregistreerde exportformaten op.

Waarde: De geregistreerde exportformaten.

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


Registreert de opgegeven afbeelding-exporter-descriptor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | De afbeelding-exporter-descriptor. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registreert de exporter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | De exporter-descriptor om te registreren. |

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


Deregistreert de exporter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | De exporter-descriptor om te deregistreren. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

