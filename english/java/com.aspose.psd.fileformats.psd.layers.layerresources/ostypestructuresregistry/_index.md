---
title: OSTypeStructuresRegistry
second_title: Aspose.PSD for Java API Reference
description: Represents the  resources registry.
type: docs
weight: 62
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Inheritance:**
java.lang.Object
```
public final class OSTypeStructuresRegistry
```

Represents the [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resources registry.
## Constructors

| Constructor | Description |
| --- | --- |
| [OSTypeStructuresRegistry()](#OSTypeStructuresRegistry--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstSupportedDescriptor(InputStream stream)](#getFirstSupportedDescriptor-java.io.InputStream-) | Gets the first supported opener descriptor. |
| [getFirstSupportedDescriptorByTypeName(String descriptorTypeName)](#getFirstSupportedDescriptorByTypeName-java.lang.String-) | Gets the first supported descriptor by its type name. |
| [getFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [getRegisteredDescriptors()](#getRegisteredDescriptors--) | Gets the registered descriptors. |
| [hashCode()](#hashCode--) |  |
| [isOSTypeStructreExist_internalized(int structureKey)](#isOSTypeStructreExist-internalized-int-) | Detects if any OSTypeStructure's descendant present with provided structureKey. |
| [loadDescriptorData_internalized(StreamContainer streamContainer)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-) | Loads the descriptor data structures from stream container. |
| [loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)](#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---) | Loads the descriptor data structures with class name and class id from stream container. |
| [loadResourceByFirstSupportedDescriptor(InputStream stream)](#loadResourceByFirstSupportedDescriptor-java.io.InputStream-) | Loads [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) using first found opener suitable for the specified  stream . |
| [loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)](#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerOpener(IOSTypeStructureLoader openerDescriptor)](#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Registers the opener. |
| [toString()](#toString--) |  |
| [unregisterOpener(IOSTypeStructureLoader openerDescriptor)](#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-) | Unregisters the opener. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OSTypeStructuresRegistry() {#OSTypeStructuresRegistry--}
```
public OSTypeStructuresRegistry()
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
### getFirstSupportedDescriptor(InputStream stream) {#getFirstSupportedDescriptor-java.io.InputStream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor(InputStream stream)
```


Gets the first supported opener descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream.

--------------------

The first loader will be actually the last registered. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The layer resource loader descriptor or null if no loader descriptor supported for such stream.
### getFirstSupportedDescriptorByTypeName(String descriptorTypeName) {#getFirstSupportedDescriptorByTypeName-java.lang.String-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptorByTypeName(String descriptorTypeName)
```


Gets the first supported descriptor by its type name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| descriptorTypeName | java.lang.String | The descriptor type name.

--------------------

The first opener descriptor will be actually the last registered. |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) - The first found opener descriptor or null if not such descriptor is found.
### getFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#getFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static IOSTypeStructureLoader getFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader)
### getRegisteredDescriptors() {#getRegisteredDescriptors--}
```
public static IOSTypeStructureLoader[] getRegisteredDescriptors()
```


Gets the registered descriptors.

Value: The registered descriptors.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOSTypeStructreExist_internalized(int structureKey) {#isOSTypeStructreExist-internalized-int-}
```
public static boolean isOSTypeStructreExist_internalized(int structureKey)
```


Detects if any OSTypeStructure's descendant present with provided structureKey.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structureKey | int | StructureKey of OSTypeStructure. |

**Returns:**
boolean - 
### loadDescriptorData_internalized(StreamContainer streamContainer) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer)
```


Loads the descriptor data structures from stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream to read of. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - The descriptor data structures.
### loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId) {#loadDescriptorData-internalized-com.aspose.psd.StreamContainer-java.lang.String---com.aspose.psd.fileformats.psd.layers.layerresources.ClassID---}
```
public static OSTypeStructure[] loadDescriptorData_internalized(StreamContainer streamContainer, String[] className, ClassID[] classId)
```


Loads the descriptor data structures with class name and class id from stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream to read of. |
| className | java.lang.String[] | The read class name. |
| classId | [ClassID\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | The read class id. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - The descriptor data structures with class name and class id.
### loadResourceByFirstSupportedDescriptor(InputStream stream) {#loadResourceByFirstSupportedDescriptor-java.io.InputStream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor(InputStream stream)
```


Loads [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) using first found opener suitable for the specified  stream .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream.

--------------------

The first opener will be actually the last registered. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The loaded [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) or null if no opener is found.
### loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream) {#loadResourceByFirstSupportedDescriptor-internalized-com.aspose.ms.System.IO.Stream-}
```
public static OSTypeStructure loadResourceByFirstSupportedDescriptor_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerOpener(IOSTypeStructureLoader openerDescriptor) {#registerOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-}
```
public static void registerOpener(IOSTypeStructureLoader openerDescriptor)
```


Registers the opener.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | The opener descriptor to register. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unregisterOpener(IOSTypeStructureLoader openerDescriptor) {#unregisterOpener-com.aspose.psd.fileformats.psd.layers.layerresources.IOSTypeStructureLoader-}
```
public static void unregisterOpener(IOSTypeStructureLoader openerDescriptor)
```


Unregisters the opener.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| openerDescriptor | [IOSTypeStructureLoader](../../com.aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | The opener descriptor to unregister. |

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

