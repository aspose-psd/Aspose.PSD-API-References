---
title: "ImageCreatorsRegistry"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar registret för bildskapare."
type: docs
weight: 56
url: /sv/java/com.aspose.psd/imagecreatorsregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Representerar registret för bildskapare.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImageCreatorsRegistry()](#ImageCreatorsRegistry--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-) | Skapar den första hittade skaparen som är lämplig för den angivna. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-) | Hämtar den första hittade stödjade beskrivaren som är lämplig för den angivna. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Hämtar de registrerade beskrivningarna. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Hämtar de registrerade bildskapande formaten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageCreatorDescriptor imageCreatorDescriptor)](#register-com.aspose.psd.IImageCreatorDescriptor-) | Registrerar den angivna bildskaparebeskrivaren. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.psd.IImageCreatorDescriptor-) | Registrerar skaparen. |
| [toString()](#toString--) |  |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-) | Avregistrerar skaparen. |
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


Skapar den första hittade skaparen som är lämplig för den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |

--------------------

Den första skaparen kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar den första hittade stödjade beskrivaren som är lämplig för den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |

--------------------

Den första skaparbetsbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Hämtar de registrerade beskrivningarna.

Värde: De registrerade deskriptörerna.

**Returns:**
com.aspose.psd.IImageCreatorDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Hämtar de registrerade bildskapande formaten.

Värde: De registrerade bildskapande formaten.

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


Registrerar den angivna bildskaparebeskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageCreatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Bildskaparbetsbeskrivaren. |

### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registrerar skaparen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Skaparbetsbeskrivaren att registrera. |

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


Avregistrerar skaparen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | Skaparbetsbeskrivaren. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

