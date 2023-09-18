---
title: SmartResourceCreator
second_title: Aspose.PSD for Java API Reference
description: Defines the SmartResourceCreator class that can create PlLd SoLd and SoLe resources.
type: docs
weight: 14
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator/
---

**Inheritance:**
java.lang.Object
```
public class SmartResourceCreator
```

Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources. Is is used to support smart object layers in the Adobe\\ufffd Photoshop\\ufffd images.
## Constructors

| Constructor | Description |
| --- | --- |
| [SmartResourceCreator()](#SmartResourceCreator--) | Initializes a new instance of the [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) class. |
| [SmartResourceCreator(boolean isCustom, boolean hasCompInfo)](#SmartResourceCreator-boolean-boolean-) | Initializes a new instance of the [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) class. |
| [SmartResourceCreator(PlacedResource template)](#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initializes a new instance of the [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) class with the given template. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generatePlacedResource()](#generatePlacedResource--) | Generates the placed resource. |
| [generateSmartEmbeddedResource()](#generateSmartEmbeddedResource--) | Generates the embedded smart object resource. |
| [generateSmartExternalResource()](#generateSmartExternalResource--) | Generates the external smart object resource. |
| [getClass()](#getClass--) |  |
| [getTemplate_internalized()](#getTemplate-internalized--) | Gets or sets the smart object resource template. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartResourceCreator() {#SmartResourceCreator--}
```
public SmartResourceCreator()
```


Initializes a new instance of the [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) class.

### SmartResourceCreator(boolean isCustom, boolean hasCompInfo) {#SmartResourceCreator-boolean-boolean-}
```
public SmartResourceCreator(boolean isCustom, boolean hasCompInfo)
```


Initializes a new instance of the [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isCustom | boolean | if set to  true  [is custom]. |
| hasCompInfo | boolean | if set to  true  [has comp information]. |

### SmartResourceCreator(PlacedResource template) {#SmartResourceCreator-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public SmartResourceCreator(PlacedResource template)
```


Initializes a new instance of the [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) class with the given template.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| template | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | The smart object resource template. |

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
### generatePlacedResource() {#generatePlacedResource--}
```
public final PlLdResource generatePlacedResource()
```


Generates the placed resource.

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) - The generated [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) instance.
### generateSmartEmbeddedResource() {#generateSmartEmbeddedResource--}
```
public final SoLdResource generateSmartEmbeddedResource()
```


Generates the embedded smart object resource.

**Returns:**
[SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) - The generated [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource) instance.
### generateSmartExternalResource() {#generateSmartExternalResource--}
```
public final SoLeResource generateSmartExternalResource()
```


Generates the external smart object resource.

**Returns:**
[SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) - The generated [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) instance.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTemplate_internalized() {#getTemplate-internalized--}
```
public final SmartObjectResource getTemplate_internalized()
```


Gets or sets the smart object resource template.

Value: The smart object resource template.

**Returns:**
[SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
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

