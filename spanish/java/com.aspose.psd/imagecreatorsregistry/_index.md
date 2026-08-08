---
title: "ImageCreatorsRegistry"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el registro de creadores de imágenes."
type: docs
weight: 56
url: /es/java/com.aspose.psd/imagecreatorsregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Representa el registro de creadores de imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageCreatorsRegistry()](#ImageCreatorsRegistry--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-) | Crea el primer creador encontrado adecuado para lo especificado. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-) | Obtiene el primer descriptor compatible encontrado adecuado para lo especificado. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Obtiene los descriptores registrados. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Obtiene los formatos de creación de imágenes registrados. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageCreatorDescriptor imageCreatorDescriptor)](#register-com.aspose.psd.IImageCreatorDescriptor-) | Registra el descriptor de creador de imágenes especificado. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.psd.IImageCreatorDescriptor-) | Registra el creador. |
| [toString()](#toString--) |  |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-) | Desregistra el creador. |
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


Crea el primer creador encontrado adecuado para lo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de imagen. |

--------------------

El primer creador será en realidad el último registrado. |

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene el primer descriptor compatible encontrado adecuado para lo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de imagen. |

--------------------

El primer descriptor de creador será en realidad el último registrado. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Obtiene los descriptores registrados.

Valor: Los descriptores registrados.

**Returns:**
com.aspose.psd.IImageCreatorDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Obtiene los formatos de creación de imágenes registrados.

Valor: Los formatos de creación de imágenes registrados.

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


Registra el descriptor de creador de imágenes especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageCreatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | El descriptor del creador de imágenes. |

### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registra el creador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | El descriptor del creador a registrar. |

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


Desregistra el creador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | El descriptor del creador. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

