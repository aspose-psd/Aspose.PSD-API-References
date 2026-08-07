---
title: "ImageCreatorsRegistry"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il registro dei creatori di immagini."
type: docs
weight: 56
url: /it/java/com.aspose.psd/imagecreatorsregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Rappresenta il registro dei creatori di immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageCreatorsRegistry()](#ImageCreatorsRegistry--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-) | Crea il primo creatore trovato adatto a quello specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-) | Ottiene il primo descrittore supportato trovato adatto a quello specificato. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Ottiene i descrittori registrati. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Ottiene i formati di creazione immagine registrati. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageCreatorDescriptor imageCreatorDescriptor)](#register-com.aspose.psd.IImageCreatorDescriptor-) | Registra il descrittore del creatore di immagini specificato. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.psd.IImageCreatorDescriptor-) | Registra il creatore. |
| [toString()](#toString--) |  |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-) | Deregistra il creatore. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageCreatorsRegistry() {#ImageCreatorsRegistry--}
```
public ImageCreatorsRegistry()
```


### createFirstSupportedCreator(ImageOptionsBase imageOptions) {#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-}
```
public static IImageCreator createFirstSupportedCreator(ImageOptionsBase imageOptions)
```


Crea il primo creatore trovato adatto a quello specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni immagine. |

--------------------

Il primo creatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - The creator which supports the specified or null if no such creator is found.
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
### getFirstSupportedDescriptor(ImageOptionsBase imageOptions) {#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-}
```
public static IImageCreatorDescriptor getFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```


Ottiene il primo descrittore supportato trovato adatto a quello specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Le opzioni immagine. |

--------------------

Il primo descrittore del creatore sarà in realtà l'ultimo registrato. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Ottiene i descrittori registrati.

Valore: I descrittori registrati.

**Returns:**
com.aspose.psd.IImageCreatorDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Ottiene i formati di creazione immagine registrati.

Valore: I formati di creazione immagine registrati.

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




### register(IImageCreatorDescriptor imageCreatorDescriptor) {#register-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void register(IImageCreatorDescriptor imageCreatorDescriptor)
```


Registra il descrittore del creatore di immagini specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageCreatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore di immagini. |

### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registra il creatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore da registrare. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterCreator(IImageCreatorDescriptor creatorDescriptor) {#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void unregisterCreator(IImageCreatorDescriptor creatorDescriptor)
```


Deregistra il creatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore. |

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

