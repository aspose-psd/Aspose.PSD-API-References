---
title: LayerResourcesRegistry
second_title: Aspose.PSD for Java API Reference
description: Represents the layer resources registry.
type: docs
weight: 25
url: /java/com.aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Inheritance:**
java.lang.Object
```
public final class LayerResourcesRegistry
```

Represents the layer resources registry.
## Constructors

| Constructor | Description |
| --- | --- |
| [LayerResourcesRegistry()](#LayerResourcesRegistry--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream, int psdVersion)](#getFirstSupportedDescriptor-java.io.InputStream-int-) | Gets the first supported opener descriptor. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Gets the first supported descriptor by its type name. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Gets the registered descriptors. |
| [hashCode()](#hashCode--) |  |
| [loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-) | Loads [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) using first found opener suitable for the specified  stream . |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerDefaultPsdOptions_internalized()](#registerDefaultPsdOptions-internalized--) | Registers the default PSD options. |
| [registerOpener(ILayerResourceLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Registers the opener. |
| [registerPsdLoadOptions_internalized(PsdLoadOptions load)](#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-) | Registers the PSD load options. |
| [toString()](#toString--) |  |
| [unregisterOpener(ILayerResourceLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-) | Unregisters the opener. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerResourcesRegistry() {#LayerResourcesRegistry--}
```
public LayerResourcesRegistry()
```


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
### getFirstSupportedDescriptor(InputStream stream, int psdVersion) {#getFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Gets the first supported opener descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| psdVersion | int | The PSD version.

--------------------

The first loader will be actually the last registered. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static ILayerResourceLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Gets the first supported descriptor by its type name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| descriptorTypeName | java.lang.String | The descriptor type name.

--------------------

The first opener descriptor will be actually the last registered. |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static ILayerResourceLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static ILayerResourceLoader[] getRegisteredDescriptors()
```


Gets the registered descriptors.

Value: The registered descriptors.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor(InputStream stream, int psdVersion)
```


Loads [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) using first found opener suitable for the specified  stream .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| psdVersion | int | The PSD version.

--------------------

The first opener will be actually the last registered. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-int-}
```
public static LayerResource loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream, int psdVersion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| psdVersion | int |  |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerDefaultPsdOptions_internalized() {#registerDefaultPsdOptions-internalized--}
```
public static void registerDefaultPsdOptions_internalized()
```


Registers the default PSD options.

### registerOpener(ILayerResourceLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void registerOpener(ILayerResourceLoader openerDescriptor)
```


Registers the opener.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | The opener descriptor to register. |

### registerPsdLoadOptions_internalized(PsdLoadOptions load) {#registerPsdLoadOptions-internalized-com.aspose.psd.imageloadoptions.PsdLoadOptions-}
```
public static void registerPsdLoadOptions_internalized(PsdLoadOptions load)
```


Registers the PSD load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| load | [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) | The load. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(ILayerResourceLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.ILayerResourceLoader-}
```
public static void unregisterOpener(ILayerResourceLoader openerDescriptor)
```


Unregisters the opener.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| openerDescriptor | [ILayerResourceLoader](../../com.aspose.psd.fileformats.psd.layers/ilayerresourceloader) | The opener descriptor to unregister. |

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

