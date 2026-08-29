---
title: "ImageLoadersRegistry"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt het register van afbeeldingsladers voor."
type: docs
weight: 59
url: /nl/java/com.aspose.psd/imageloadersregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageLoadersRegistry
```

Stelt het register van afbeeldingsladers voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageLoadersRegistry()](#ImageLoadersRegistry--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createFirstSupportedLoader(InputStream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-java.io.InputStream-com.aspose.psd.LoadOptions-) | Maakt de eerst gevonden loader die geschikt is voor de opgegeven stream en eventueel de loadOptions. |
| [createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-) | Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven stream en eventueel de loadOptions. |
| [getFirstSupportedDescriptorByFileFormat(long fileFormat)](#getFirstSupportedDescriptorByFileFormat-long-) | Haalt het eerst ondersteunde bestandsformaat op op basis van de type‑naam. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Haalt de eerste ondersteunde descriptor op op basis van de type‑naam. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Haalt de geregistreerde descriptors op. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Haalt de geregistreerde afbeeldingslaadformaten op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageLoaderDescriptor imageLoaderDescriptor)](#register-com.aspose.psd.IImageLoaderDescriptor-) | Registreert de opgegeven afbeeldingsloader‑descriptor. |
| [registerLoader(IImageLoaderDescriptor loaderDescriptor)](#registerLoader-com.aspose.psd.IImageLoaderDescriptor-) | Registreert de loader. |
| [toString()](#toString--) |  |
| [unregisterLoader(IImageLoaderDescriptor loaderDescriptor)](#unregisterLoader-com.aspose.psd.IImageLoaderDescriptor-) | Deregistreert de loader. |
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


Maakt de eerst gevonden loader die geschikt is voor de opgegeven stream en eventueel de loadOptions.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

--------------------

De eerste loader zal eigenlijk de laatst geregistreerde zijn. |

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - The loader which supports the specified  stream  and  loadOptions  or null if no such loader is found.
### createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#createFirstSupportedLoader-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoader createFirstSupportedLoader_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
### getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor(InputStream stream, LoadOptions loadOptions)
```


Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven stream en eventueel de loadOptions.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream. |
|  | loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

--------------------

De eerste loader‑descriptor zal feitelijk de laatst geregistreerde zijn. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The loader descriptor which supports the specified  stream  and  loadOptions  or null if no such descriptor is found.
### getFirstSupportedDescriptorByFileFormat(long fileFormat) {#getFirstSupportedDescriptorByFileFormat-long-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByFileFormat(long fileFormat)
```


Haalt het eerst ondersteunde bestandsformaat op op basis van de type‑naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | long | Het ondersteunde descriptor‑bestandsformaat. |

--------------------

De eerste loader‑descriptor zal feitelijk de laatst geregistreerde zijn. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Haalt de eerste ondersteunde descriptor op op basis van de type‑naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | descriptorTypeName | java.lang.String | De naam van het descriptor type. |

--------------------

De eerste loader‑descriptor zal feitelijk de laatst geregistreerde zijn. |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) - The first found loader descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static IImageLoaderDescriptor getFirstSupportedDescriptor_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageLoaderDescriptor[] getRegisteredDescriptors()
```


Haalt de geregistreerde descriptors op.

Waarde: De geregistreerde descriptors.

**Returns:**
com.aspose.psd.IImageLoaderDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Haalt de geregistreerde afbeeldingslaadformaten op.

Waarde: De geregistreerde afbeeldingslaadformaten.

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


Registreert de opgegeven afbeeldingsloader‑descriptor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageLoaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | De afbeeldingsloader‑descriptor. |

### registerLoader(IImageLoaderDescriptor loaderDescriptor) {#registerLoader-com.aspose.psd.IImageLoaderDescriptor-}
```
public static void registerLoader(IImageLoaderDescriptor loaderDescriptor)
```


Registreert de loader.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | De loader‑descriptor om te registreren. |

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


Deregistreert de loader.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loaderDescriptor | [IImageLoaderDescriptor](../../com.aspose.psd/iimageloaderdescriptor) | De loader‑descriptor om te deregistreren. |

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

