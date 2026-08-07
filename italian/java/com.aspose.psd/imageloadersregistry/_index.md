---
title: "ImageLoadersRegistry"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il registro dei caricatori di immagini."
type: docs
weight: 59
url: /it/java/com.aspose.psd/imageloadersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Rappresenta il registro dei caricatori di immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageLoadersRegistry()](#ImageLoadersRegistry--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-) | Crea il primo loader trovato adatto al flusso specificato e, opzionalmente, alle loadOptions. |
| [createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-) | Ottiene il primo descrittore supportato trovato adatto al flusso specificato e, opzionalmente, alle loadOptions. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Ottiene il primo formato file supportato per nome del tipo. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Ottiene il primo descrittore supportato per nome tipo. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Ottiene i descrittori registrati. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Ottiene i formati di caricamento immagine registrati. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.psd.IImageLoaderDescriptor-) | Registra il descrittore del loader immagine specificato. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.psd.IImageLoaderDescriptor-) | Registra il loader. |
| [toString()](#toString--) |  |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-) | Deregistra il loader. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageLoadersRegistry() {#ImageLoadersRegistry--}
```
public ImageLoadersRegistry()
```


### createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)
```


Crea il primo loader trovato adatto al flusso specificato e, opzionalmente, alle loadOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

--------------------

Il primo loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - The loader which supports the specified  stream  and  loadOptions  or null if no such loader is found.
### createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader)
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
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Ottiene il primo descrittore supportato trovato adatto al flusso specificato e, opzionalmente, alle loadOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Le opzioni di caricamento. |

--------------------

Il primo descrittore del loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The loader descriptor which supports the specified  stream  and  loadOptions  or null if no such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Ottiene il primo formato file supportato per nome del tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | long | Il formato file del descrittore supportato. |

--------------------

Il primo descrittore del loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Ottiene il primo descrittore supportato per nome tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Il nome del tipo di descrittore. |

--------------------

Il primo descrittore del loader sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Ottiene i descrittori registrati.

Valore: I descrittori registrati.

**Returns:**
com.aspose.psd.IImageLoaderDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Ottiene i formati di caricamento immagine registrati.

Valore: I formati di caricamento immagine registrati.

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




### register(IImageLoaderDescriptor imageLoaderDescriptor) {#register-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void register(IImageLoaderDescriptor imageLoaderDescriptor)
```


Registra il descrittore del loader immagine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Il descrittore del loader immagine. |

### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registra il loader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Il descrittore del loader da registrare. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterLoader(IImageLoaderDescriptor loaderDescriptor) {#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void unregisterLoader(IImageLoaderDescriptor loaderDescriptor)
```


Deregistra il loader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Il descrittore del loader da deregistrare. |

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

