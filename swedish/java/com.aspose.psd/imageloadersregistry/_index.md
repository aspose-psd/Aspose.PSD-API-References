---
title: "ImageLoadersRegistry"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar registret för bildladdare."
type: docs
weight: 59
url: /sv/java/com.aspose.psd/imageloadersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Representerar registret för bildladdare.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ImageLoadersRegistry()](#ImageLoadersRegistry--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-) | Skapar den första hittade laddaren som är lämplig för den angivna  strömmen  och eventuellt  loadOptions . |
| [createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-) | Hämtar den första hittade stödjade beskrivaren som är lämplig för den angivna  strömmen  och eventuellt  loadOptions . |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Hämtar det första stödjade filformatet efter dess typnamn. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Hämtar den första stödda beskrivningen efter dess typnamn. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Hämtar de registrerade beskrivningarna. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Hämtar de registrerade bildladdningsformaten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.psd.IImageLoaderDescriptor-) | Registrerar den angivna bildladdarbeskrivaren. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.psd.IImageLoaderDescriptor-) | Registrerar laddaren. |
| [toString()](#toString--) |  |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-) | Avregistrerar laddaren. |
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


Skapar den första hittade laddaren som är lämplig för den angivna  strömmen  och eventuellt  loadOptions .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

--------------------

Den första laddaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - The loader which supports the specified  stream  and  loadOptions  or null if no such loader is found.
### createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Hämtar den första hittade stödjade beskrivaren som är lämplig för den angivna  strömmen  och eventuellt  loadOptions .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

--------------------

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The loader descriptor which supports the specified  stream  and  loadOptions  or null if no such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Hämtar det första stödjade filformatet efter dess typnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | long | Det stödjade filformatet för beskrivaren. |

--------------------

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Hämtar den första stödda beskrivningen efter dess typnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | Deskriptortypens namn. |

--------------------

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Hämtar de registrerade beskrivningarna.

Värde: De registrerade deskriptörerna.

**Returns:**
com.aspose.psd.IImageLoaderDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Hämtar de registrerade bildladdningsformaten.

Värde: De registrerade bildladdningsformaten.

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


Registrerar den angivna bildladdarbeskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Bildladdarbeskrivaren. |

### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registrerar laddaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Laddarbeskrivaren att registrera. |

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


Avregistrerar laddaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | Laddarbeskrivaren att avregistrera. |

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

