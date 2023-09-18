---
title: AliasStructure
second_title: Aspose.PSD for Java API Reference
description: The alias structure.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/aliasstructure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
```
public final class AliasStructure extends OSTypeStructure
```

The alias structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [AliasStructure(ClassID keyName)](#AliasStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Initializes a new instance of the [AliasStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/aliasstructure) class. |
## Fields

| Field | Description |
| --- | --- |
| [StructureKey](#StructureKey) | Identifies the structure key. |
## Methods

| Method | Description |
| --- | --- |
| [<T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)](#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Finds the structure by key name value. |
| [<T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)](#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Finds the structure by key name value. |
| [arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)](#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-) | Arranges structures to one dictionary by key name. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataLength()](#getDataLength--) | Gets the exact data length in bytes. |
| [getFullPath()](#getFullPath--) | Gets or sets the full path. |
| [getHeaderLength()](#getHeaderLength--) | Gets the header length. |
| [getKey()](#getKey--) | Gets the structure key. |
| [getKeyName()](#getKeyName--) | Gets or sets the key name. |
| [getLength()](#getLength--) | Gets the [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) length in bytes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)](#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Find and removes structure from the input items list. |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Saves the structure to the specified stream container. |
| [saveWithoutKeyName(StreamContainer streamContainer)](#saveWithoutKeyName-com.aspose.psd.StreamContainer-) | Saves the structure to the specified stream container. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | Gets or sets the full path. |
| [setKeyName(ClassID value)](#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Gets or sets the key name. |
| [setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)](#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Add or update the structure to input items list. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AliasStructure(ClassID keyName) {#AliasStructure-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public AliasStructure(ClassID keyName)
```


Initializes a new instance of the [AliasStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/aliasstructure) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyName | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | The key name. |

### StructureKey {#StructureKey}
```
public static final int StructureKey
```


Identifies the structure key.

### <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container) {#-T-findByKeyName-from-placed-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public static T <T>findByKeyName_from_placed_internalized(String keyName, PlacedResource container)
```


Finds the structure by key name value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyName | java.lang.String | The key name. |
| container | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | The items container to search in.

 T : The type of result object. |

**Returns:**
T - The structure by key name value.
### <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items) {#-T-findByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static T <T>findByKeyName_internalized(String keyName, System.Collections.Generic.IGenericList<OSTypeStructure> items)
```


Finds the structure by key name value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyName | java.lang.String | The key name. |
| items | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | The items to search in.

 T : The type of result object. |

**Returns:**
T - The structure by key name value.
### arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix) {#arrangeToDictionary-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--java.lang.String-}
```
public static System.Collections.Generic.Dictionary<String,OSTypeStructure> arrangeToDictionary_internalized(OSTypeStructure[] structures, System.Collections.Generic.Dictionary<String,OSTypeStructure> dictionary, String prefix)
```


Arranges structures to one dictionary by key name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structures | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structures |
| dictionary | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | The dictionary to arrange |
| prefix | java.lang.String | The prefix for key names. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Arranged structures as dictionary by key name.
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
### getDataLength() {#getDataLength--}
```
public final int getDataLength()
```


Gets the exact data length in bytes.

Value: The data length in bytes.

**Returns:**
int
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


Gets or sets the full path.

Value: The full path.

**Returns:**
java.lang.String
### getHeaderLength() {#getHeaderLength--}
```
public int getHeaderLength()
```


Gets the header length.

**Returns:**
int - The header length
### getKey() {#getKey--}
```
public int getKey()
```


Gets the structure key.

**Returns:**
int
### getKeyName() {#getKeyName--}
```
public final ClassID getKeyName()
```


Gets or sets the key name.

Value: The key name.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getLength() {#getLength--}
```
public int getLength()
```


Gets the [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) length in bytes.

**Returns:**
int
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




### removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items) {#removeByKeyName-internalized-java.lang.String-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void removeByKeyName_internalized(String keyName, System.Collections.Generic.List<OSTypeStructure> items)
```


Find and removes structure from the input items list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyName | java.lang.String | The key name. |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | The items. |

### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Saves the structure to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |

### saveWithoutKeyName(StreamContainer streamContainer) {#saveWithoutKeyName-com.aspose.psd.StreamContainer-}
```
public final void saveWithoutKeyName(StreamContainer streamContainer)
```


Saves the structure to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


Gets or sets the full path.

Value: The full path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setKeyName(ClassID value) {#setKeyName-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setKeyName(ClassID value)
```


Gets or sets the key name.

Value: The key name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items) {#setToList-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public static void setToList_internalized(OSTypeStructure structure, System.Collections.Generic.List<OSTypeStructure> items)
```


Add or update the structure to input items list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The structure to add update. |
| items | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> | The items. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

