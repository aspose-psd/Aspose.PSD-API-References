---
title: "ImageExportersRegistry"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente le registre des exportateurs d'images."
type: docs
weight: 57
url: /fr/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Représente le registre des exportateurs d'images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Crée le premier exportateur trouvé adapté aux options d'enregistrement spécifiées et à l'image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement spécifiées et à l'image. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Obtient les descripteurs d'exportateur enregistrés. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtient les formats d'exportation enregistrés. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Enregistre le descripteur d'exportateur d'image spécifié. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Enregistre l'exportateur. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Désenregistre l'exportateur. |
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


Crée le premier exportateur trouvé adapté aux options d'enregistrement spécifiées et à l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à exporter. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement à utiliser pour l'exportation. |

--------------------

Le premier exportateur sera en fait le dernier enregistré. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement spécifiées et à l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à exporter. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

--------------------

Le premier descripteur d'exportateur sera en fait le dernier enregistré. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Obtient les descripteurs d'exportateur enregistrés.

Valeur: les descripteurs d'exportateur enregistrés.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtient les formats d'exportation enregistrés.

Valeur: les formats d'exportation enregistrés.

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


Enregistre le descripteur d'exportateur d'image spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur d'image. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Enregistre l'exportateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur à enregistrer. |

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


Désenregistre l'exportateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur à désenregistrer. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

