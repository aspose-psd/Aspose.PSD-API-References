---
title: ImageCreatorsRegistry
second_title: Aspose.PSD for Java API Reference
description: Represents the image creators registry.
type: docs
weight: 56
url: /java/com.aspose.psd/imagecreatorsregistry/
---

**Inheritance:**
java.lang.Object
```
public final class ImageCreatorsRegistry
```

Represents the image creators registry.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageCreatorsRegistry()](#ImageCreatorsRegistry--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createFirstSupportedCreator(ImageOptionsBase imageOptions)](#createFirstSupportedCreator-com.aspose.psd.ImageOptionsBase-) | Creates the first found creator suitable for the specified. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(ImageOptionsBase imageOptions)](#getFirstSupportedDescriptor-com.aspose.psd.ImageOptionsBase-) | Gets the fist found supported descriptor suitable for the specified. |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Gets the registered descriptors. |
| [getRegisteredFormats()](#getRegisteredFormats--) | Gets the registered image creation formats. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [register(IImageCreatorDescriptor imageCreatorDescriptor)](#register-com.aspose.psd.IImageCreatorDescriptor-) | Registers the specified image creator descriptor. |
| [registerCreator(IImageCreatorDescriptor creatorDescriptor)](#registerCreator-com.aspose.psd.IImageCreatorDescriptor-) | Registers the creator. |
| [toString()](#toString--) |  |
| [unregisterCreator(IImageCreatorDescriptor creatorDescriptor)](#unregisterCreator-com.aspose.psd.IImageCreatorDescriptor-) | Unregisters the creator. |
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


Creates the first found creator suitable for the specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The image options.

--------------------

The first creator will be actually the last registered. |

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - The creator which supports the specified or null if no such creator is found.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the fist found supported descriptor suitable for the specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The image options.

--------------------

The first creator descriptor will be actually the last registered. |

**Returns:**
[IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) - The creator descriptor which supports the specified or null if no such descriptor is found.
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IImageCreatorDescriptor[] getRegisteredDescriptors()
```


Gets the registered descriptors.

Value: The registered descriptors.

**Returns:**
com.aspose.psd.IImageCreatorDescriptor[]
### getRegisteredFormats() {#getRegisteredFormats--}
```
public static long getRegisteredFormats()
```


Gets the registered image creation formats.

Value: The registered image creation formats.

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


Registers the specified image creator descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageCreatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | The image creator descriptor. |

### registerCreator(IImageCreatorDescriptor creatorDescriptor) {#registerCreator-com.aspose.psd.IImageCreatorDescriptor-}
```
public static void registerCreator(IImageCreatorDescriptor creatorDescriptor)
```


Registers the creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | The creator descriptor to register. |

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


Unregisters the creator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| creatorDescriptor | [IImageCreatorDescriptor](../../com.aspose.psd/iimagecreatordescriptor) | The creator descriptor. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

