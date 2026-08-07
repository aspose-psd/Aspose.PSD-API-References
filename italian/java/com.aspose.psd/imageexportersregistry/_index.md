---
title: "ImageExportersRegistry"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il registro degli esportatori di immagini."
type: docs
weight: 57
url: /it/java/com.aspose.psd/imageexportersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageExportersRegistry
```

Rappresenta il registro degli esportatori di immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageExportersRegistry()](#ImageExportersRegistry--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createFirstSupportedExporter(Image image, ImageOptionsBase options)](#createFirstSupportedExporter-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(Image image, ImageOptionsBase options)](#getFirstSupportedDescriptor-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Ottiene il primo descrittore supportato trovato adatto alle opzioni di salvataggio e all'immagine specificate. |
| [getRegisteredExporterDescriptors()](#getRegisteredExporterDescriptors--) | Ottiene i descrittori degli esportatori registrati. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Ottiene i formati di esportazione registrati. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageExporterDescriptor imageExporterDescriptor)](#register-com.aspose.psd.IImageExporterDescriptor-) | Registra il descrittore dell'esportatore di immagini specificato. |
| [registerExporter(IImageExporterDescriptor exporterDescriptor)](#registerExporter-com.aspose.psd.IImageExporterDescriptor-) | Registra l'esportatore. |
| [toString()](#toString--) |  |
| [unregisterExporter(IImageExporterDescriptor exporterDescriptor)](#unregisterExporter-com.aspose.psd.IImageExporterDescriptor-) | Annulla la registrazione dell'esportatore. |
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


Crea il primo esportatore trovato adatto alle opzioni di salvataggio e all'immagine specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da esportare. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni di salvataggio da utilizzare per l'esportazione. |

--------------------

Il primo esportatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - The exporter which supports the specified image and save options or null if no such exporter is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene il primo descrittore supportato trovato adatto alle opzioni di salvataggio e all'immagine specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da esportare. |
|  | options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni. |

--------------------

Il primo descrittore dell'esportatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) - The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.
### getRegisteredExporterDescriptors() {#getRegisteredExporterDescriptors--}
```
public static IImageExporterDescriptor[] getRegisteredExporterDescriptors()
```


Ottiene i descrittori degli esportatori registrati.

Valore: I descrittori degli esportatori registrati.

**Returns:**
com.aspose.psd.IImageExporterDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Ottiene i formati di esportazione registrati.

Valore: I formati di esportazione registrati.

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


Registra il descrittore dell'esportatore di immagini specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageExporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Il descrittore dell'esportatore di immagini. |

### registerExporter(IImageExporterDescriptor exporterDescriptor) {#registerExporter-com.aspose.psd.IImageExporterDescriptor-}
```
public static void registerExporter(IImageExporterDescriptor exporterDescriptor)
```


Registra l'esportatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Il descrittore dell'esportatore da registrare. |

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


Annulla la registrazione dell'esportatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| exporterDescriptor | [IImageExporterDescriptor](../../com.aspose.psd/iimageexporterdescriptor) | Il descrittore dell'esportatore da annullare la registrazione. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

