---
title: "ImageExportersRegistry"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt das Register der Bildexporter dar."
type: docs
weight: 57
url: /de/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Stellt das Register der Bildexporter dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für die angegebenen Speicheroptionen und das Bild geeignet ist. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Ruft die registrierten Exporter-Deskriptoren ab. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Ruft die registrierten Exportformate ab. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Registriert den angegebenen Bild-Exporter-Deskriptor. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Registriert den Exporter. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Deregistriert den Exporter. |
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


Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das zu exportierende Bild. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die zu verwendenden Speicheroptionen für den Export. |

--------------------

Der erste Exporter wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für die angegebenen Speicheroptionen und das Bild geeignet ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das zu exportierende Bild. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionen. |

--------------------

Der erste Exporter-Deskriptor wird tatsächlich der zuletzt registrierte sein. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Ruft die registrierten Exporter-Deskriptoren ab.

Wert: Die registrierten Exporter-Deskriptoren.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Ruft die registrierten Exportformate ab.

Wert: Die registrierten Exportformate.

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


Registriert den angegebenen Bild-Exporter-Deskriptor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Der Bild-Exporter-Deskriptor. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registriert den Exporter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Der zu registrierende Exporter-Deskriptor. |

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


Deregistriert den Exporter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Der Exporter-Deskriptor zum Abmelden. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

